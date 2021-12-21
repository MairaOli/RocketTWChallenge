# API Upload

This API controls the upload of files on live chats.

**Document version:** 1.0.0



With **Rocket.Chat** users are able to upload files into live chats by simply dragging and dropping.

![Drop and drag file](C:\Users\maira.oliveira\OneDrive - ACRELEC\Área de Trabalho\Rocket Chat\Gif_Upload\Gif_Upload.gif)



The **Upload API** checks the following conditions:

<ul><li>Visitor token for authentication</li><li>Room ID (for an active chat room)</li><li>File size</li><li>File type (format)</li><li>File details</li><ul>

If the permissions are correct and the file specifications are met, the system proceeds to upload the file as configured in the **File Upload** menu (**Administration > File Upload**).

If the files do not match the required conditions, the system returns an error message informing what was wrong, as in the example below:

![Error message: Media type not accepted](C:\Users\maira.oliveira\OneDrive - ACRELEC\Área de Trabalho\Rocket Chat\Rocket3.jpg)



> If you are not able to upload a file into the live chat check the upload configurations or contact our support tea.
