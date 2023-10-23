Elijah Thomas ethomas7@uoregon.edu

CS 322 Project 3

Implementation of an Anagram game using AJAX as a frontend and Flask as a backend.

The only problem I've encountered recently was that some words had duplicates added in the response paragraph element.
To my knowledge, this has been fixed in the frontend. Requests are only sent to Flask if they do not match the previous
request. For some reason, duplicate requests were being sent.