## Blade Template Engine Snippets

* @ext - @extends('`name`')
* @sec - @section('`name`') @endsection
* @secy - @section('`name`') @yield_section
* @yl - @yield('`name`')
* @par - @parent
* @}} - {{ $`var` }}
* @}}} - {{ `expression` }}
* @inc - @include('`name`')

* @if - @if (`condition`) @endif
* @ife - @if (`condition`) @else @endif
* @foreach - @foreach(`$array` as `$element`) @endforeach
* @fore - @forelse (`$array` as `$element`) @endforelse
* @for - @for (`$i` = `0`; `$i` `<` `…`; `$i++`) @endfor
* @while - @while (`condition`) @endwhile
* @unless - @unless (`condition`) @endunless

##Deprecated

* @lay - @extends('`name`')
    Still functional but modified to use extends rather than layout