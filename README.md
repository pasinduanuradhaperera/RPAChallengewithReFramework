# RPA Challenge - Simple Demo using UiPath REFramework
![UiPath REFramework](https://img.shields.io/badge/UiPath-REFramework-blue?style=for-the-badge&logo=uipath)
![RPA Challenge](https://img.shields.io/badge/Challenge-rpachallenge.com-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green)

<img src="https://uipath.com/cdn-cgi/image/format=auto/https:////images.ctfassets.net/5965pury2lcm/5K5FiWrn71nr0bHEYAqKlk/fe2f95aa97cc0bd100c0087f6669230b/Robot_Accent_8.png" 
     alt="UiPath Logo" height="150">
<img src="https://i.pinimg.com/736x/31/4b/96/314b960aa8fee08076b6f2db5e80ca4c.jpg" 
     alt="rpachallenge.com" height="150">
     <img src="https://global.discourse-cdn.com/uipath/original/4X/b/7/a/b7ae33f10e3fd3e230956cb9153a063eb24f9e17.png" 
     alt="ReFrameWork" height="150">


> A clean, beginner-friendly demo project that solves the **[rpachallenge.com](https://rpachallenge.com)** using the official **UiPath Robotic Enterprise Framework (REFramework)**.

This project is designed to be **easy to understand**, well-commented, and ready for you to edit and adapt to your own automation projects.

---

### What is **rpachallenge.com** [Read More...](RPACHALLENGE.md)?

### What is **REFramework** [Read More...](REFRAMEWORK.md)?

---

## How This Demo Works

1. **Initialization**  
   - Opens browser to http://rpachallenge.com 
   - Reads all rows into a DataTable (TransactionItems)

2. **Get Transaction Data**
   - Load Data One by One to a DataRow.

3. **Process Transaction**  
   - Takes one person from the queue  
   - Fills the 7 fields: First Name, Last Name, Company, Role, Address, Email, Phone  
   - Clicks Submit  
   - Handles retries if something fails

4. **End Process**  
   - Takes screenshot of final score  and save the final message text.
   - Closes browser

---

## Screenshots (Add these paths to your project folder or replace paths inside the ***[Config.xlsx](Data\Config.xlsx)***)

```markdown
[ScreenShot](ScreenShot)
[ErrorScreenShot](ErrorScreenShot)
[Exceptions_Screenshots](Exceptions_Screenshots)
```

## How to Run

### !!! important :- Please Allow Uipath Extention to run on Incognito mode change if needed.
### !!! important :- This Automation Default Runs On Chrome change if Needed.
### !!  important :- Please Create above ScreenShot Paths in your project.
### !   important :- Please insert the input file to your input file location.
```
Open the project in UiPath Studio (2021.10 or newer recommended)
follow the basic Uipath Web Automation prerequests

Update Data\Config.xlsx → Sheet "Settings":
   input_File → input file location
   Sheet_Name → default downloded file's sheet name is Sheet1
   WebsiteURL → keep as it is or update to https://rpachallenge.com/
   ScreenShotsPath → update to you location
   ErrorScreenShotsPath → update to you location
   Output_Location → update to you location

Press Run (F5) or run it manually
That's it!
```

### Customization Tips

- Add delay if your internet/machine is slow
- Use Orchestrator Queue instead of in-memory queue
- Add email notification on completion
- Upload final screenshot to Orchestrator or SharePoint


## License
[MIT License](LICENSE) – Feel free to use, modify, and share.

Happy Automating!
Made with ❤️ for the UiPath community

<img src="https://uipath.com/cdn-cgi/image/format=auto/https:////images.ctfassets.net/5965pury2lcm/5K5FiWrn71nr0bHEYAqKlk/fe2f95aa97cc0bd100c0087f6669230b/Robot_Accent_8.png" alt="UiPath Logo" style="max-height:150px;">

