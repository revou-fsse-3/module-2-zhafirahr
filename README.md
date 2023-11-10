# Week 4 Assignment
## Case Study: HoHoLand Online Zoo
HoHoLand Online Zoo is a web to appreciate all of cute creatures in Hoyoverse game~
## Tasks
We will deploy it with Niagahoster 
====================================
### PS: Link week 3 [Link](https://hohoverse-up1.netlify.app/)
## Deployment
1. The website was deployed using Netlify, with a custom domain from Niagahoster.
![image](assets/Screenshot%202023-11-10%20215042.png)
![image](assets/Screenshot%202023-11-10%20221140.png)
2. To ensure seamless integration between Github and Netlify, connect your Netlify account with Github, and choose to deploy from your Github repository. This ensures that Netlify will automatically initiate deployments whenever there are any changes in your GitHub repository.
3. Cloudflare, a content delivery network (CDN), was employed to optimize the website's performance and provide enhanced security.
![image](assets/Screenshot%202023-11-10%20215549.png)
4. I used a domain I've already bought and set up for another website long ago. Therefore, what's left is only redirecting it to a different website.
5. It can be done by changing the target field to a different website and deleting the old one. I also use the CNAME type because it is easier for Netlify.
![image](assets/Screenshot%202023-11-10%20221410.png)
![image](assets/Screenshot%202023-11-10%20221432.png)
6. Afterwards, add another record with CNAME type, fill the name field with www, and target it to the custom domain website.
7. Next, in Netlify, delete the used custom domain on the old website, and click "Add Domain" on your new website in the domain settings menu.
![image](assets/Screenshot%202023-11-10%20222117.png)
8. Follow the instructions to add the custom domain. The finished result will look like this.
![image](assets/Screenshot%202023-11-10%20221941.png)
![image](assets/Screenshot%202023-11-10%20222150.png)
9. Wait for a few minutes, and there we go~
### PS: Link week 4 [Link](https://hohoverse-up1.placeblog.site/)
