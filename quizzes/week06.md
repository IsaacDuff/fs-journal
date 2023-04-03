# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
The App.vue
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
a component is a single piece of a page that is built elsewhere and placed within the page. 
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for will allow you repeat a component over and over for the length of the collection. 
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
the template, the script and the style. 
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
it stands for the Liskov substitution principle
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
the router.js is where pages are declared and mounted. 
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
The AppState is the file where information is held that needs to be accessed throughout the rest of the application. the state object within a component is the piece of it that will be pushed into a page elsewhere. 
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
The services is where anything that reaches out and talks with the api or makes changes to it on the backend are handled. 
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
The App.vue is where our most base element of html is held. everything else is placed within this on rendering. 
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
the style tag, adding scoped 
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
computed, or you can create a watcher that will function as a fancy appstate.on from mvc
```