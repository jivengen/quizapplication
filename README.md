<h1>**Random Quiz App**</h1>

Choosing random Students to answer a set of questions

<p>This app was a practice to create a quiz that randomly selects students.</p>

<h3>How to use:</h3>

<p>A randomize button is to select a question and a student, then the student will
answer a question based off of a randomizer.  This program tells if the 
student is correct or not and counts the number of answers correct by each
student.</p>

<h3>Code:</h3>

``` 
quizModule.factory("LocalStorageService", function($window, $rootScope){
    
    angular.element($window).on('storage', function($window, $rootScope){
        if(event.key === 'student-storage'){
            $rootScope.$apply();
        }
        if(event.key === 'question-storage'){
            $rootScope.$apply();
        }
```
