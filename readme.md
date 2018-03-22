# TACHYONS LESS

Functional css for humans.

Quickly build and design new UI without writing css.

This is a fork of [Tachyons](https://github.com/tachyons-css/tachyons) with values being
configurable in a single variables file. More information about Tachyons can be found at http://tachyons.io

##### src/_variables.less
```
/*

    VARIABLES   

*/

@breakpoint-not-small: ~'screen and (min-width: 30em)';
@breakpoint-medium: ~'screen and (min-width: 30em) and (max-width: 60em)';
@breakpoint-large: ~'screen and (min-width: 60em)';

@sans-serif: -apple-system, BlinkMacSystemFont, 'avenir next', avenir, helvetica, 'helvetica neue', ubuntu, roboto, noto, 'segoe ui', arial, sans-serif;
@serif: georgia, serif;
@code: consolas, monaco, monospace;

@font-size-headline: 6rem;
@font-size-subheadline: 5rem;
@font-size-1: 3rem;
@font-size-2: 2.25rem;
@font-size-3: 1.5rem;
@font-size-4: 1.25rem;
@font-size-5: 1rem;
@font-size-6: .875rem;
@font-size-7: .75rem;

@letter-spacing-tight:-.05em;
@letter-spacing-1:.1em;
@letter-spacing-2:.25em;

@line-height-solid: 1;
@line-height-title: 1.25;
@line-height-copy: 1.5;

@measure: 30em;
@measure-narrow: 20em;
@measure-wide: 34em;

@spacing-none: 0;
@spacing-extra-small: .25rem;
@spacing-small: .5rem;
@spacing-medium: 1rem;
@spacing-large: 2rem;
@spacing-extra-large: 4rem;
@spacing-extra-extra-large: 8rem;
@spacing-extra-extra-extra-large: 16rem;
@spacing-copy-separator: 1.5em;

@height-1: 1rem;
@height-2: 2rem;
@height-3: 4rem;
@height-4: 8rem;
@height-5: 16rem;

@width-1: 1rem;
@width-2: 2rem;
@width-3: 4rem;
@width-4: 8rem;
@width-5: 16rem;

@max-width-1: 1rem;
@max-width-2: 2rem;
@max-width-3: 4rem;
@max-width-4: 8rem;
@max-width-5: 16rem;
@max-width-6: 32rem;
@max-width-7: 48rem;
@max-width-8: 64rem;
@max-width-9: 96rem;

@border-radius-none: 0;
@border-radius-1: .125rem;
@border-radius-2: .25rem;
@border-radius-3: .5rem;
@border-radius-4: 1rem;
@border-radius-circle: 100%;
@border-radius-pill: 9999px;

@border-width-none: 0;
@border-width-1: .125rem;
@border-width-2: .25rem;
@border-width-3: .5rem;
@border-width-4: 1rem;
@border-width-5: 2rem;

@box-shadow-1: 0px 0px 4px 2px rgba( 0, 0, 0, 0.2 );
@box-shadow-2: 0px 0px 8px 2px rgba( 0, 0, 0, 0.2 );
@box-shadow-3: 2px 2px 4px 2px rgba( 0, 0, 0, 0.2 );
@box-shadow-4: 2px 2px 8px 0px rgba( 0, 0, 0, 0.2 );
@box-shadow-5: 4px 4px 8px 0px rgba( 0, 0, 0, 0.2 );

@black: #000;
@near-black: #111;
@dark-gray:#333;
@mid-gray:#555;
@gray: #777;
@silver: #999;
@light-silver: #aaa;
@moon-gray: #ccc;
@light-gray: #eee;
@near-white: #f4f4f4;
@white: #fff;

@transparent:transparent;

@black-90: rgba(0,0,0,.9);
@black-80: rgba(0,0,0,.8);
@black-70: rgba(0,0,0,.7);
@black-60: rgba(0,0,0,.6);
@black-50: rgba(0,0,0,.5);
@black-40: rgba(0,0,0,.4);
@black-30: rgba(0,0,0,.3);
@black-20: rgba(0,0,0,.2);
@black-10: rgba(0,0,0,.1);
@black-05: rgba(0,0,0,.05);
@black-025: rgba(0,0,0,.025);
@black-0125: rgba(0,0,0,.0125);

@white-90: rgba(255,255,255,.9);
@white-80: rgba(255,255,255,.8);
@white-70: rgba(255,255,255,.7);
@white-60: rgba(255,255,255,.6);
@white-50: rgba(255,255,255,.5);
@white-40: rgba(255,255,255,.4);
@white-30: rgba(255,255,255,.3);
@white-20: rgba(255,255,255,.2);
@white-10: rgba(255,255,255,.1);
@white-05: rgba(255,255,255,.05);
@white-025: rgba(255,255,255,.025);
@white-0125: rgba(255,255,255,.0125);

@dark-red:  #e7040f;
@red:  #ff4136;
@light-red:  #ff725c;
@orange:  #ff6300;
@gold:  #ffb700;
@yellow:  #ffd700;
@light-yellow:  #fbf1a9;
@purple:  #5e2ca5;
@light-purple:  #a463f2;
@dark-pink:  #d5008f;
@hot-pink: #ff41b4;
@pink:  #ff80cc;
@light-pink:  #ffa3d7;
@dark-green:  #137752;
@green:  #19a974;
@light-green:  #9eebcf;
@navy:  #001b44;
@dark-blue:  #00449e;
@blue:  #357edd;
@light-blue:  #96ccff;
@lightest-blue:  #cdecff;
@washed-blue:  #f6fffe;
@washed-green:  #e8fdf5;
@washed-yellow:  #fffceb;
@washed-red:  #ffdfdf;
```

## Getting started

Docs can be found at http://tachyons.io/docs
The modules are generally pretty small and thus easy to read and grock if you're familiar with css at all.


## License

MIT


## Credits

http://tachyons.io/

https://github.com/tachyons-css/tachyons-custom