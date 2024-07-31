# SpringSecurity


filtering directories on your website
@Bean
    SecurityFilterChain defaultSecurityFilterChain(HttpSecurity http) throws Exception {
        http.authorizeHttpRequests((requests) -> requests
                .requestMatchers("/getBalance").authenticated()//you first get a login form
                .requestMatchers("/getAccount").permitAll());//you dont get a login form, you get directed through without login form
        http.formLogin(withDefaults());
        http.httpBasic(withDefaults());
        return http.build();
    }
