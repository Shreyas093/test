
TEST SCENARIOS FOR E-Commerce Web Application:-

HOW DO U TEST A LOGIN PAGE?
1.	Verify that all the labels and controls including text-boxes, buttons, and links are present on the Login page.
2.	Verify that the font type and size of the labels and the text written on the different elements should be clearly visible.
3.	Verify that the size, color, and UI of the different elements are as per the specifications. 
4.	Verify that the application’s UI is responsive i.e. it should adjust to different screen resolutions and devices.
Test Scenarios for Login Page
1.	Verify that as soon as the login page opens, by default the cursor should remain on the username textbox.
2.	Verify that the user is able to navigate or access the different controls by pressing the ‘Tab’ key on the keyboard.
3.	Verify that the password is in masked form when entered.
4.	Verify if the password can be copy-pasted or not.
5.	Verify that the user is able to login by entering valid credentials and clicking on the ‘Login’ button.
6.	Verify that the user is able to login by entering valid credentials and pressing Enter key.
7.	Verify that the user is not able to login with an invalid username and password.
8.	Verify that the validation message gets displayed in case the user leaves the username or password field as blank.
9.	Verify that the validation message is displayed in the case the user exceeds the character limit of the user name and password fields.
10.	Verify that reset button functionality on the login page. Clicking on it should clear the textbox’s content.
11.	Verify if there is a checkbox with the label “remember password” on the login page.
12.	Verify that closing the browser should not log-out an authenticated user. Launching the application should lead the user to login state only.


HOW DO U TEST A REGESTRATION PAGE???

1.	Verify that all the specified fields are present on the registration page.
2.	Verify that the required/mandatory fields are marked with * against the field.
3.	Verify that for better user interface dropdowns, radio buttons and checkboxes, etc fields are displayed wherever possible instead of just text boxes.
4.	Verify the page has both submit and cancel/reset buttons at the end.
5.	Verify that clicking submits button after entering all the required fields, submits the data to the server.
6.	Verify that clicking cancels/reset button after entering all the required fields, cancels the submit request, and reset all the fields.
7.	Verify that whenever possible validation should take place at the client-side.
8.	Verify that not filling the mandatory fields and clicking the submit button will lead to a validation error.
9.	Verify that not filling the optional fields and clicking the submit button will still send data to the server without any validation error.
10.	Check the upper limit of the textboxes.
11.	Check validation on the date and email fields (only valid dates and valid email Ids should be allowed.
12.	Check validation on numeric fields by entering alphabets and special characters.
13.	Verify that leading and trailing spaces are trimmed.
14.	Verify that entering blank spaces on mandatory fields leads to the validation error.
15.	Verify that after making a request to the server and then sending the same request again with the same unique key will lead to the server-side validation error.


HOW DO YOU TEST ECOMMERCE APPLICATION?
1.	Verify that the user is able to navigate through all the products across different categories.
2.	Verify that all the links and banners are redirecting to correct product/category pages and none of the links are broken.
3.	Verify that the company logo is clearly visible.
4.	Verify that all the text – product, category name, price, and product description are clearly visible.
5.	Verify that all the images – product and banner are clearly visible.
6.	Verify that category pages have a relevant product listed specific to the category.
7.	Verify that the correct count of total products is listed on the category pages.
8.	Search – Verify that on searching all the product satisfying the search criteria are visible on the search result page.
9.	Search – Verify the more relevant product for the search term is displayed on the top for a particular search term.
10.	Search – Verify that count of products is correctly displayed on the search result page for a particular search term.
11.	Filtering – Verify that filtering functionality correctly filters products based on the filter applied.
12.	Filtering – Verify that filtering works correctly on category pages.
13.	Filtering – Verify that filtering works correctly on the search result page.
14.	Filtering – Verify that the correct count of total products is displayed after a filter is applied.
15.	Sorting – Verify that all the sort options work correctly – correctly sort the products based on the sort option chosen.
16.	Sorting – Verify that sorting works correctly on the category pages.
17.	Sorting – Verify that sorting works correctly on the search result page.
18.	Sorting – Verify that sorting works correctly on the pages containing the filtered result, after applying filters.
19.	Sorting – Verify that product count remains intact irrespective of sorting option applied.
Product Buy Flow – Test cases for Ecommerce Website
1.	Verify that on the product page, the user can select the desired attribute of the product e.g. size, color, etc.
2.	Verify that the user can add to cart one or more products.
3.	Verify that users can add products to the wishlist.
4.	Verify that the user can buy products added to the cart after signing in to the application (or as per the functionality of the website).
5.	Verify that the user can successfully buy more than one product that was added to his/her cart.
6.	Verify that the user cannot add more than the available inventory of the product.
7.	Verify that the limit to the number of products a user can by is working correctly by displaying an error message and preventing the user from buying more than the limit.
8.	Verify that the delivery can be declined for the places where shipping is not available.
9.	Verify that the Cash on Delivery option of payment is working fine.
10.	Verify that the different pre-paid methods of payments are working fine.
11.	Verify that product return functionality works fine.
User(Buyer) Registration – Test cases
1.	Verify that all the specified fields are present on the registration page.
2.	Verify that the required/mandatory fields are marked with * against the field.
3.	Verify that for better user interface dropdowns, radio buttons and checkboxes, etc fields are displayed wherever possible instead of just textboxes
4.	Verify the page has both submit and cancel/reset buttons at the end.
5.	Verify that clicking submits button after entering all the required fields, submits the data to the server.
6.	Verify that clicking cancels/reset button after entering all the required fields, cancels the submit request, and reset all the fields.
7.	Verify that whenever possible validation should take place at client side
8.	Verify that not filling the mandatory fields and clicking the submit button will lead to validation error.
9.	Verify that not filling the optional fields and clicking the submit button will still send data to the server without any validation error.
10.	Check the upper limit of the textboxes.
11.	Check validation on the date and email fields (only valid dates and valid email Ids should be allowed.
12.	Check validation on numeric fields by entering alphabets and special characters.
13.	Verify that leading and trailing spaces are trimmed.
14.	Verify that entering blank spaces on mandatory fields leads to validation error.
15.	Verify that after making a request to the server and then sending the same request again with the same unique key will lead to server-side validation error.
Seller – Product creation Test cases
1.	Verify that authenticated sellers get access to product creation panels specific to the authorized categories.
2.	Verify that the product creation panel is working fine for single product creation.
3.	Verify that the product creation panel is working fine for multiple product creation.
4.	Verify that the maximum product creation limit for the seller is working fine, limiting the seller to create more than the desired number of products.
5.	Verify panel validation for checking mandatory fields.
6.	Verify that duplicate product creation is restricted through the panel.
7.	Verify that seller can update the information and price of existing products.
8.	Verify that products created by sellers get visible on the website after a certain period of time.
9.	Verify that updates made by the seller get visible on the website after a certain period of time.

HOW DO YOU TEST GOOGLE SEARCH?
1.	Verify that the response fetched for a particular keyword is correct and related to the keyword, containing links to the particular webpage
2.	Verify that the response are sorted by relevancy in descending order i.e. most relevant result for the keyword are displayed on top
3.	Verify that response for multi word keyword is correct
4.	Verify that response for keywords containing alphanumeric and special characters is correct
5.	Verify that the link title, URL and description have the keyword highlighted in the response
6.	Verify auto-suggestion in Google e.g. providing input as ‘fac’ should give suggestions like ‘facebook’, ‘facebook massenger’, ‘facebook chat’ etc
7.	Verify that response fetched on selecting the suggested keyword and on providing the keyword directly should be same
8.	Verify that the suggestion provided by Google are sorted by most popular/relevant suggestions
9.	Verify that user can make search corresponding to different categories – web, images, videos, news, books etc and response should correspond to the keyword in that category only
10.	Verify that misspelled keyword should get corrected and response corresponding to the correct keyword should get displayed
11.	Verify that multi word misspelled keywords also get corrected
12.	Verify the performance of search- check if the time taken to fetch the response is within the ballpark
13.	Verify that total number of results fetched for a keyword
14.	Verify that the search response should be localised that is response should be more relevant to the country/area from which the search request is initiated
15.	Verify Google calculator service- make any arithmetic request, calculator should get displayed with correct result
16.	Verify Google converter service- make request like- 10USD in INR and check if the result is correct
17.	Verify search response for a large but valid strings
18.	Verify that incorrect keywords – keywords not having related result should lead to “did not match any documents” response
19.	Verify that user can make search using different languages
20.	Verify that for a keywords, some related search terms are also displayed to aid user’s search
21.	Verify that for number of results more than the limit on a single page, pagination should be present, clicking on which user can navigate to subsequent page’s result
22.	Verify Google’s advanced search options like- searching within a website, searching for files of specific extension
23.	Verify if the search is case-insensitive or not
24.	Verify the functionality of “I’m feeling Lucky” search- the top most search result should get directly returned (but as of now google doodle page link is displayed)
UI Test Cases for Google Search
1.	Verify that Google Logo is present and centre aligned
2.	Verify that the search textbox is centre aligned and editable
3.	Verify that search request should get hit by clicking on search button or hitting enter after writing the search term
4.	Verify that in the search result- webpage’s title, URL and description are present
5.	Verify that clicking the search result will lead to the corresponding web page
6.	Verify that pagination is present in case number of results are greater than the maximum results allowed in a page
7.	Verify that user can navigate to a page number directly or move to previous or next page using the links present
8.	Verify that different languages links are present and gets applied on clicking the same
9.	Verify that the total number of results for the keyword is displayed
10.	Verify that the time taken to fetch the result is displayed


HOW TO DO YOU TEST GMAIL?
Test Case for Gmail – Inbox Functionality
1.	Verify that a newly received email is displayed as highlighted in the Inbox section.
2.	Verify that a newly received email has correctly displayed sender email Id or name, mail subject and mail body(trimmed to a single line).
3.	Verify that on clicking the newly received email, the user is navigated to email content.
4.	Verify that the email contents are correctly displayed with the desired source formatting.
5.	Verify that any attachments are attached to the email and are downloadable.
6.	Verify that the attachments are scanned for viruses before download.
7.	Verify that all the emails marked as read are not highlighted.
8.	Verify that all the emails read as well as unread have a mail read time appended at the end on the email list displayed in the inbox section.
9.	Verify that count of unread emails is displayed alongside ‘Inbox’ text in the left sidebar of Gmail.
10.	Verify that unread email count increases by one on receiving a new email.
11.	Verify that unread email count decreases by one on reading an email ( marking an email as read).
12.	Verify that email recipients in cc are visible to all users.
13.	Verify that email recipients in bcc are not visible to the user.
14.	Verify that all received emails get piled up in the ‘Inbox’ section and get deleted in cyclic fashion based on the size availability.
15.	Verify that email can be received from non-Gmail email Ids like – yahoo, Hotmail etc.
Test Cases for GMail – Compose Mail Functionality
1.	Verify that on clicking ‘Compose’ button, a frame to compose a mail gets displayed.
2.	Verify that user can enter email Ids in ‘To’, ‘cc’ and ‘bcc’ sections and also user will get suggestions while typing the emailds based on the existing emailIds in user’s email list.
3.	Verify that the user can enter multiple comma-separated emailIds in ‘To’, ‘cc’ and ‘bcc’ sections.
4.	Verify that the user can type Subject line in the ‘Subject’ textbox.
5.	Verify that the user can type the email in the email-body section.
6.	Verify that users can format mail using editor-options provided like choosing font-family, font-size, bold-italic-underline, etc.
7.	Verify that the user can attach file as an attachement to the email.
8.	Verify that the user can add images in the email and select the size for the same.
9.	Verify that after entering emailIds in either of the ‘To’, ‘cc’ and ‘bcc’ sections, entering Subject line and mail body and clicking ‘Send’ button, mail gets delivered to intended receivers.
10.	Verify that sent mails can be found in ‘Sent Mail’ sections of the sender.
11.	Verify that mail can be sent to non-gmail emailIds also.
12.	Verify that all sent emails get piled up in the ‘Sent Mail’ section and get deleted in cyclic fashion based on the size availability.
13.	Verify that the emails composed but not sent remain in the draft section.
14.	Verify the maximum number of email recipients that can be entered in ‘To’, ‘cc’ and ‘bcc’ sections.
15.	Verify the maximum length of text that can be entered in the ‘Subject’ textbox.
16.	Verify the content limit of text/images that can be entered and successfully delivered as mail body.
17.	Verify the maximum size and number of attachment that can be attached with an email.
18.	Verify that only the allowed specifications of the attachment can be attached with an email/
19.	Verify that if the email is sent without Subject, a pop-up is generated warning user about no subject line. Also, verify that on accepting the pop-up message, the user is able to send the email..

HOW DO YOU TEST YOUTUBE?
Test Scenerios for Video Uploader Functionality
1.	Verify that user can upload single video or allowed format and size successfuly.
2.	Verify that while uploading user should select the video license and type of video along with its attributes like- name, artsist name, company etc.
3.	Verify the maximum size of video that is permitted to upload and check that any attempt to upload video of size greater than the allowed value results in an error message.
4.	Verify if there is any minimum size of video that is permitted to upload and any attempt to upload file size less than specified results in error message.
5.	Verify all the video formats that are allowed to upload – .mp4, .3gp, .avi etc and check that uploading file formats other that alllowed results in error message.
6.	Verify that uploading blank file should result in error message.
7.	Verify that user can upload multiple videos or allowed format and sie successfuly.
8.	Verify that upladers get notification of comments posted on the videos uploaded by them.
9.	Verify that user can view likes, dislikes and comments for their videos.
10.	Verify that user can reply to the comments posted in their videos.
Test scenarios for Video Viewing Functionality
1.	Verify that video page can be opened by direct link to a video.
2.	Verify that on cliking the video play icon over the video, the video should play.
3.	Verify all the video player controls- play, pause, volume, mute etc.
4.	Verify that user can select the allowed video quality for playing the video.
5.	Verify that once the video is complete, user can replay the video using ‘replay’ icon.
6.	Verify that video should be searchable by name, displaying the most relevant video on the top in search results.
7.	Verify that other attributes of video like artist name, description should also be searchable.
8.	Verify that user should get auto suggestions while searching for videos in the youtube search bar.
9.	Verify that search results should display information like video name, thumbnail, video length, view counts etc.
10.	Verify that clicking the video thumbnails in the search results should lead to video page.
11.	Verify that video filtering and sorting option while searching for video like – sort be view count, like, upload date etc.
12.	Verify that user can view ‘view count’, ‘comments’, ‘like’ and ‘dislikes’ for a video.
13.	Verify that with each view the ‘view count’ increases by one.
14.	Verify that user can like or dislike a video and the corresponding count should increase by one.
15.	Verify that user can comment in the comments section.
16.	Verify that user should be presented with related videos in the sidebar section.
17.	Verify that the related videos are related to the current video or is based on the past viewing history of user.
18.	Verify that clicking rleated video thumbnail should open the video.
19.	Verify that for age restricted video, user is asked to login to youtube account.
20.	Verify that logged-in user should see there history as well as recommended videos in the home page.
21.	Verify that every video viewed goes to history for logged in user..
22.	Verify that user can view or delete history items.
 

User Timeline Test Cases for Facebook
1.	Verify that user can set profile pic uploaded from his or her computer.
2.	Verify that user can set profile pic uploaded from mobile.
3.	Verify that uer can set profile pic from photos present on his facbook account’s photo section.
4.	Verify that user can set profile from webcam or mobile camera.
5.	Verify that user can set cover pic uploaded from his or her computer.
6.	Verify that user can set cover pic uploaded from mobile.
7.	Verify that user can set cover pic from photos present on his facbook account’s photo section.
8.	Verify that user can set cover from webcam or mobile camera.
9.	Verify that uploading image of unsupported type should lead to error message.
10.	Verify that uploading image of size exceeding maximum allowed size should lead to error message.
11.	Verify that uploading image of size less than the allowed minimum size should lead to error message.
12.	Verify that uploading image of larger dimension than permitted should lead to error message.
13.	Verify that uploading image of smaller dimension than permitted should lead to error message.
14.	Verify that change in profile pic should get reflected in each post/comment of the user’s timeline.
15.	Verify that user can add/edit their account information displayed to other users.
16.	Verify that users can post text in their timeline and the same gets displyed to their friends.
17.	Verify that users can post images in their timeline and the same gets displyed to their friends.
18.	Verify that users can post links with or without preview in their timeline and the same gets displayed to their friends.
19.	Verify that user can tag friends in their posts.
20.	Verify that users can see the all the post in their timeline.
21.	Verify that users can see comments, likes and reactions in the posts present in their timeline.
22.	Verify that users can post comments, like and react to the posts present in their timeline.


HOW DO YOU TEST FACEBOOK?
Friends and their Timelines Scenarios for Facebook
1.	Verify that the user can search for friends in facebook’s ‘Find friends’ search functionality.
2.	Verify that users can send a friend requests to any user by visiting their page.
3.	Verify that the user can navigate through their Friend’s friend and send a friend requests to them.
4.	Verify that the user can approve or decline received friend request.
5.	Verify that the user can unfriend any existing friend.
6.	Verify that users can see the timeline of their friends.
7.	Verify that users can post text in their friend’s timeline.
8.	Verify that users can post images in their timeline and the same gets displayed to their friends.
9.	Verify that users can post links with or without preview in their friend’s timeline.
10.	Verify that users can tag friends in their posts on a friend’s timeline.
11.	Verify that users can see all the posts in their friend’s timeline.
12.	Verify that users can see comments, likes, and reactions in the posts present in their friend’s timeline.
13.	Verify that users can post comments, like and react to the posts present in their friend’s timeline.
Facebook Notification Test Scenarios
1.	Verify that users receive different notifications on facebook ‘Notifications’ icon.
2.	Verify that users receive different notifications on email or cell phone based on the settings chosen when not logged in to Facebook.
3.	Verify that users receive a notification when their friend request gets approved.
4.	Verify that users receive a notification when they get a friend request.
5.	Verify that users receive a notification when they get tagged by someone on posts or comments.
6.	Verify that users receive a notification when they get comments, like or reactions on their posts.
7.	Verify that users receive notification when someone posts on their timeline.
