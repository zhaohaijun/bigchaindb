# How to Handle Pull Requests

This document is for whoever has the ability to merge pull requests in the Git repositories associated with BigchainDB.

If the pull request is from an employee of BigchainDB GmbH, then you can ignore this document.

If the pull request is from someone who is _not_ an employee of BigchainDB, then:

A. Have they agreed to the Individual Contributor Agreement in the past? There's a list of them in [a Google Spreadsheet that's accessible to all bigchaindb.com accounts](https://docs.google.com/spreadsheets/d/1VhekO6lgk1ZPx8dSjriucy4UinaU9pIdPQ5JXKcbD_Y/edit?usp=sharing). If yes, then you can merge the PR and ignore the rest of this document.

B. Do they belong to a company or organization which agreed to the Entity Contributor Agreement in the past, and will they be contributing on behalf of that company or organization? (See the Google Spreadsheet link in A.) If yes, then you can merge the PR and ignore the rest of this document.

C. Did they make a pull request to one of the bigchaindb repositories on GitHub (e.g. bigchaindb/bigchaindb)? If you're not sure, or you can't find one, then respond with an email of the form:

Dear [NAME OF PERSON WHO AGREED TO THE CLA]

According to the email copied below, you agreed to the BigchainDB Contributor License Agreement (CLA).

Did you intend to do that? If no, then feel free to ignore this email and we'll pretend it never happened.

If you did intend to do that, then do you intend to make a pull request in a BigchainDB repository? Maybe you already did? If so, can you please point me to the pull request in question?

Sincerely,
[INSERT YOUR NAME HERE]

D. Otherwise, go to the pull request in question and post a comment using this template:

Hi @nameofuser

Before we can merge this pull request, we need you or your organization to agree to one of our contributor agreements. One of the big concerns for people using and developing open source software is that someone who contributed to the code might claim the code infringes on their copyright or patent. To guard against this, we ask all our contributors to sign a Contributor License Agreement. This gives us the right to use the code contributed and any patents the contribution relies on. It also gives us and our users comfort that they won't be sued for using open source software. We know it's a hassle, but it makes the project more reliable in the long run. Thank you for your understanding and your contribution!

If you are contributing on behalf of yourself (and not on behalf of your employer or another organization you are part of) then you should:

1. Go to: https://www.bigchaindb.com/cla/
2. Read the Individual Contributor Agreement
3. Fill in the form "For Individuals"
4. Check the box to agree
5. Click the SEND button

If you're contributing as an employee, and/or you want all employees of your employing organization to be covered by our contributor agreement, then someone in your organization with the authority to enter agreements on behalf of all employees must do the following:

1. Go to: https://www.bigchaindb.com/cla/
2. Read the Entity Contributor Agreement
3. Fill in the form "For Organizations”
4. Check the box to agree
5. Click the SEND button

We will email you (or your employer) with further instructions.

(END OF COMMENT)

Once they click SEND, we (BigchainDB) will get an email with the information in the form. (Troy gets those emails for sure, I'm not sure who else.) The next step is to send an email to the email address submitted in the form, saying something like (where the stuff in [square brackets] should be replaced):

Hi [NAME],

The next step is for you to copy the following block of text into the comments of Pull Request #[NN] on GitHub:

BEGIN BLOCK

This is to confirm that I agreed to and accepted the BigchainDB [Entity/Individual] Contributor Agreement at https://www.bigchaindb.com/cla/ and to represent and warrant that I have authority to do so.

[Insert long random string here. One good source of those is https://www.grc.com/passwords.htm ]

END BLOCK

(END OF EMAIL)

The next step is to wait for them to copy that comment into the comments of the indicated pull request. Once they do so, it's safe to merge the pull request.

## How to Handle CLA Agreement Emails with No Associated Pull Request

Reply with an email like this:

Hi [First Name],

Today I got an email (copied below) to tell me that you agreed to the BigchainDB Contributor License Agreement. Did you intend to do that?

If no, then you can ignore this email.

If yes, then there's another step to connect your email address with your GitHub account. To do that, you must first create a pull request in one of the BigchainDB repositories on GitHub. Once you've done that, please reply to this email with a link to the pull request. Then I'll send you a special block of text to paste into the comments on that pull request.
