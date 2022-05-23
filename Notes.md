# Angular Notes

## Angular Components

Components are pieces of the UI including the template (HTML), logic and styling.

Components are reusable and can be embedded into the template as an XML-like tag.

- example

``` 
@Component({
    selector: 'app-hero-list',
    templateUrl: './hero-list.component.html',
    providers: [ HeroService ]
})

export class HeroListComponent implements OnInit {
    /* . . . */ 
}
```

## Angular Services

Angular distinguishes components from servicess to increase modularity and reusability.

By seperating a component's view-related functionality from other kinds of processing, you can make your component classes lean and efficient

A component can delegate certain tasks to services, such as fetching data from the server, validating user input, or logging directly to the console

