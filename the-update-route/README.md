# ![[tktk Module Name] - tktk Microlesson Name](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to tktk

This microlesson starts with an edit page that gets linked from the individual item's show page. It could be a third-level nested route from the react-router-dom's perspective, since it's nested within 
items/:id => items/:id/edit 

That edit form has all the state pre-filled in from the existing data of the object.

Once submitted, it makes the PUT request to the backend and awaits the response before updating the state of the local show page component AND the index page's collection of the items.