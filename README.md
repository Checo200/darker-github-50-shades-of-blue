 # darker-github-50-shades-of-blue
CSS tweaks (for userstyles) to make github darker so the white pages won't hurt your eyes.

This is a userstyle theme made for github.com. It is made darker, since i personally don't like the white pages from GitHub. They burn my eyes! Tried to keep as close as the official design from GitHub as possible, while making everything darker / "blueish".
 # Color Variables Scheme:
```css
	--color-scale-black: #f8f9fa;
    --color-scale-white: #636363;

	/* Colors Scale Gray */
	--color-scale-gray-0: #f8f9fa;
	--color-scale-gray-1: #f1f3f5;
	--color-scale-gray-2: #e9ecef;
	--color-scale-gray-3: #dee2e6;
	--color-scale-gray-4: #ced4da;
	--color-scale-gray-5: #adb5bd;
	--color-scale-gray-6: #868e96;
	--color-scale-gray-7: #495057;
	--color-scale-gray-8: #343a40;
	--color-scale-gray-9: #212529;
    /* Colors Scale Gray - End */

	/* Colors Scale Blue */
	--color-scale-blue-0: #e7f5ff;
	--color-scale-blue-1: #d0ebff;
	--color-scale-blue-2: #a5d8ff;
	--color-scale-blue-3: #74c0fc;
	--color-scale-blue-4: #4dabf7;
	--color-scale-blue-5: #339af0;
	--color-scale-blue-6: #339af0;
	--color-scale-blue-7: #1c7ed6;
	--color-scale-blue-8: #1971c2;
	--color-scale-blue-9: #1864ab;
    /* Colors Scale Blue - End */

	/* Colors Scale Green */
	--color-scale-green-0: #ebfbee;
	--color-scale-green-1: #d3f9d8;
	--color-scale-green-2: #b2f2bb;
	--color-scale-green-3: #8ce99a;
	--color-scale-green-4: #69db7c;
	--color-scale-green-5: #51cf66;
	--color-scale-green-6: #40c057;
	--color-scale-green-7: #37b24d;
	--color-scale-green-8: #2f9e44;
	--color-scale-green-9: #2b8a3e;
    /* Colors Scale Green - End */

	/* Colors Scale Yellow */
	--color-scale-yellow-0: #fff9e8;
	--color-scale-yellow-1: #fef3d1;
	--color-scale-yellow-2: #feedba;
	--color-scale-yellow-3: #fee7a3;
	--color-scale-yellow-4: #fee28c;
	--color-scale-yellow-5: #fddc75;
	--color-scale-yellow-6: #fdd65e;
	--color-scale-yellow-7: #fdd047;
	--color-scale-yellow-8: #fcca30;
	--color-scale-yellow-9: #fcc419;
    /* Colors Scale Yellow - End */

	/* Colors Scale Orange */
	--color-scale-orange-0: #fff2e8;
	--color-scale-orange-1: #ffe5d0;
	--color-scale-orange-2: #fed8b9;
	--color-scale-orange-3: #fecba1;
	--color-scale-orange-4: #febf8a;
	--color-scale-orange-5: #feb272;
	--color-scale-orange-6: #fea55b;
	--color-scale-orange-7: #fd9843;
	--color-scale-orange-8: #fd8b2c;
	--color-scale-orange-9: #fd7e14;
    /* Colors Scale Orange - End */

	/* Colors Scale Red */
	--color-scale-red-0: #fff5f5;
	--color-scale-red-1: #ffe3e3;
	--color-scale-red-2: #ffc9c9;
	--color-scale-red-3: #ffa8a8;
	--color-scale-red-4: #ff8787;
	--color-scale-red-5: #ff6b6b;
	--color-scale-red-6: #fa5252;
	--color-scale-red-7: #f03e3e;
	--color-scale-red-8: #e03131;
	--color-scale-red-9: #c92a2a;
    /* Colors Scale Red - End */

	/* Colors Scale Purple */
	--color-scale-purple-0: #f3f0ff;
	--color-scale-purple-1: #e5dbff;
	--color-scale-purple-2: #d0bfff;
	--color-scale-purple-3: #b197fc;
	--color-scale-purple-4: #9775fa;
	--color-scale-purple-5: #845ef7;
	--color-scale-purple-6: #7950f2;
	--color-scale-purple-7: #7048e8;
	--color-scale-purple-8: #6741d9;
	--color-scale-purple-9: #5f3dc4;
    /* Colors Scale Purple - End */

	/* Colors Scale Pink */
	--color-scale-pink-0: #fff0f6;
	--color-scale-pink-1: #ffdeeb;
	--color-scale-pink-2: #fcc2d7;
	--color-scale-pink-3: #faa2c1;
	--color-scale-pink-4: #f783ac;
	--color-scale-pink-5: #f06595;
	--color-scale-pink-6: #e64980;
	--color-scale-pink-7: #d6336c;
	--color-scale-pink-8: #c2255c;
	--color-scale-pink-9: #a61e4d;
    /* Colors Scale Pink - End */

    /* Colors auto Black */
	--color-auto-black: #0a3357;
    --color-auto-black: #f8f9fa;
    /* Colors auto Black - End */

    /* Colors Auto Gray */
	--color-auto-gray-0: #f8f9fa;
	--color-auto-gray-1: #f1f3f5;
	--color-auto-gray-2: #e9ecef;
	--color-auto-gray-3: #dee2e6;
	--color-auto-gray-4: #ced4da;
	--color-auto-gray-5: #adb5bd;
	--color-auto-gray-6: #868e96;
	--color-auto-gray-7: #495057;
	--color-auto-gray-8: #343a40;
	--color-auto-gray-9: #212529;
    /* Colors Auto Gray - End */

	/* Colors Auto Blue */
	--color-auto-blue-0: #e7f5ff;
	--color-auto-blue-1: #d0ebff;
	--color-auto-blue-2: #d0ebff;
	--color-auto-blue-3: #74c0fc;
	--color-auto-blue-4: #4dabf7;
	--color-auto-blue-5: #339af0;
	--color-auto-blue-6: #228be6;
	--color-auto-blue-7: #1c7ed6;
	--color-auto-blue-8: #1971c2;
	--color-auto-blue-9: #1864ab;
    /* Colors Auto Blue - End */

	/* Colors Auto Green */
	--color-auto-green-0: #ebfbee;
	--color-auto-green-1: #d3f9d8;
	--color-auto-green-2: #b2f2bb;
	--color-auto-green-3: #8ce99a;
	--color-auto-green-4: #69db7c;
	--color-auto-green-5: #51cf66;
	--color-auto-green-6: #40c057;
	--color-auto-green-7: #37b24d;
	--color-auto-green-8: #2f9e44;
	--color-auto-green-9: #2b8a3e;
    /* Colors Auto Green - End */

	/* Colors Auto Yellow */
	--color-auto-yellow-0: #fff9e8;
	--color-auto-yellow-1: #fef3d1;
	--color-auto-yellow-2: #feedba;
	--color-auto-yellow-3: #feedba;
	--color-auto-yellow-4: #fee28c;
	--color-auto-yellow-5: #fddc75;
	--color-auto-yellow-6: #fdd65e;
	--color-auto-yellow-7: #fdd047;
	--color-auto-yellow-8: #fcca30;
    --color-auto-yellow-9: #fcc419;
    /* Colors Auto Yellow - End */

	/* Colors Auto Orange */
	--color-auto-orange-0: #fff2e8;
	--color-auto-orange-1: #ffe5d0;
	--color-auto-orange-2: #fed8b9;
	--color-auto-orange-3: #fecba1;
	--color-auto-orange-4: #febf8a;
	--color-auto-orange-5: #feb272;
	--color-auto-orange-6: #fea55b;
	--color-auto-orange-7: #fd9843;
	--color-auto-orange-8: #fd8b2c;
	--color-auto-orange-9: #fd7e14;
    /* Colors Auto Orange - End */

	/* Colors Auto Red */
	--color-auto-red-0: #fff5f5;
	--color-auto-red-1: #ffe3e3;
	--color-auto-red-2: #ffc9c9;
	--color-auto-red-3: #ffa8a8;
	--color-auto-red-4: #ff8787;
	--color-auto-red-5: #ff6b6b;
	--color-auto-red-6: #fa5252;
	--color-auto-red-7: #f03e3e;
	--color-auto-red-8: #e03131;
	--color-auto-red-9: #c92a2a;
    /* Colors Auto Red - End */

	/* Colors Auto Purple */
	--color-auto-purple-0: #f3f0ff;
	--color-auto-purple-1: #e5dbff;
	--color-auto-purple-2: #d0bfff;
	--color-auto-purple-3: #b197fc;
	--color-auto-purple-4: #9775fa;
	--color-auto-purple-5: #845ef7;
	--color-auto-purple-6: #7950f2;
	--color-auto-purple-7: #7048e8;
	--color-auto-purple-8: #6741d9;
	--color-auto-purple-9: #5f3dc4;
    /* Colors Auto Purple - End */

	/* Colors Auto Pink */
	--color-auto-pink-0: #fff0f6;
	--color-auto-pink-1: #ffdeeb;
	--color-auto-pink-2: #fcc2d7;
	--color-auto-pink-3: #faa2c1;
	--color-auto-pink-4: #f783ac;
	--color-auto-pink-5: #f06595;
	--color-auto-pink-6: #e64980;
	--color-auto-pink-7: #d6336c;
	--color-auto-pink-8: #c2255c;
	--color-auto-pink-9: #a61e4d;
    /* Colors Auto Pink - End */

	/* Colors Text */
	--color-text-primary: #f8f9fa;
	--color-text-secondary: #c9c9c9;
	--color-text-tertiary: #f0f0f0;
	--color-text-placeholder: #4a6b8c;
	--color-text-disabled: #02336b;
	--color-text-inverse: #f8f9fa;
	--color-text-link: #68a3e6;
	--color-text-danger: #e03131;
	--color-text-success: #51cf66;
	--color-text-warning: #e39e21;
	--color-text-white: #f8f9fa;
	--color-text-link-primary: #1a6bb8;
	--color-text-link-secondary: #165c9e;
	--color-text-link-tertiary: #1b73c4;
    /* Colors Text - End */

	/* Colors Icon */
	--color-icon-info: #339af0;
	--color-icon-danger: #fa5252;
	--color-icon-success: #51cf66;
	--color-icon-warning: #e39e21;
    /* Colors Icon - End */

	/* Color Border */
	--color-border-primary: #1864ab;
	--color-border-secondary: #1a6bb8;
	--color-border-tertiary: #2391f7;
	--color-border-inverse: #f8f9fa;
	--color-border-info: #339af0;
	--color-border-danger: #fa5252;
	--color-border-success: #47b559;
	--color-border-warning: #f0d018;
    /* Color Border - End*/

	/* Background Colors */
	--color-bg-canvas: #223140;
	--color-bg-canvas-mobile: #223140;
	--color-bg-canvas-inverse: #1b2733;
	--color-bg-canvas-inset: #1b2733;
	--color-bg-primary: #223140;
	--color-bg-secondary: #2f4459;
	--color-bg-tertiary: #1b2733;
	--color-bg-overlay: #223140;
	--color-bg-info: #30455a;
	--color-bg-info-inverse: #4f7295;
	--color-bg-danger: #ffa8a8;
	--color-bg-danger-inverse: #fa5252;
	--color-bg-success: #56cc7f;
	--color-bg-success-inverse: #3b8c57;
	--color-bg-warning: #fff7d6;
	--color-bg-warning-inverse: #e39e21;
    /* Background Colors - End */

	/* Shadow Colors */
	/* Using Material Design Shadows from: https://codepen.io/sdthornton/pen/wBZdXq. */
	--color-shadow-small:0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
	--color-shadow-medium:0 3px 6px rgba(0,0,0,0.16), 0 3px 6px rgba(0,0,0,0.23);
	--color-shadow-large:0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
	--color-shadow-extra-large:0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22);
	--color-shadow-highlight:inset 0 1px 0 rgba(25,23,23,0.25);
	--color-shadow-inset:inset 0 1px 0 rgba(21,22,23,0.2);
    /* Shadow Colors - End */

	--color-state-hover-primary-bg: #0366d6;
	--color-state-hover-primary-border: #77b0e5;
	--color-state-hover-primary-text: #f8f9fa;
	--color-state-hover-primary-icon: #f8f9fa;
	--color-state-hover-secondary-bg: #1871d6;
	--color-state-hover-secondary-border: #bcd2e5;
	--color-state-selected-primary-bg: #1871d6;
	--color-state-selected-primary-border: #77b0e5;
	--color-state-selected-primary-text: #f8f9fa;
	--color-state-selected-primary-icon: #f8f9fa;
	--color-state-focus-border: #77b0e5;
	--color-state-focus-shadow:0 0 0 3px rgba(106,157,204,0.02);
	--color-fade-black-10:rgba(33,27,41,0.1);
	--color-fade-black-15:rgba(33,27,41,0.15);
	--color-fade-black-30:rgba(33,27,41,0.3);
	--color-fade-black-50:rgba(33,27,41,0.5);
	--color-fade-black-70:rgba(33,27,41,0.7);
	--color-fade-black-85:rgba(33,27,41,0.85);
	--color-fade-white-10:hsla(210,17%,98%,0.1);
	--color-fade-white-15:hsla(210,17%,95%,0.15);
	--color-fade-white-30:hsla(210,16%,93%,0.3);
	--color-fade-white-50:hsla(210,16%,91%,0.5);
	--color-fade-white-70:hsla(210,15%,91%,0.7);
	--color-fade-white-85:hsla(210,15%,89%,0.85);
	--color-alert-info-text: #212529;
	--color-alert-info-icon:rgba(33,37,41,0.6);
	--color-alert-info-bg: #3e5974;
	--color-alert-info-border:rgba(188,212,230,0.2);
	--color-alert-warn-text: #212529;
	--color-alert-warn-icon: #fac219;
	--color-alert-warn-bg: #fef3d1;
	--color-alert-warn-border:rgba(230,219,172,0.2);
	--color-alert-error-text: #212529;
	--color-alert-error-icon:rgba(224,74,74,0.6);
	--color-alert-error-bg: #ffc9c9;
	--color-alert-error-border:rgba(230,181,181,0.2);
	--color-alert-success-text: #b2f2bb;
	--color-alert-success-icon:rgba(160,217,168,0.8);
	--color-alert-success-bg: #2b8a3e;
	--color-alert-success-border:rgba(35,112,50,0.2);
	--color-autocomplete-bg: #283b4d;
	--color-autocomplete-border: #536271;
	--color-autocomplete-shadow:0 10px 20px rgba(0,0,0,0.19), 0 6px 6px rgba(0,0,0,0.23);
	--color-autocomplete-row-border: #c8cbcf;
	--color-blankslate-icon: #868e96;
	--color-btn-text: #f8f9fa;
	--color-btn-bg: #0366d6;
	--color-btn-border:rgba(53,133,222,1);
	--color-btn-shadow:0 3px 6px rgba(0,0,0,0.16), 0 3px 6px rgba(0,0,0,0.23);
	--color-btn-inset-shadow:inset 0 1px 0 hsla(209,46%,69%,0.25);
	--color-btn-hover-bg: #1565c0;
	--color-btn-hover-border:rgba(33,27,41,0.15);
	--color-btn-selected-bg: #5c97db;
	--color-btn-focus-bg: #5c97db;
	--color-btn-focus-border:rgba(139,181,230,0.15);
	--color-btn-focus-shadow:0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
	--color-btn-shadow-active:inset 0 .15em .3em rgba(139,181,230,0.15);
    --color-btn-shadow-input-focus:0 0 0 .2em rgba(3,102,214,0.3);

	/* Colors Button Primary */
	--color-btn-primary-text: #f8f9fa;
	--color-btn-primary-bg: #166bcc;
	--color-btn-primary-border:rgba(24,114,217,0.15);
	--color-btn-primary-shadow:0 3px 6px rgba(0,0,0,0.16), 0 3px 6px rgba(0,0,0,0.23);
	--color-btn-primary-inset-shadow:inset 0 1px 0 hsla(0,0%,100%,0.03);
	--color-btn-primary-hover-bg: #1257a6;
	--color-btn-primary-hover-border:rgba(15,74,140,0.15);
	--color-btn-primary-selected-bg: #4589d6;
	--color-btn-primary-selected-shadow:inset 0 1px 0 rgba(92,151,219,0.2);
	--color-btn-primary-disabled-text:hsla(210,11%,15%,0.8);
	--color-btn-primary-disabled-bg: #8bb5e6;
	--color-btn-primary-disabled-border:rgba(115,166,224,0.1);
	--color-btn-primary-focus-bg: #5c97db;
	--color-btn-primary-focus-border:rgba(69,137,214,0.15);
	--color-btn-primary-focus-shadow:0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
	--color-btn-primary-icon:hsla(210,17%,95%,0.8);
	--color-btn-primary-counter-bg:hsla(212,65%,83%,0.2);
    /* Colors Button Primary - End */

	/* Colors Button Outline */
	--color-btn-outline-text: #f8f9fa;
	--color-btn-outline-hover-text: #e9ecef;
	--color-btn-outline-hover-bg: #026be3;
	--color-btn-outline-hover-border:rgba(18,19,20,0.15);
	--color-btn-outline-hover-shadow:0 1px 0 rgba(21,22,23,0.1);
	--color-btn-outline-hover-inset-shadow:inset 0 1px 0 hsla(0,4%,5%,0.03);
	--color-btn-outline-hover-counter-bg:hsla(0,3%,8%,0.2);
	--color-btn-outline-selected-text: #e9ecef;
	--color-btn-outline-selected-bg: #67a6ee;
	--color-btn-outline-selected-border:rgba(25,27,29,0.15);
	--color-btn-outline-selected-shadow:inset 0 1px 0 rgba(14,17,20,0.2);
	--color-btn-outline-disabled-text:rgba(20,23,25,0.5);
	--color-btn-outline-disabled-bg: #b9d3f0;
	--color-btn-outline-disabled-counter-bg:rgba(115,166,224,0.05);
	--color-btn-outline-focus-border:rgba(139,181,230,0.15);
	--color-btn-outline-focus-shadow:0 0 0 3px rgba(20,96,184,0.4);
	--color-btn-outline-counter-bg:rgba(24,114,217,0.1);
    /* Colors Button Outline - End */

	/* Colors Button Danger */
	--color-btn-danger-text: #f8f9fa;
	--color-btn-danger-hover-text: #e9ecef;
	--color-btn-danger-hover-bg: #e03131;
	--color-btn-danger-hover-border:rgba(251,117,117,0.15);
	--color-btn-danger-hover-shadow:0 1px 0 rgba(200,66,66,0.1);
	--color-btn-danger-hover-inset-shadow:inset 0 1px 0 hsla(0,51%,39%,0.03);
	--color-btn-danger-hover-counter-bg:hsla(0,51%,33%,0.2);
	--color-btn-danger-selected-text: #e9ecef;
	--color-btn-danger-selected-bg: #fb6363;
	--color-btn-danger-selected-border:rgba(252,130,130,0.15);
	--color-btn-danger-selected-shadow:inset 0 1px 0 rgba(176,69,69,0.2);
	--color-btn-danger-disabled-text:rgba(215,58,73,0.5);
	--color-btn-danger-disabled-bg: #fdc1c1;
	--color-btn-danger-disabled-counter-bg:rgba(176,69,69,0.05);
	--color-btn-danger-focus-border:rgba(253,177,177,0.15);
	--color-btn-danger-focus-shadow:0 0 0 3px rgba(253,161,161,0.4);
	--color-btn-danger-counter-bg:rgba(151,59,59,0.1);
    /* Colors Button Danger - End */

	/* Colors Button Counter */
	--color-btn-counter-bg:rgba(33,27,41,0.08);
	--color-counter-text: #f8f9fa;
	--color-counter-bg:rgba(209,213,218,0.5);
	--color-counter-primary-text: #f8f9fa;
	--color-counter-primary-bg: #466685;
	--color-counter-secondary-text: #dee2e6;
    /* Colors Button Counter - End */

	/* Colors Dropdown */
	--color-dropdown-bg: #2f4459;
	--color-dropdown-border: #1864ab;
	--color-dropdown-shadow:0 3px 6px rgba(0,0,0,0.16), 0 3px 6px rgba(0,0,0,0.23);
    /* Colors Dropdown - End */

	/* Colors Label */
	--color-label-border: #0366d6;
	--color-label-primary-text: #f8f9fa;
	--color-label-primary-border: #4f94e2;
	--color-label-secondary-text: #e9ecef;
	--color-label-secondary-border: #9ac2ef;
	--color-label-info-text: #339af0;
	--color-label-info-border: #339af0;
	--color-label-success-text: #51cf66;
	--color-label-success-border: #28a745;
	--color-label-warning-text: #fac219;
	--color-label-warning-border: #f0d018;
	--color-label-danger-text: #fa5252;
	--color-label-danger-border: #e03131;
    /* Colors Label - End */

	/* Colors Input */
	--color-input-bg: #283b4d;
	--color-input-contrast-bg: #1a2835;
	--color-input-border: #1864ab;
	--color-input-shadow:inset 0 1px 2px rgba(169,177,184,0.075);
	--color-input-disabled-bg: #1c2936;
	--color-input-disabled-border: #bfc4ca;
	--color-input-warning-border: #f0d018;
	--color-input-error-border: #e03131;
    /* Colors Input - End */

	/* Colors Input Tooltip Succes */
	--color-input-tooltip-success-text: #2b8a3e;
	--color-input-tooltip-success-bg: #b2f2bb;
	--color-input-tooltip-success-border: #40c057;
    /* Colors Input Tooltip Succes - End */

	/* Colors Input Tooltip Warning */
	--color-input-tooltip-warning-text: #fac219;
	--color-input-tooltip-warning-bg: #fff5b1;
	--color-input-tooltip-warning-border: #f0d018;
    /* Colors Input Tooltip Warning - End */

	/* Colors Input Tooltip Error */
	--color-input-tooltip-error-text: #86181d;
	--color-input-tooltip-error-bg: #ffa8a8;
	--color-input-tooltip-error-border: #f97583;
    /* Colors Input Tooltip Error - End */

	/* Colors Avatar */
	--color-avatar-border:transparent;
	--color-avatar-stack-fade: #8cb2d5;
	--color-avatar-stack-fade-more: #bad1e6;
	--color-avatar-child-shadow:-2px -2px 0 hsla(208,48%,94%,0.8);
    /* Colors Avatar - End */

	/* Colors Toast IC */
	--color-toast-ic-bg-loading: #697682;
    /* Colors Toast IC - End */

	/* Colors Timeline */
	--color-timeline-text: #f1f3f5;
	--color-timeline-badge-bg: #cde0f7;
	--color-timeline-target-badge-border: #2188ff;
	--color-timeline-target-badge-shadow: #1e7be6;
    /* Colors Timeline - End */

	/* Colors Select Menu */
	--color-select-menu-bg: #293b4d;
	--color-select-menu-border: #1864ab;
	--color-select-menu-border-secondary: #2f74b3;
	--color-select-menu-shadow:0 0 18px rgba(12,50,86,0.4);
	--color-select-menu-backdrop-bg:rgba(84,98,113,0.5);
	--color-select-menu-backdrop-border:transparent;
	--color-select-menu-tap-highlight:rgba(127,137,148,0.5);
	--color-select-menu-tap-focus-bg: #a3c1dd;
    /* Colors Select Menu - End */

	/* Colors Box */
	--color-box-blue-border: #1a6bb8;
	--color-box-row-yellow-bg: #fef3d1;
	--color-box-row-blue-bg: #1864ab;
	--color-box-header-blue-bg: #446280;
	--color-box-header-blue-border: #0366d6;
    /* Colors Box - End */

    /* Colors Popover */
	--color-popover-border:rgba(1,41,86,0.15);
	/* Colors Popover - End */
	/* Colors Branchname */
	--color-branch-name-text:rgba(186,209,230,0.6);
	--color-branch-name-icon: #a3c1dd;
	--color-branch-name-bg: #023d80;
	--color-branch-name-link-text: #bad1e6;
	--color-branch-name-link-icon: #bad1e6;
	--color-branch-name-link-bg: #023d80;
    /* Colors Branchname - End */

	/* Colors Markdown */
	--color-markdown-code-bg:rgba(47,68,89,0.05);
	--color-markdown-frame-border: #dfe2e5;
	--color-markdown-blockquote-border: #dfe2e5;
	--color-markdown-table-border: #dfe2e5;
	--color-markdown-table-tr-border: #c6cbd1;
    /* Colors Markdown - End */

	/* Colors Menu */
	--color-menu-heading-text: #f8f9fa;
	--color-menu-border-active: #f0d018;
    /* Colors Menu - End */

	/* Colors Sidenav */
	--color-sidenav-selected-bg: #0f528c;
	--color-sidenav-border-active: #f0d018;
    /* Colors Sidenav - End */

	/* Colors Tabnav */
	--color-tabnav-selected-bg: #223140;
    /* Colors Tabnav - End */

	/* Colors Header */
	--color-header-text:hsla(210,17%,98%,0.7);
	--color-header-bg: #283b4d;
	--color-header-logo: #fff;
    /* Colors Header - End */

	/* Colors Filter Item bar */
	--color-filter-item-bar-bg: #364e66;
    /* Colors Filter Item bar - End  */

	/* Color Hidden Text Expander */
	--color-hidden-text-expander-bg: #3d5873;
	--color-hidden-text-expander-bg-hover: #57728d;
    /* Color Hidden Text Expander - End */

	/* Colors Drag & Drop */
	--color-drag-and-drop-border: #1864ab;
    /* Colors Drag & Drop - End */

	/* Colors Upload Enabled */
	--color-upload-enabled-border: #165a9a;
	--color-upload-enabled-border-focused: #4683bc;
    /* Colors Upload Enabled - End */

	/* Colors Previewable Comment */
	--color-previewable-comment-form-border: #161f29;
	--color-previewable-comment-form-bg: #161f29;
    /* Colors Previewable Comment - End */

	/* Underlinenav Border Colors */
	--color-underlinenav-border:rgba(176,137,18,0);
	--color-underlinenav-border-hover: #ca9d14;
	--color-underlinenav-border-active: #ca9d14;
    /* Underlinenav Border Colors - End*/

	/* Underlinenav Text Colors */
	--color-underlinenav-text: #adb5bd;
	--color-underlinenav-text-hover: #f8f9fa;
	--color-underlinenav-text-active: #f8f9fa;
    /* Underlinenav Text Colors -  End */

	/* Underlinenav Icon Colors */
	--color-underlinenav-icon: #adb5bd;
	--color-underlinenav-icon-hover: #f8f9fa;
	--color-underlinenav-icon-active: #f8f9fa;
    /* Underlinenav Icon Colors - End */

	/* Underlinenav Counter Colors */
	--color-underlinenav-counter-text: #f8f9fa;
    /* Underlinenav Counter Colors - End */

	/* Verified Badge Colors */
	--color-verified-badge-text: #2b8a3e;
	--color-verified-badge-bg: #d3f9d8;
	--color-verified-badge-border: #b2f2bb;
    /* Verified Badge Colors - End */

	/* Social Count Colors */
	--color-social-count-bg: #1257a6;
    /* Social Count Colors - End */

	/* Header Search Colors */
	--color-header-search-bg: #223140;
	--color-header-search-border: #1864ab;
	/* Header Search Colors - End */

	/* Diffstat Colors */
	--color-diffstat-neutral-bg: #d0ebff;
	--color-diffstat-neutral-border: #bbd4e6;
	--color-diffstat-deletion-bg: #fa5252;
	--color-diffstat-deletion-border: #c84242;
	--color-diffstat-addition-bg: #2f9e44;
    --color-diffstat-addition-border: #2f9e44;

	/* Diffstat Colors - End */
	--color-icon-folder: #79b8ff;
	--color-hl-author-bg: #f1f8ff;
	--color-hl-author-border: #c8e1ff;
	--color-logo-subdued: #d1d5da;
	--color-discussion-border: #a2cbac;
    /* Diff Blob Num Colors */

	--color-diff-blob-num-text:rgba(211,218,224,0.925);
	--color-diff-blob-num-hover-text:rgba(196,201,206,0.721);
    /* Diff Blob Num Colors - End */

	/* Diff Blob Addition Colors */
	--color-diff-blob-addition-num-bg: #20602c;
	--color-diff-blob-addition-line-bg: #339a46;
	--color-diff-blob-addition-word-bg: #b3e6bc;
    /* Diff Blob Addition Colors - End */

	/* Diff Blob Deletion Colors */
	--color-diff-blob-deletion-num-bg: #701919;
	--color-diff-blob-deletion-line-bg: #b32727;
	--color-diff-blob-deletion-word-bg: #f3adad;
    /* Diff Blob Deletion Colors - End */

	/* Diff Blob Hunk Colors */
	--color-diff-blob-hunk-text:rgba(248,249,250,0.7);
	--color-diff-blob-hunk-num-bg: #acbfd3;
	--color-diff-blob-hunk-line-bg: #1a2632;
    /* Diff Blob Hunk Colors - End */

	/* Diff Blob Empty Colors */
	--color-diff-blob-empty-block-bg: #587fa6;
    /* Diff Blob Empty Colors - End */

	/* Diff Blob Selected Colors */
	--color-diff-blob-selected-line-highlight-bg:rgba(255,223,93,0.2);
	--color-diff-blob-selected-line-highlight-border: #ffd33d;
    /* Diff Blob Selected Colors - End */

	/* Diff Blob Expander Colors */
	--color-diff-blob-expander-icon: #586069;
	--color-diff-blob-expander-hover-icon: #f8f9fa;
	--color-diff-blob-expander-hover-bg: #339af0;
    /* Diff Blob Expander Colors - End */

	/* Diff Blob Comment Colors */
	--color-diff-blob-comment-button-icon: #f8f9fa;
	--color-diff-blob-comment-button-bg: #339af0;
	--color-diff-blob-comment-button-gradient-bg: #0372ef;
    /* Diff Blob Comment Colors - End */

	/* Global Nav Colors */
	--color-global-nav-logo: #f8f9fa;
	--color-global-nav-bg: #283b4d;
	--color-global-nav-text: #f8f9fa;
	--color-global-nav-icon: #f8f9fa;
	--color-global-nav-input-bg: #fafbfc;
	--color-global-nav-input-border: #fafbfc;
	--color-global-nav-input-icon: #d1d5da;
	--color-global-nav-input-placeholder: #c9c9c9;
    /* Global Nav Colors - End */

	/*  Calendar Colors */
	--color-calendar-graph-day-bg: #f6fbff;
	--color-calendar-graph-day-border:rgba(241,249,255,0.06);
	--color-calendar-graph-day-L1-bg: #538aca;
	--color-calendar-graph-day-L2-bg: #4b7cb6;
	--color-calendar-graph-day-L3-bg: #426ea2;
	--color-calendar-graph-day-L4-bg: #3a618d;
	--color-calendar-graph-day-L4-border:rgba(58,97,141,0.06);
	--color-calendar-graph-day-L3-border:rgba(66,110,162,0.06);
	--color-calendar-graph-day-L2-border:rgba(75,124,182,0.06);
	--color-calendar-graph-day-L1-border:rgba(83,138,202,0.06);
    /* Calendar Colors - End */

	/* footer invertocat Colors */
	--color-footer-invertocat-octicon: #d1d5da;
	--color-footer-invertocat-octicon-hover: #6a737d;
    /* footer invertocat Colors - End */

	/* PR State Colors */
	--color-pr-state-draft-text: #f8f9fa;
	--color-pr-state-draft-bg: #6a737d;
	--color-pr-state-draft-border:transparent;
	--color-pr-state-open-text: #f8f9fa;
	--color-pr-state-open-bg: #28a745;
	--color-pr-state-open-border:transparent;
	--color-pr-state-merged-text: #f8f9fa;
	--color-pr-state-merged-bg: #7048e8;
	--color-pr-state-merged-border:transparent;
	--color-pr-state-closed-text: #f8f9fa;
	--color-pr-state-closed-bg: #fa5252;
	--color-pr-state-closed-border:transparent;
    /* PR State Colors - End */

	/* Topic tag Colors */
	--color-topic-tag-text: #212529;
	--color-topic-tag-bg: #9ac2ef;
	--color-topic-tag-hover-bg: #81b3eb;
	--color-topic-tag-active-bg: #81b3eb;
    /* Topic tag Colors - End */

	/* Merge Box Succes Colors */
	--color-merge-box-success-icon-bg: #28a745;
	--color-merge-box-success-icon-text: #ecf9ee;
	--color-merge-box-success-icon-border:transparent;
	--color-merge-box-success-indicator-bg: #28a745;
	--color-merge-box-success-indicator-border:transparent;
    /* Merge Box Succes Colors - End */

	/* Merge Box Merged Colors */
	--color-merge-box-merged-icon-bg: #7048e8;
	--color-merge-box-merged-icon-text: #f3f0ff;
	--color-merge-box-merged-icon-border:transparent;
	--color-merge-box-merged-box-border: #e5dbff;
    /* Merge Box Merged Colors - End */

	/* Merge Box Neutral Colors */
	--color-merge-box-neutral-icon-bg: #697682;
	--color-merge-box-neutral-icon-text: #f8f9fa;
	--color-merge-box-neutral-icon-border:transparent;
	--color-merge-box-neutral-indicator-bg: #697682;
	--color-merge-box-neutral-indicator-border:transparent;
    /* Merge Box Neutral Colors - End */

	/* Merge Box Warning Colors */
	--color-merge-box-warning-icon-bg: #e3b017;
	--color-merge-box-warning-icon-text: #fff9e8;
	--color-merge-box-warning-icon-border:transparent;
	--color-merge-box-warning-box-border: #fcc419;
    /* Merge Box Warning Colors - End */

	/* Merge Box Error Colors */
	--color-merge-box-error-icon-bg: #fa5252;
	--color-merge-box-error-icon-text: #fee;
	--color-merge-box-error-icon-border:transparent;
	--color-merge-box-error-indicator-bg: #fa5252;
	--color-merge-box-error-indicator-border:transparent;
	/* Merge Box Error Colors - End */
```

