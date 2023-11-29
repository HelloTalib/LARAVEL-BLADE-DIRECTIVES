Certainly! Below is a more comprehensive list of Laravel Blade directives:

| Directive                           | Description                                           |
| ----------------------------------- | ----------------------------------------------------- |
| `@extends('layout')`                 | Extends a layout view.                                |
| `@section('content')`               | Defines a section in a view.                          |
| `@show`                             | Display the content of the current section.           |
| `@yield('content')`                 | Outputs the content of a section.                     |
| `@include('view')`                  | Includes another view.                                |
| `@includeIf('view', ['some' => 'data'])` | Includes another view if the given condition is true. |
| `@includeWhen($condition, 'view', ['some' => 'data'])` | Includes another view when the given condition is true. |
| `@each('item.view', $items, 'item')` | Loops over a collection and includes a view for each item. |
| `@if($condition)`                   | Starts an if statement.                               |
| `@elseif($condition)`                | Adds an else if clause to an if statement.            |
| `@else`                             | Adds an else clause to an if statement.               |
| `@endif`                            | Ends an if statement.                                 |
| `@unless($condition)`                | Starts an unless statement.                           |
| `@endunless`                        | Ends an unless statement.                             |
| `@for($i = 0; $i < 10; $i++)`       | Starts a for loop.                                    |
| `@endfor`                           | Ends a for loop.                                      |
| `@foreach($items as $item)`         | Starts a foreach loop.                                |
| `@endforeach`                        | Ends a foreach loop.                                  |
| `@while($condition)`                | Starts a while loop.                                  |
| `@endwhile`                         | Ends a while loop.                                    |
| `@isset($variable)`                 | Checks if a variable is set.                         |
| `@empty($variable)`                 | Checks if a variable is empty.                       |
| `@switch($value)`                   | Starts a switch statement.                            |
| `@case($value)`                     | Defines a case in a switch statement.                |
| `@default`                          | Defines the default case in a switch statement.      |
| `@endswitch`                        | Ends a switch statement.                              |
| `@auth`                             | Checks if the user is authenticated.                 |
| `@guest`                            | Checks if the user is a guest.                       |
| `@csrf`                             | Outputs the CSRF token.                               |
| `@error('field')`                   | Outputs the validation error message for a field.    |
| `@env('environment')`               | Checks the application environment.                  |
| `@json($data)`                      | Converts a variable to JSON format.                  |
| `@verbatim`                         | Treats enclosed content as raw text.                 |
| `@php`                              | Executes PHP code.                                    |
| `@push('scripts')`                  | Pushes content to a stack for later use.             |
| `@stack('scripts')`                 | Outputs the content of a stack.                      |
| `@hasSection('section')`            | Checks if a section is defined.                      |
| `@inertia`                          | Renders an Inertia page.                             |
| `@lang`                             | Translates the given key.                            |
| `@choice`                           | Translates the given key with pluralization.         |
| `@verbatim`                         | Treats enclosed content as raw text.                 |

This list covers many of the commonly used Blade directives, but keep in mind that Laravel is a dynamic framework, and new features and directives may be introduced in later versions. Always refer to the official Laravel documentation for the most up-to-date information: [Laravel Blade Templates](https://laravel.com/docs/8.x/blade).
