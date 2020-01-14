User Story for Bookmark

# Bookmark Manager

 This is week 6 of Maker - this is a focus on databases - to understand now to implenement a database successfully.
 This code is intended as a supplementary guide for [bookmark manager](https://github.com/makersacademy/course/tree/master/bookmark_manager). The commits on master branch roughly correspond with the walkthroughs provided in the challenge.

 ## User Stories

 ```
 As a time-pressed user
 So that I can quickly go to web sites I regularly visit
 I would like to see a list of bookmarks
 ```

 ## Domain Model

 ![Bookmark Manager domain model](./public/images/bookmark_manager_1.png)

 Client --> Controller(is the app, that links to the logic to the view)--> Model(logic code is kept) 
            Controller    --> View (what we see)