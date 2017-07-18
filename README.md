# uFR Series documentation

Documentation for uFR Series devices, focused on two main points: uFR Series serial communication protocol and uFR Series libraries API. Other documents contains tips on special cases and scenarios of usage.

## Scope and guidelines

uFR Series devices establish communication with host over D-Logic's serial communication protocol, which is described in separate document in this project folder.
API reference sits on top of that protocol. Purpose of API is to provide much easier and faster programming, much more convenient fo developers.
Many complex operations are summarized in few API functions.
General directions:
if your platform provides any type of serial or VCOM interface you can use API with our library. 
If you have specific approach and/or platform, you should use serial protocol directly.
Please refer to documents in this project for more details.  

### Prerequisites

No special prerequisites, any Open office or similar would be fine.
Documents are intentionally kept in .odt format for the purpose of user's convenince, like esaier handling of code snippets etc. 

### Updates

Each firmware, library or protocol changes are and will be documented. Please check them frequently.
New document called "ufR API new (new style, work in progress)" is a roadpath to more tidy way of writing and is currently in progress. It is maintained according to available time. 

## License

This project is licensed under the ..... License - see the [LICENSE.md](LICENSE.md) file for details

## Contributions and bugs

* Please contact us at support@d-logic.rs for any further help, questions or assistance. 
* If you find some inconsistence, mistake, typo or similar in documents, please contact us on above e-mail.


