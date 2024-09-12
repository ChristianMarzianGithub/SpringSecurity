<h1>SpringSecurity Notes</h1>


<h2>1. Filtering directories on your website</h2>

![image](https://github.com/user-attachments/assets/653fea61-d871-4444-8512-babc8b356d90)


<h2>2. Testing your api with postman</h2>

<h2>3. Setting default usr/pw in properties</h2>
add that to your application.properties file:
</br>
<i>
  spring.security.user.name=${SECURITY_USERNAME:eazybytes}
  </br>
  spring.security.user.password=${SECURITY_PASSWORD:12345}
</i>

<h2>4. create different users</h2>

![image](https://github.com/user-attachments/assets/a93dee25-12c2-4427-8dc8-9ff36b670690)


<h2>5. persist users with credentials in db</h2>

![image](https://github.com/user-attachments/assets/e21be990-e4c8-4d2e-8d6b-25353a76bf1d)


![image](https://github.com/user-attachments/assets/99bc7daa-3265-4699-8e8c-6a5b9822ffd7)


![image](https://github.com/user-attachments/assets/0d33bc3f-bb86-4264-b9a4-f29fdf2b48cb)

![image](https://github.com/user-attachments/assets/72415380-80eb-430d-a4f1-f9011bed0d7e)

<h2>6. custom form login</h2>
=> Tutorial video 60 bis 64
or slide in the pdf 60 to 65

<h2>7. defining Roles and Authorities/ Listening to AuthorityEvents</h2>

<h2>8. custom form login</h2>

<h2>9. adding a custom Filter to the FilterChain</h2>

<h2>10. JWT-token based Authentication</h2>
<h2>11. Method-Level Security</h2>
<ol>
    <h3>Authorization</h3>
    <ol>
    <li>@PreAuthorize</li>  
    <li>@PostAuthorize</li>  
    </ol>
    <h3>Filtering Autorization</h3>
    <ol>
      <li>
        PreFilter  
      </li>  
      <li>
        PostFilter  
      </li>      
    </ol>
</ol>


