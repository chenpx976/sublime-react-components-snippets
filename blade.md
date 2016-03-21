# Blade Snippets for Sublime Text
##Avalable snippets

| Shortcut  | Result |
|-----------|--------|
| can       | @can('`policy`', $model) <br /> **{{-- expr --\}\}** <br /> @endcan |
| cane      | @can('`policy`', $model) <br /> **{{-- expr --\}\}** <br /> @else <br /> **{{-- expr --\}\}** @endcan |
| ext		| @extends('`name`') |
| lay		| @layout('`name`')  |
| sec		| @section('`name`') <br /> **{{-- expr --\}\}** <br /> @endsection    |
| secy		| @section('`name`') <br /> **{{-- expr --\}\}** <br /> @yield_section |
| yl		| @yield('`section`', '`default`') |
| lsec		| @section('`name`') <br /> **{{-- expr --\}\}** <br /> @show |
| par       | @parent   |
| stack		| @stack('`name`')	|
| push      | @push('`name`') <br /> **{{-- expr --\}\}** <br /> @endpush    |
| !!		| {!! $`var` !!}	|
| }}		| {{ `escaped output` }}	|
| inc		| @include('`view.name`', `array('some' => 'data')`)  |
| if		| @if (`condition`) <br /> **{{-- expr --\}\}** <br /> @endif   |
| ife		| @if (`condition`) <br /> **{{-- expr --\}\}** <br /> @else <br /> **{{-- expr --\}\}** <br /> @endif  |
| foreach	| @foreach(`$array` as `$element`) <br /> **{{-- expr --\}\}** <br /> @endforeach  |
| fore		| @forelse (`$array` as `$element`) <br /> **{{-- expr --\}\}** <br /> @endforelse  |
| for		| @for (`$i` = `0`; `$i` `<` `…`; `$i++`) <br /> **{{-- expr --\}\}** <br /> @endfor  |
| each		| @each ('`item.view`', $`items`, '`item`', '`empty.view`')
| trans		| {{ trans('`language.line`') }}	|
| route		| {{ route('`name`') }}	|
| asset     | {{ asset('`path`') }} |
| url		| {{ url('`path`') }}	|
| while		| @while (`condition`) <br /> **{{-- expr --\}\}** <br /> @endwhile  |
| unless	| @unless (`condition`) <br /> **{{-- expr --\}\}** <br /> @endunless  |
| choise	| @choice('`language.line`', $`number`)  |
| comment	| {{-- `comment` --}}	|
| lang		| @lang('`language.line`', array('`variable` => '`replacement`'))  |


---
Original snippets by:
[@dev4dev](https://github.com/dev4dev)

Cool Readme formatting and latest updates belong to:
* Github: [@AAlakkad](https://github.com/AAlakkad).
* Twitter: [@Am_Alakkad](https://twitter.com/Am_Alakkad).
* Email: [am.alakkad@gmail.com](mailto:am.alakkad@gmail.com).