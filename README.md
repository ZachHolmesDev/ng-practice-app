# NgPracticeApp

## to-do's 

### make components 
3 pages Home, Table and About
- [ ] nav bar component 
- [ ] home page welcome component 
- [ ] about component 
- [ ] table-card component
- [ ] table component

### put components together and route them 
- [ ] setting up routing
- [ ] setting table

### add functiality 
- [ ] fetch some steam API data and display on component 
- [ ] add filters for the table via steam API data 

---

## Git Feature Branch Workflow

This project adheres to the *Git Feature Branch Workflow*. All development work is done in dedicated feature branches created from the main branch. Contributors are encouraged to isolate their changes to these feature branches, ensuring the main branch always remains in a deployable state. Upon completion of development and testing in a feature branch, it is merged back into main through a pull request, maintaining the project's integrity and history.  

Please refer to the following docs for more info [atlassian git feature-branch-workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)


### Project Workflow with Testing Branch

This project employs a structured workflow that integrates a testing branch for enhanced quality assurance. Follow these steps for contributing:

### Development & Initial Testing

1. **Create Feature Branch**: From `main`, create your branch:  
   ```
   git checkout -b feature-name
   ```
2. **Develop**: Implement your changes in the feature branch.

3. **Stay Updated**: Regularly merge updates from `main` to your branch:  
   ```
   git pull origin main
   ```

4. **Local Testing**: Test your changes locally to ensure functionality.

### Integration & Final Testing

5. **Merge to Testing**: Create a pull request to merge your feature into the `testing` branch for further review and testing.

6. **Review & Testing**: Conduct thorough testing in the `testing` environment and review code.

### Deployment

7. **Merge to Main**: Once approved, merge changes from `testing` to `main`.

8. **Deploy**: Deploy the changes in `main` to production.

9. **Cleanup**: Delete feature and testing branches post-merge to maintain a clean repository.

```
git branch -d feature-name
git push origin --delete feature-name
```

### Key Points

- **Feature Branch**: Isolate development work.
- **Testing Branch**: Acts as a pre-production/staging area.
- **Main Branch**: Stable and deployable to production.



--- 


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
