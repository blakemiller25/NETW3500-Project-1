# Installing Applications Using System Configuration Manager

1. Getting the apps or app that you would like to install
Make sure that the package that you try to use for deployment is .msi, .appx, .appxbundle, .msix, .msixbundle. Or convert your exe to one of the app extensions that I had listed.
![Wire Shark install](_images/Wireshark-Install.png)
I am going to be using wireshark for my example.

2. Make a folder that you will share on the network.
![Folder Creation](_images/Folder-Creation.png)

3. Right click on the folder that you just created and select properties.
![Setup Network Share](_images/Folder-Properties.png)

4. Click on Share
![Share](_images/Share.png)

5. Copy the msi file to the network share folder
![App in the Network Share](_images/App-In-Network-Share.png)

6. In the network access click on share. Then click done
![Nework Access](_images/Network-Access.png)

7. Opening Configuration Manager Console
You will now want to navigate to your search bar and search for Configuration Manager Console and open it.
![Configuration Manager](_images/Configuration-Manager-Console.png)
There will be a windows that pops up and will have a dahsbaord like interface on it.

8. In the bottom left of Configuration Manager Console click on software libary.
![Software Libary](_images/Select-Software-Libary.png)

9. Right click on applications and select create application.
![Create Application](_images/Create-Application.png)

10. Browse to the application that is in your network share folder. then click next.
![Browse to Application](_images/Browse-to-Application.png)

11. Next again on the general information.

12. Set the installation Properties for the install in general information. The next option you can just click next on. Then close.
![Installation Properties](_images/Installation-Properties.png)

13. Right click on the new application and select Distribute Content.
![Distribute Content](_images/Distribute-Content.png)

14. In the Content Destination click on the add button. And select Distibution Point
![Add Button](_images/Add-Button.png)

15. Select the server that you are going to deploy from. Then Click Ok then next
![Distribution Point](_images/Distribution-Menu.png)

16. On the Deployment setting page set the purpose to install.
![Purpose](_images/Purpose.png)

17. In the summary click next. The Close on the completion.

18. Right click on the application and select deploy.
![Deploy](_images/Deploy.png)

19. In the General settings select the browse next to collection.
![Collection](_images/Collection.png)

20. Now you will select the users that will have access to the deployment. I'm going to deploy to all users. Then click Ok and then next.
![Users](_images/Select-Users.png)

21. In content select next, Deployment settings select next, In scheduling you can specify when the application can be made available for me I'm not going to set that then click next. User experience click next. Alerts click next if you dont need them. On summary click next then close.

22. You will then want to login to a user in the domain on a client machine.
![Login](_images/Login-to-client-machine.png)

23. Open control panel and go to system and security.
![Control Panel](_images/Control-Panel.png)

24. You will then want to go to configuration manager at the bottom of the page
![Configuration Manager](_images/Configuration-manager.png)

25. you will want to select the **Actions** tab then select **Machine Policy Retrieval & Evaluation Cycle**. Then once selected click run now.
![Machine Policy](_images/Machine-Policy.png)

26. On the bottom right of your screen you will get a notification saying that you IT department requires changes to the device.
![Notification](_images/Notification.png)

27. The application will automatically download and install in the background once it is done it will have a notification that will pop up in the lower right hand corner saying that it finished downloading and installing.

28. Now you can launch the app and use it.
![Done](_images/Can-Search.png)

![Launched App](_images/Wireshark.png)