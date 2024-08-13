


HOW DO U TEST A LOGIN PAGE????
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


HOW DO YOU TEST ECOMMERCE APPLICATION????
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

HOW DO YOU TEST GOOGLE SEARCH???
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


HOW TO DO YOU TEST GMAIL???
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

HOW DO YOU TEST YOUTUBE????
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


HOW DO YOU TEST FACEBOOK????
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





How do u test an ATM machine???
1.	Verify that all the labels and controls including text-boxes, buttons, images, and links are present on the screen.
2.	Verify that the informative text written displayed on the screen is clearly visible and legible.
3.	Verify that the size, color, and UI of the different objects are as per the specifications. 
4.	Verify that the application’s UI is responsive i.e. it should adjust to different screen resolutions of ATM machines.


FUNCTIONAL SCENARIOS :-
1.	Verify the type of ATM machine, if it is completely touch-enabled, with both keypad buttons only or both.
2.	Verify that the user is presented with options when the card is inserted correctly.
3.	Verify that no option to continue and enter credentials is displayed to the user when the card is inserted incorrectly.
4.	Verify that the touch of the ATM screen is smooth and operational.
5.	Verify that the user is presented with the option to choose a language for further operations.
6.	Verify that the user is asked to enter pin number before displaying any card/bank account detail.
7.	Verify that there is a limited number of attempts up to which the user is allowed to enter pin code.
8.	Verify that if a total number of incorrect pin attempts gets surpassed then the user is not allowed to continue further and operations like temporary blocking of the card, etc get initiated.
9.	Verify that the pin is displayed in masked form when entered.
10.	Verify that the user is presented with different account type options like- saving, current, etc.
11.	Verify that the user is allowed to get account details like available balance.
12.	Verify that the correct amount of money gets withdrawn as entered by the user for cash withdrawal.
13.	Verify that the user is only allowed to enter the amount in multiples of denominations as per the specifications.
14.	Verify that the user is prompted to enter the amount again in case the amount entered is less than the minimum amount configured.
15.	Verify that the user cannot withdraw more amount than the total available balance and a proper message should be displayed.
16.	Verify that the user is provided the option to get the transaction details in printed form.
17.	Verify that the user’s session timeout is maintained.
18.	Verify that the user is not allowed to exceed one transaction limit amount.
19.	Verify that the user is not allowed to exceed the one-day transaction limit amount.
20.	Verify that the user is allowed to do only one transaction per pin request.
21.	Verify that in case the ATM machine runs out of money, a proper message is displayed to the user.
22.	Verify that the applicable fee gets deducted along with the withdrawn amount in case the user exceeds the limit of the number of free transactions in a month.
23.	Verify that the applicable fee gets deducted along with the withdrawn amount in case the user uses the card of a bank other than that of ATM.
24.	Verify that the user is not allowed to proceed with the expired ATM card and proper error message gets displayed.
25.	Verify that in case sudden electricity loss before withdrawing cash, the transaction is marked as null and the amount is not withdrawn from the user’s account.

HOW DO U TEST COFFEE MACHINE????
1.	UI scenario – Verify that the dimension of the coffee machine is as per the specification
2.	Verify that outer body, as well as inner part’s material, is as per the specification
3.	Verify that the machine’s body color as well brand is correctly visible and as per specification
4.	Verify the input mechanism for coffee ingredients-milk, water, coffee beans/powder, etc
5.	Verify that the quantity of hot water, milk, coffee powder per serving is correct
6.	Verify the power/voltage requirements of the machine
7.	Verify the effect of suddenly switching off the machine or cutting the power. The machine should stop in that situation and in power resumption, the remaining coffee should not get come out of the nozzle.
8.	Verify that coffee should not leak when not in operation
9.	Verify the amount of coffee served in single-serving is as per specification
10.	Verify that the digital display displays correct information
11.	Check if the machine can be switched on and off using the power buttons
12.	Check for the indicator lights when the machine is switched on-off
13.	Verify that the functioning of all the buttons work properly when pressed
14.	Verify that each button has an image/text with it, indicating the task it performs
15.	Verify that complete quantity of coffee should get poured in a single operation, no residual coffee should be present in the nozzle
16.	Verify the mechanism to clean the system work correctly- foamer
17.	Verify that the coffee served has the same and correct temperature each time it is served by the machine
18.	Verify that system should display an error when it runs out of ingredients
19.	Verify that pressing the coffee button multiple times leads to multiple serving of coffee
20.	Verify that there is the passage for residual/extra coffee in the machine
21.	Verify that machine should work correctly in different climatic, moistures and temperature conditions
22.	Verify that machine should not make too much sound when in operation
23.	Performance test – Check the amount of time the machine takes to serve a single serving of coffee
24.	Performance test – Check the performance of the machine when used continuously until the ingredients run out of the requirements
25.	Negative Test – Check the functioning of the coffee machine when two/multiple buttons are pressed simultaneously
26.	Negative Test – Check the functioning of coffee machine with a lesser or higher voltage than required


HOW DO U TEST CALENDER???
1.	Verify that on clicking the date field, a calendar widget should open.
2.	Verify that the default width of the calendar should be displayed as per the specification.
3.	Verify that the calendar widget’s dimensions should be responsive as per the device and screen size.
4.	Verify that the user can select a date in the calendar and after selecting the date the same gets displayed in the date field.
5.	Verify that by default the current month’s calendar should be displayed.
6.	Verify that the user can move to previous and next month’s calendar by choosing the left and right icon over the calendar.
7.	Verify that the user can check the calendar of a particular month of any year.
8.	Verify that the user can enter a date manually on the date following the date format.
9.	Verify the date format supported by the calendar e.g. – dd/mm/yy, mm/dd/yy etc.
10.	Verify that the user can also edit a date that is already set in the calendar.
11.	Verify that values other than numerics should not be allowed in the date field (apart from the characters used in the date format like ‘/’ or ‘-‘.
12.	Verify that invalid dates are not allowed in the date field (like date value exceeding 31, month value exceeding 12, etc).
13.	Verify the oldest possible date that can be set on the calendar.
14.	Verify the last possible date that can be set on the calendar.
Negative Test Cases for Calender:-
1.	Verify the state of the calendar widget on entering special characters, either the special characters should not be allowed and in the case allowed, they should get discarded while setting a date.
2.	Verify the state of the calendar widget on entering foreign language characters on the editable date field.
3.	Check the UI of the calendar widget on extremely small and extremely large screen sizes.


How do you test a Door???
1.	Verify if the door is single door or bi-folded door
2.	Check if the door opens inwards or outwards
3.	Verify that the dimension of the doors are as per the specifications
4.	Verify that the material used in the door body and its parts is as per the specifications
5.	Verify that color of the door is as specified
6.	Verify if the door is sliding door or rotating door
7.	Check the position, quality and strength of hinges
8.	Check the type of locks in the door
9.	Check the number of locks in the door interior side or exterior side
10.	Verify if the door is having peek-hole or not
11.	Verify if the door is having stopper or not
12.	Verify if the door closes automatically or not – spring mechanism
13.	Verify if the door makes noise when opened or closed
14.	Check the door condition when used extensively with water
15.	Check the door condition in different climatic conditions- temperature, humidity etc
16.	Check the amount of force- pull or push required to open or close the door




How do you test a calculator????
1.	Check if the calculator is a normal calculator or a scientific calculator.
2.	Verify that all the buttons are present and text written on them is readable.
3.	Check the arithmetic operations are working fine- +, -, /, * etc.
4.	Verify that BODMAS is applied in case of complex queries and the correct result is returned.
5.	Verify that the calculator gives the correct result in case of operations containing decimal numbers.
6.	Check if the calculator is battery operated or works on solar power.
7.	Verify the outer body material of the calculator.
8.	Verify the spacing between the two buttons, the buttons should not be too closely placed.
9.	Check the pressure required to press a button, the pressure required should not be too high.
10.	Verify the number of digits allowed to enter in the calculator for any operation.
11.	Verify the limit of the response value.
12.	Verify the functioning of memory functions.
13.	Check if the calculator allows navigating through previous calculations.
14.	Verify that hitting ‘C’ cancels any digits or operation added.
15.	Verify the working of the ON-OFF button in the calculator.
16.	Check if keeping the calculator unused for a certain period of time, turns it off automatically.
17.	Verify that on pressing two operators one after the other, the latest one will override the previous operator.
18.	Verify the state of the calculator when two buttons are pressed simultaneously.
19.	Verify if the user can delete digits one by one using the backspace key.


HOW DO YOU TEST FLIGHT RESERVATION APPLICATION???/
1.	Verify that there is a portal to add new flights in the system.
2.	Verify that on filling flight details like flight name, code, from and to destinations, capacity, timings, and frequency etc, new filghts get successfully added in the system.
3.	Verify that users can search for flights by name, from-to airports or flight code for checking their status and timings.
4.	Verify that search results have flight details, timings and availability.
5.	Verify that clicking the search results open complete details for flight.
6.	Verify that the user should see realtime flight status of availability of seats.
7.	Verify that the user is presented with a graphical view of the airline’s sitting arrangement along with seat number and availability status.
8.	Verify that the pricing of different types of seats is displayed to the users.
9.	Verify that users can successfully select single or more than one seat.
10.	Verify that the user can not select or is not permitted to select seats that are already booked or not allowed for booking.
11.	Verify that after selecting seats, entering passenger details and making payment the selected seats get booked.
12.	Verify that on successful booking the ticket should be visible and downloadable.
13.	Verify that after successful booking the seat’s status is updated to booked.
14.	Verify that the user also receives confirmation mail along with tickets on the emailIds provided while filling the details.
15.	Verify the maximum limit of seats that a user can book, selecting more seats than permitted results in error message.
16.	Verify that all the different types of payment methods work fine.
17.	Verify that user is presented with additional options like- luggage, extra legroom, foods/beverages, etc and selecting the same results in additional cost with the booking amount.
18.	Verify that the user can also cancel the tickets booked by entering the mandatory details and the amount after deducting the cancellation fee gets refunded back to user.
19.	Verify that after cancellation the seat’s status is updated to available.


HOW DO YOU TEST A KEYBOARD???
1.	Check if all the keys- characters, numeric, function, special characters, and arrow keys are present
2.	Verify the ordering of the keys is as per the QWERTY standard
3.	Check the functioning of each type of key-characters, numeric, function, special characters, and arrow keys
4.	Verify the working of the keys that work in combination like- shift+{other keys}
5.	Check if the dimension of the key is as per the specification
6.	Check the color of both keyboard body as well as the text written over the buttons
7.	Check if the font type and size is as per the specification and legible
8.	Check if the pressure required to press a key is not too high
9.	Check the spacing between two keys, keys should not be congested and at the same time not too widely placed
10.	Verify that in case of caps lock and other similar keys- an indicator light glows
11.	Check if keys don’t make too much noise when clicked
12.	Verify if the keyboard is a wireless or wired keyboard
13.	In case the keyboard is wireless, verify the range of keyboard
14.	In case of a wired keyboard, check the length of the keyboard
15.	Verify if the keyboard contains multimedia functions as well


HOW DO U TEST A LIFT??
1.	Verify the dimensions of the lift
2.	Verify the type of door of the lift is as per the specification
3.	Verify the type of metal used in the lift interior and exterior
4.	Verify the capacity of the lift in terms of the total weight
5.	Verify the buttons in the lift to close and open the door and numbers as per the number of floors
6.	Verify that lift moves to the particular floor as the button of the floor is clicked
7.	Verify that lift stops when up/down buttons at particular floor are pressed
8.	Verify if there is an emergency button to contact officials in case of any mishap
9.	Verify the performance of the floor – the time is taken to go to a floor
10.	Verify that in case of power failure, lift doesn’t free-fall and get halted in the particular floor
11.	Verify lifts working in case button to open the door is pressed before reaching the destination floor
12.	Verify that in case door is about to close and an object is placed between the doors if the doors sense the object and again open or not
13.	Verify the time duration for which door remain open by default
14.	Verify if lift interior is having proper air ventilation
15.	Verify lighting in the lift
16.	Verify that at no point lifts door should open while in motion
17.	Verify that in case of power loss, there should be a backup mechanism to safely get into a floor or a backup power supply
18.	Verify that in case multiple floor number button is clicked, lift should stop at each floor
19.	Verify that in case of capacity limit is reached users are prompted with warning alert- audio/visual
20.	Verify that inside lift user are prompted with current floor and direction information the lift is moving towards- audio/visual prompt

HOW DO YOU TEST MOBILE PHONE???
1.	Verify that all the required buttons- numbers 0-9, calling buttons etc are present
2.	Verify that the user can make a call by pressing numbers and hitting calling(green) button
3.	Verify that user can make a call by selecting a contact person from the phone directory
4.	Verify that the user can reject an incoming call
5.	Verify that the user can receive an SMS
6.	Verify that the user can type and send an SMS
7.	Verify that the dimension of the mobile is as per specification
8.	Verify the screen size of the mobile
9.	Verify that the weight of the mobile is as per the specification
10.	Verify the font type and size of the characters printed on the keypad
11.	Verify the color of the mobile phone’s outer body and characters printed on keypad
12.	Verify the pressure required to press a key on the keypad
13.	Verify that spacing between the keys on the keypad are adequate
14.	Check the type of mobile- smartphone or normal
15.	Check if the mobile is colored or black-white
16.	Check the lighting on the mobile screen is adequate- verify in dark daylight
17.	Check if a mobile phone can be locked out without password or pin
18.	Check if mobile phone can be locked out with password or pin
19.	Verify that the mobile phone can be unlocked with/without password
20.	Verify that the user can receive a call when the phone is locked
21.	Verify that receiving a call when phone is locked, doesn’t unlock it after call completion
22.	Verify that user can select an incoming call and SMS alert ringtone
23.	Verify that the user can make silent or vibrate mode or incoming calls and SMS
24.	Verify the battery requirement of the mobile
25.	Verify the total time taken to charge the mobile completely
26.	Verify the total time for mobile to get completely discharged when left idle
27.	Verify the total talk for mobile to get completely discharged when continuously used in conversation
28.	Verify the length of charger wire
29.	Verify that mobile can be switched off and ON
30.	Verify that user can store contact details on the phone book directory
31.	Verify that user can delete and update contact details in the phonebook directory
32.	Verify that Call logs are maintained in the Call Logs
33.	Verify that received and Sent SMSs are saved in mobile
34.	Verify that user can silent the phone during an incoming call
35.	Verify the auto-reject option can be applied and removed on particular numbers
HOW DO YOU TEST A MOUSE???
1.	Check if the mouse is an optical mouse or not.
2.	Verify that left-click and right-click buttons are working fine.
3.	Check if the double click is working fine.
4.	Verify the time duration between two left clicks, in order to consider it as a double click.
5.	Check if the scroller is present at the top or not.
6.	Verify the speed of the mouse pointer.
7.	Check the pressure required for clicking the mouse buttons.
8.	Verify the acceleration of the mouse pointer.
9.	Verify that clicking the button and dragging the mouse operation is working fine(drag and drop functionality).
10.	Check the dimension of the mouse, if it’s suitable to grip and work.
11.	Verify that the mouse works in all the allowed surfaces.
12.	Check if the mouse is a wireless mouse or corded mouse.
13.	In the case of wireless mouse, check the range up to which the mouse remains operational.
14.	In the case of a wireless mouse, check the battery requirement of the mouse.
15.	Check if there is an option to switch on or mouse.


HOW DO YOU TEST A MICROWAVE  OWEN???
1.	Verify that the dimensions of the oven are as per the specification provided.
2.	Verify that the oven’s material is optimal for its use as an oven and as per the specification.
3.	Verify that the oven heats the food at the desired temperature properly.
4.	Verify that oven heats food at the desired temperature within a specified time duration.
5.	Verify the ovens functioning with maximum attainable temperature.
6.	Verify the ovens functioning with minimum attainable temperature.
7.	Verify that the oven’s plate rotation is speed is optimal and not too high to spill the food kept over it.
8.	Verify that the oven’s door gets closed properly.
9.	Verify that the oven’s door opens smoothly.
10.	Verify the battery requirement of the microwave oven and check that it function’s smoothly at that power.
11.	Verify that the text written over the oven’s body is clearly readable.
12.	Verify that the digital display is clearly visible and functions correctly.
13.	Verify that the temperature regulator is smooth to operate.
14.	Verify that the temperature regulator works correctly.
15.	Check the maximum capacity of the oven and test its functioning with that volume of food.
16.	Check oven’s functionality with different kinds of food – solid, liquid.
17.	Check the oven’s functionality with different food at different temperatures.
18.	Verify the oven’s functionality with different kinds of container material.
19.	Verify that the power cord of the oven is long enough.
20.	Verify that the usage instruction or user manuals have clear instructions.

HOW DO YOU TEST A NOTEPAD?????
1.	Verify that on launching the notepad application, the notepad editor should open with its default size.
2.	Verify that users can write/type alphabets from a standard keyboard.
3.	Verify that the user can type numerics from a standard keyboard.
4.	Verify that the user can type special characters and symbols on the notepad editor window.
5.	Verify that by default the font size is normal or as per the specifications.
6.	Verify that the user can set the font size and family.
7.	Verify that the user can save the text in a file.
8.	Verify that the user can open any exiting file in notepad.
9.	Verify that file formats not permitted by notepad are not loaded and don’t corrupt the application.
10.	Verify that the user can append text to any file and again save the file.
11.	Verify that users can select, copy, and paste the text.
12.	Verify that users can select, cut, and paste the text.
13.	Verify that the user can select and delete a text.
14.	Verify that the user can delete a text using backspace and delete buttons.
15.	Verify that the user can navigate through the text in a file using the arrow keys.
16.	Verify that the user can navigate through the text in a file using the mouse pointer.
17.	Verify that the user can edit and delete data in between the text file.
18.	Verify that the user can undo any latest change done in the file.
19.	Verify that the user can redo any change undone by undo option.
20.	Verify that the user can search for single or multiple characters and words through the file.
21.	Verify that the user can search and replace single or multiple characters and words through the file.
22.	Verify that the user can resize the notepad window.
23.	Verify that the user can minimize the notepad editor window.
24.	Verify that the user can maximize the notepad editor window.
25.	Verify that the user can close the editor window by clicking the cross icon.




HOW DO YOU TEST  A PENCIL???
1.	Verify that the text written with the pencil is readable/legible.
2.	Verify that the user can write smoothly on different types/quality of paper surfaces.
3.	Check that the darkness/color of the text written by pencil is as per the specifications.
4.	Check the strength of the lead, it should not break when a specified(normal human) pressure is applied.
5.	Verify that the text written by pencil can be erased by normal erasers.
6.	Verify that the quality and strength of the pencil’s wood.
7.	Check whether the outer body of the pencil is circular or some polygon shape.
8.	Verify that the length and radius of the pencil are as per the specification.
9.	Verify that the weight of the application is as per the specification.
10.	Verify that the pencil can be sharpened easily by a normal sharpener.
11.	Verify the total length of text written by a complete pencil.
12.	Verify the total length of text written before you need to sharpen the pencil again.
13.	Verify that the pencil writes on the normally specified surfaces clearly.
14.	Verify the outer coloring of the pencil’s paint.
15.	Check if the pencil writes when putting in water for some time.
16.	Check the quality and strength of the pencil when immersed in water for some time.
17.	Check that the text written by pencil gets erased or note when the paper is immersed in water and later dried.


HOW DO YOU TEST TV REMOTE???
1.	Verify that all the buttons are present- 0 to 9, volume, channel up-down and other audio-video functionality etc buttons
2.	Verify the functionality of power ON-OFF button
3.	Verify that the Remote Control should work for a particular TV set model numbers only
4.	Verify that user can navigate to different single digit and multi digit channels
5.	Verify that user can increase or decrease the volume
6.	Verify that user can navigate up and down the channel using channel up and down buttons
7.	Verify that functioning of audio-video and other auxillary buttons
8.	Verify the maximum distance from the Television set upto which the remote works smoothly
9.	Verify the button press event that triggers the functionality i.e. an event gets triggered on button down press, button release etc
10.	Verify the arc/different directions the remote control works correctly
11.	Verify the battery requirement of the remote control
12.	Verify the material of the remote’s body and its button
13.	Verify the weight of the remote control
14.	Verify the dimensions of remote control
15.	Verify the spacing between two buttons, the spacing between the two buttons should be optimum distance apart so that user can press a button comfortably
16.	Verify that there should be contrast between button’s color and remote’s outer body color
17.	Verify the remote’s functioning on pressing more than one button simultaneously
18.	Verify that the font – style and size of the numbers and other information should be readable
19.	Verify that on battery discharge, the remote should work normally on inserting new batteries
20.	Verify the pressure required to press the button
21.	Verify the strength of the remote’s outer body, if it works normally on dropping from a certain height
22.	Verify that any operation performed on the remote control while the TV is switched off should not make any difference to TV’s functioning when switched on
23.	Verify if the remote control is water proof or not, if its water proof, check if it works normally after immersing it in water


HOW DO YOU TEST A TRIANGLE???
1.	Verify that the figure is closed (polygon).
2.	Verify that the figure is two-dimensional and formed with straight lines only.
3.	Verify that the figure has exactly three sides.
4.	Verify that the figure has exactly three vertices.
5.	Verify that the figure has exactly three angles.
6.	Verify that the sum of the angles of the figure is 180 degrees.
7.	Verify that no two sides are parallel to each other.
8.	Verify that the sum of the length of two sides of the triangle should be greater than the length of the third side.
9.	Verify that no two angles of a triangle have 90 degrees and above value.
10.	Verify the type of traingle is as per the specification, based on its sides – scalene, isosceles or equilateral.
11.	Verify the type of triangle is as per the specification, based on its angles – acute angle, obtuse angle, or right-angled triangle.
12.	Verify that the area of triangle is equal to half of the product of its base and height.


HOW DO YOU TEST A TV???
1.	Verify the dimensions of the TV – length, breadth and height are as per the specifications
2.	Check the TV technology type – LED, LCD etc
3.	Verify that the screen resolution of the TV is as per the specifications
4.	Check the material used for outer body of TV
5.	Check the material used for screen of TV
6.	Verify that on supplying specified power supply, TV gets switched on after pressing ‘Power’ button
7.	Verify that all the buttons on TV perform there functioning correctly
8.	Verify that TV screen clearly displayes videos
9.	Verify that audio of TV is audible without any noise
10.	Verify that buttons in TV have clearly visible lables indicating there functionality
11.	Verify that buttons in TV function correctly when pressed
12.	Verify that remote’s signal reciever recieves signal within a specified range

HOW DO YOU TEST BIKE????
UI Test Cases for Bike
1.	Verify that design and dimension of the application are as per the specifications.
2.	Verify that the different colors used in the bike are of the correct shades as per the specifications.
3.	Verify that the weight of the bike is as per the specifications.
4.	Check the material used in different parts of the bike – outer body, tires, seat, etc.
Positive Test Cases for Bike
1.	Check if the bike is of type electric start, manual start or both.
2.	Verify that the bike starts smoothly using the available options.
3.	Check the amount of force to kick-start the bike.
4.	Verify that bike runs smoothly and attain desired speed when accelerated.
5.	Verify that the maximum speed attained by bike is as per the specification.
6.	Verify that the maximum acceleration attained by bike is as per the specification.
7.	Verify that noise made by bike is within the acceptable decibel levels.
8.	Verify that both the brakes work correctly.
9.	Verify that clutch works correctly.
10.	Check the number of gears in bike.
11.	Verify that user can change the gear from lower to higher.
12.	Verify that user can change the gear from higher to lower.
13.	Verify that bike can be ridden on all types of road surfaces – charcoal, cement, wet road etc.
14.	Verify that bike can be ridden on all weather conditions.
15.	Verify that bike can be ridden on slop and ramp.
16.	Verify the mileage of the bike is as per the specification when driven on the standard surface.
17.	Check the pick-up of the bike.
18.	Check the fuel tank capacity of the bike.
19.	Check the fuel type requirement.
20.	Verify that the pollution is within the permissible limit.
21.	Verify that the fuel meter displays the correct status of fuel.
22.	Verify that speedometer displays correct speed of the bike.
23.	Verify that the dashboard displays all the information correctly.
24.	Verify that indicators and indicator light works correctly.
25.	Verify that the headlight works correctly.
26.	Check if the bike has reserve oil or not.
27.	Verify that the horn works correctly.
Negative Test Cases for Bike
1.	Check if the bike starts when fuel other than prescribed fuel is filled in the bike.
2.	Check the condition of the bike when tires are filled with pressure less or more than specified.
3.	Check the condition of the bike when both the tires have different air pressure.
4.	Check the bike’s condition when it is ridden at high speed on first gear only.

HOW DO YOU TEST A MARKER???
1.	 Verify if the marker’s outer body is made of specified material(plastic, fiber, metal, etc.).
2.	Verify that the marker has the name of the company that manufactured it.
3.	Verify that the logo of the manufacturing company is clearly printed or embossed.
4.	Check if the body of the marker is sturdy, rugged, and unbreakable to an extent.
5.	Check if the outer cover’s color matches with the ink of the marker providing an idea of the marker’s ink just by seeing the outer body.
6.	Check if the bar code is printed so as to identify each marker.
7.	Verify the weight of the marker and the specified weight. Make sure it’s light-weighted (if not specified) for a smooth writing experience.
8.	Check if the body is neither too thick nor too slender for comfortable gripping.
9.	Check if the marker is refillable so as to avoid wastage.
10.	Check the tip of the marker, it should be neither too thin nor flat to assist user comfortability.
11.	Check the smoothness of the marker.
12.	Check if the ink is neither permanent nor getting easily rubbed off. This will ensure easy use of it on whiteboards.
13.	The ink should be eye-pleasing.
14.	The ink should not release any pungent smell.
15.	The life of the marker should be as per the standards.
16.	Verify the refill is of optimum quantity so as to make it cost-effective.
17.	Check if the marker is working even if held at various different angles.
18.	Check if there is slight friction between the tip and the board so as to not make it slippery or uncomfortable while writing.
19.	Check if the ink does not leak if the marker is held in different positions.
20.	The marker should be able to write on boards as well as on similar surfaces like paper.



HOW DO U TEST A PEN?????
1.	Verify the type of pen, whether it is a ballpoint pen, ink pen or gel pen.
2.	Verify that the user is able to write clearly over different types of papers.
3.	Verify the weight of the pen, it should be as per the specifications. In case not mentioned in the specifications, the weight should not be too heavy to impact its smooth operation.
4.	Verify if the pen is with a cap or without a cap.
5.	Verify the color of the ink of the pen.
6.	Verify the odor of the pen’s ink on writing over a surface.
7.	Verify the surfaces over which pen is able to write smoothly apart from paper e.g. cardboard, rubber surface, etc.
8.	Verify that the text written by the pen should have consistent ink flow without leaving any blob.
9.	Verify that the pen’s ink should not leak in case it is tilted upside down.
10.	Verify if the pen’s ink should not leak at higher altitudes.
11.	Verify if the text written by the pen is erasable or not.
12.	Verify the functioning of pen on applying normal pressure during writing.
13.	Verify the strength of the pen’s outer body. It should not be easily breakable.
14.	Verify that text written by pen should not get faded before a certain time as mentioned in the specification.
15.	Verify if the text written by the pen is water-proof or not.
16.	Verify that the user is able to write normally on tilting the pen at a certain angle instead of keeping it straight while writing.
17.	Check the grip of the pen, whether it provides adequate friction for the user to comfortably grip the pen.
18.	Verify if the pen can support multiple refills or not.
19.	In the case of an ink pen, verify that the user is able to refill the pen with all the supported ink types.
20.	In the case of an ink pen, verify that the mechanism to refill the pen is easy to operate.
21.	In the case of a ballpoint pen, verify the size of the tip.
22.	In the case of a ball and gel pen, verify that the user can change the refill of the pen easily.

2.   HOW DO YOU TEST A FAN?????
1.	Check the type of fan – whether the fan is ceiling fan or table fan
2.	Verify the number of blades on the fan
3.	Verify the ON-OFF functionality of fan
4.	Verify if the fan works normally-throws wind on the right direction
5.	Verify the material of which fan’s blade and other parts are made
6.	Check the voltage/power requirement of the fan
7.	Verify the maximum speed of fan
8.	Check the minimum speed of the fan
9.	Verify that the speed of fan can be regulated using regulator
10.	Verify that when in motion, the fan should not wobble
11.	Check the length of the fan rod and blades
12.	Verify that the weight of the fan is as per the specifications
13.	Verify that the color of the fan is as per the specifications
14.	Check the effect of voltage fluctuation on fan when in motion
15.	Check the effect of sudden electricity outage on fan’s motor and other electrical parts
16.	Verify the fan’s condition when continuously switched on for very large duration
17.	Check if there is any lifetime of fan’s internal parts or the body
18.	Check if the blades of the fan can be bend or not, check if its material is brittle
19.	Check the time taken by fan to attain maximum speed, when switched ON


HOW DO U TEST A WATER BOTTLE??????
1.	Verify that the dimensions of the bottle are as per the specifications.
2.	Verify that the color of the bottle is as per the specifications.
3.	Verify the material used in the bottle.
4.	Verify the weight of the bottle is as per the specifications.
5.	Verify the type of the bottle – with a lid or without a lid.
6.	Check if the bottle is with a sipper or without a sipper.
7.	Measure the volume of water that can be stored in the bottle and check if the volume is as specified.
8.	Verify that bottle doesn’t leak when tilted or placed upside down.
9.	Verify that the lid of the bottle is firmly tightened with a bottle.
10.	Check the bottle’s condition with liquid of different temperatures.
11.	Check bottle’s condition with different liquids – water, tea, etc.
12.	Check the insulation of bottle – time for the liquid to achieves room temperature.
13.	Check the brittleness of the bottle’s material.
14.	Check if the expiry date is clearly mentioned or not.
15.	Verify the maximum temperature of the liquid allowed.
16.	Verify the minimum temperature of the liquid allowed.
Negative Test Cases for Water Bottle
Here, we will see some negative test scenarios, in which we will cover the test cases focusing on the stress testing or robustness of the water bottle when subjected to extreme conditions.
1.	Check the bottle’s condition on pouring liquid at a very high temperature, more than the permissible value.
2.	Check the bottle’s condition on pouring liquid at a very low temperature, less than the permissible value.
3.	Check the bottle’s condition when subjected to a very high temperature.
4.	Check the bottle’s condition on pouring liquid/gas at very high pressure, more than the normal pressure.




HOW DO U TEST A WHITE BOARD?????
1.	Verify that the dimension of the whiteboard is as per the specifications.
2.	Verify the exact color of the board – white color’s variant.
3.	Verify the smoothness of the whiteboard.
4.	Verify the material used to develop the surface of the whiteboard
5.	Verify the material used in the body of the whiteboard, its hooks, and other parts.
6.	Verify if the board is suitable for writing with normal/specified marker types.
7.	Verify if there is sufficient friction in the board to allow writing on its surface.
8.	Verify if text written in the board using normal markers gets erased using a duster.
9.	Check if there is a holder for markers and duster in the whiteboard.
10.	Verify that the board works normally in all climatic conditions- humidity, temperatures, etc.
11.	Verify that the board doesn’t reflect too much light that makes it unreadable.
12.	Verify the amount of pressure required to write on the board using normal markers.
13.	Verify that markers of all colors but white should be visible on the board.
14.	Verify that text written in the board should not fade away quickly(or before a specified time).
15.	Verify that the board has hooks to hang them over the wall.
16.	Verify if text written using permanent markers, paints etc can be erased on the board using chemicals.

HOW DO U TEST A CHAIR????
1.	Verify that the chair is stable enough to take an average human load
2.	Check the material used in making the chair-wood, plastic etc
3.	Check if the chair’s leg are level to the floor
4.	Check the usability of the chair as an office chair, normal household chair
5.	Check if there is back support in the chair
6.	Check if there is support for hands in the chair
7.	Verify the paint’s type and color
8.	Verify if the chair’s material is brittle or not
9.	Check if cushion is provided with chair or not
10.	Check the condition when washed with water or effect of water on chair
11.	Verify that the dimension of chair is as per the specifications
12.	Verify that the weight of the chair is as per the specifications
13.	Check the height of the chair’s seat from floor

HOW DO U TEST A WRIST WATCH???/
1.	Verify the type of watch – analog or digital.
2.	In the case of an analog watch, check the correctness time displayed by the second, minute, and hour hand of the watch.
3.	In the case of a digital watch, check the digital display for hours, minutes, and seconds is correctly displayed.
4.	Verify the material of the watch and its strap.
5.	Check if the shape of the dial is as per specification.
6.	Verify the dimension of the watch is as per the specification.
7.	Verify the weight of the watch.
8.	Check if the watch is waterproof or not.
9.	Verify that the numbers in the dial are clearly visible or not.
10.	Check if the watch is having a date and day display or not.
11.	Verify the color of the text displayed in the watch – time, day, date, and other information.
12.	Verify that clock’s time can be corrected using the key in case of an analog clock and buttons in case of a digital clock.
13.	Check if the second hand of the watch makes ticking sound or not.
14.	Verify if the brand of the watch and check if its visible in the dial.
15.	Check if the clock is having stopwatch, timers, and alarm functionality or not.
16.	In the case of a digital watch, verify the format of the watch 12 hours or 24 hours.
17.	Verify if the watch comes with any guarantee or warranty.
18.	Verify if the dial has glass covering or plastic, check if the material is breakable or not.
19.	Verify if the dial’s glass/plastic is resistant to minor scratches or not.
20.	Check the battery requirement of the watch.

HOW  DO YOU TEST A CAR???

Positive Test Cases for Car
1.	Verify that car should get unlocked and start smoothly on unlocking with its key
2.	Verify that car gets driven smoothly at normal speed on road and under normal climatic condition
3.	Verify that clutch, break and accelerator functions are working correctly
4.	Verify the engine type of car – whether it is Petrol, Diesel or CNG engine
5.	Verify the car’s performance on different types of roads- charcoal, cement etc
6.	Verify car’s performance and fuel consumption on plains, hills and slops
7.	Verify that the mileage of the car is as per the specification
8.	Verify that the dimensions of the car are as per the specification
9.	Check if the car is sports car or luxury car
10.	Check that the fuel capacity is as per the specification
11.	Check if the steering is power steering or not
12.	Check if gears are automatic or manual
13.	Verify if the reverse gear of the car works correctly
14.	Check if the height of the car’s floor is at an optimum distance from road
15.	Verify the top speed of the car under normal conditions
16.	Verify the maximum acceleration of the car
17.	Verify the car’s outer body material
18.	Check if the car’s pane is made of tempered glass or not
19.	Check the number of seats in the car
20.	Check if the hand brakes are functional or not
21.	Verify that brakes work correctly and gets applied in a timely manner or not
22.	Verify the type and power of battery
23.	Check if the headlights are working fine and give proper lighting when applied at night/dark
24.	Verify the shock absorber of the car
25.	Verify if the air bags are present or not and are functional if present
26.	Check if centre locking is present or not and is functional if present
27.	Check if the seat belts are present and are functioning correctly
28.	Verify car’s interior- spacing, material, quality etc
29.	Verify if the speedometer, fuel meter and other indicators are working fine or not
30.	Verify cars performance, tyre’s grip on driving the car on rainy day
31.	Verify that car should get started and run smoothly on using it after several days
32.	Check the automatic car lock functionality
33.	Verify that car’s back light should get lightened on reversing the car
34.	Verify that left and right indicators should function correctly
35.	Check if anti-theft alarm is working correctly or not
Negative Test Cases for Car
1.	Verify the car’s functioning on filling it with non-prescribed fuel type
2.	Drive car at high speed on first gear only
3.	Keep the air pressure different on all the four tyres and than drive the car
4.	Use hand break while driving the car
5.	Try to start the car with some other key
6.	Check the condition of tyres on filling them at pressure higher than prescribed
7.	Check the condition, speed and fuel consumption of car on filling the tyres with pressure less than prescribed
8.	Check car’s speed, performance and fuel consumption on driving the car on roads not conducive for driving


HOW DO U TEST A STAPLER?????
1.	Verify that the stapler staples the paper firmly.
2.	Verify that the stapler works correctly with a maximum number of paper sheets or a maximum width of papers to be stapled.
3.	Verify that stapler works correctly with materials other than paper that are commonly stapled things like cartridge sheet.
4.	Verify the pressure required to staple is not too high.
5.	Verify that the maximum number of pins that can be placed in a stapler at a time is as per the specification.
6.	Verify the dimension of the stapler.
7.	Verify the outer material of the stapler.
8.	Verify the color of the stapler’s outer body is as per the specifications.
9.	Verify the width of the pins used in the stapler.
10.	Verify that the component to unstaple is present in the stapler(usually at the end).
