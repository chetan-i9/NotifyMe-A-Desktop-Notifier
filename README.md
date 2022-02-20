# NotifyMe-A-Desktop-Notifier

A desktop notifier, is a simple application which produces a notification pop-up message on desktop. These desktop notifications provide simple and effortless access to various information regarding emergency alerts, news, reports, etc.

The application delivers information right to ones desktop, allowing you to safely receive important information that is relevant and preferred by the user. Flexible formats can be personalized with your branding and adapted for your needs, including direct on-screen alerts or smaller pop-up notifications.

The project **“Notify Me”** is simple desktop notifying application that connects the user with the around world through providing news and weather updates.

_**Introduction**_

In this tech world, everyone is using technology in some or the other means i.e. right from the morning till going to bed at night. Laptops and Desktops have become a part and an important content of ones office/college bags and work desks, respectively. Due to high work commitments and busy schedules of students and employees of various companies , lot of them are not aware of the latest news & updates of the world. The **“NotifyMe”** is an user friendly solution which illustrates these needs and wants of desktop users that were identified in brainstorming exercise as apart of requirement for their devices.

_**Scope**_

Primarily, the scope retains to the news notifying features for providing the user with the updates without disturbing their works, saving their precious time. It focuses on the user preferences and needs which makes this application an user-friendly solution.

_**Purpose**_

The purpose of this document is to collect and analyze all assorted ideas that have come up to define the application, its requirements with respect to users. Also, we shall predict and sort out how we hope this application will be used in order to gain a better understanding of the project, outline concepts that may be developed later, and document ideas that are being considered. Also, describes the project's target audience and its user interface, hardware and software requirements

_**Software Requirements Specifications**_

**Functionality** - The application displays pop-up notifications as per the user-preferences for the news and weather updates. User is allowed to choose his/her preferences according to ones needs Which includes- 
1. Time interval-At what interval one wants to see updates pop-ups.
2. Location-provides options for different geographical locations. 
3. Interests-like sports, entertainment, politics etc.
4. Languages- different language options for the news is Available too.
5. Requires no user data and no login option.

**Usability** 

1._Graphical User Interface_ - The application provides simple and uniform look between different windows. Also, provides use of dropdown boxes for selection of options and auto      suggests the options while taking input through keyboard.

2._Performance_ - The application may take initial load time depending on internet connection strength which also depends on the media from which the application is run. The   performance also depends upon hardware components of the user.

3._Data Transfer and Storage_ - No accessing of confidential information, passwords and any cookies involved.

**Design/Implementation**

1._Standard Development Tool_ - The application is built using **Python programming language** and its features like tkinter, win10toast, requests and gnewsclient. The python script extracts news from Google News feed by using gnews module , and also extracts weather forecast using API of openweather.com.

    i) Gnews Client gnewsclient is a python client for Google News Feed from where the application extracts news articles.

    ii) API [Application Programming Interface] It is a server that you can use to retrieve and send data to using code. They are most commonly used to retrieve data.In this application, we used openweather.com’s api for retrieving weather details.

    iii) GUI [ Graphical User Interface] Python offers multiple options for developing GUI (Graphical User Interface). Out of all the GUI methods, tkinter is the most commonly used method.It is a standard Python interface to the Tk GUI toolkit shipped with Python. Python with tkinter outputs the fastest and easiest way to create the GUI applications.

    iv) Windows 10 Toast Library-An easy-to-use Python library for displaying Windows 10 Toast Notifications which is useful for Windows GUI development.

    v) Requests -Requests is a simple, yet elegant HTTP library.It is ready for the demands of building robust and reliable HTTP–speaking applications, for the needs of today.
       >Keep-Alive & Connection Pooling 
       >International Domains and URLs 
       >Sessions with Cookie Persistence 
       >Browser-style TLS/SSL Verification  
       >Basic & Digest Authentication
       >Familiar dict–like Cookies 
       >Automatic Content Decompression and Decoding  
       >Multi-part File Uploads and SOCKS Proxy Support 
       >Connection Timeouts
       >Streaming Downloads  
       >Chunked HTTP Request

2._Basic Requirements_

 A general knowledge of basic computer skills is required to use the application. 
 
 Python and required packages and modules should be installed to run this application. 
 
 Propper Internet Connection. 
 
 Response time for loading the application should take no longer than five minutes.
 
