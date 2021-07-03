(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var p;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function ca(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var da=ca(this);function t(a,b){if(b)a:{var c=da;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
t("Symbol",function(a){function b(e){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c("jscomp_symbol_"+(e||"")+"_"+d++,e)}
function c(e,f){this.h=e;ba(this,"description",{configurable:!0,writable:!0,value:f})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d=0;return b});
t("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=da[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return ea(aa(this))}})}return a});
function ea(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function u(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
var fa="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ha;
if("function"==typeof Object.setPrototypeOf)ha=Object.setPrototypeOf;else{var ia;a:{var ja={a:!0},ka={};try{ka.__proto__=ja;ia=ka.a;break a}catch(a){}ia=!1}ha=ia?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var la=ha;
function ma(a,b){a.prototype=fa(b.prototype);a.prototype.constructor=a;if(la)la(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.A=b.prototype}
function na(){this.o=!1;this.l=null;this.i=void 0;this.h=1;this.u=this.j=0;this.m=null}
function oa(a){if(a.o)throw new TypeError("Generator is already running");a.o=!0}
na.prototype.s=function(a){this.i=a};
function pa(a,b){a.m={X:b,ra:!0};a.h=a.j||a.u}
na.prototype.return=function(a){this.m={return:a};this.h=this.u};
function y(a,b,c){a.h=c;return{value:b}}
function qa(a){a.j=0;var b=a.m.X;a.m=null;return b}
function ra(a){this.h=new na;this.i=a}
function sa(a,b){oa(a.h);var c=a.h.l;if(c)return ta(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return ua(a)}
function ta(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.o=!1,e;var f=e.value}catch(g){return a.h.l=null,pa(a.h,g),ua(a)}a.h.l=null;d.call(a.h,f);return ua(a)}
function ua(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.o=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,pa(a.h,c)}a.h.o=!1;if(a.h.m){b=a.h.m;a.h.m=null;if(b.ra)throw b.X;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function va(a){this.next=function(b){oa(a.h);a.h.l?b=ta(a,a.h.l.next,b,a.h.s):(a.h.s(b),b=ua(a));return b};
this.throw=function(b){oa(a.h);a.h.l?b=ta(a,a.h.l["throw"],b,a.h.s):(pa(a.h,b),b=ua(a));return b};
this.return=function(b){return sa(a,b)};
this[Symbol.iterator]=function(){return this}}
function z(a,b){b=new va(new ra(b));la&&a.prototype&&la(b,a.prototype);return b}
t("Reflect.setPrototypeOf",function(a){return a?a:la?function(b,c){try{return la(b,c),!0}catch(d){return!1}}:null});
function wa(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
t("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=wa(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
t("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=wa(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
t("Object.setPrototypeOf",function(a){return a||la});
function A(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
var xa="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)A(d,e)&&(a[e]=d[e])}return a};
t("Object.assign",function(a){return a||xa});
t("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.s=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.m()})}this.h.push(g)};
var e=da.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.m=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(m){k||(k=!0,l.call(h,m))}}
var h=this,k=!1;return{resolve:g(this.ea),reject:g(this.m)}};
b.prototype.ea=function(g){if(g===this)this.m(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.ga(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.da(g):this.o(g)}};
b.prototype.da=function(g){var h=void 0;try{h=g.then}catch(k){this.m(k);return}"function"==typeof h?this.ha(h,g):this.o(g)};
b.prototype.m=function(g){this.u(2,g)};
b.prototype.o=function(g){this.u(1,g)};
b.prototype.u=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.fa();this.C()};
b.prototype.fa=function(){var g=this;e(function(){if(g.J()){var h=da.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.J=function(){if(this.s)return!1;var g=da.CustomEvent,h=da.Event,k=da.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=da.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.C=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.ga=function(g){var h=this.l();g.O(h.resolve,h.reject)};
b.prototype.ha=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(r,q){return"function"==typeof r?function(x){try{l(r(x))}catch(v){m(v)}}:q}
var l,m,n=new b(function(r,q){l=r;m=q});
this.O(k(g,l),k(h,m));return n};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.O=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.s=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=u(g),m=l.next();!m.done;m=l.next())d(m.value).O(h,k)})};
b.all=function(g){var h=u(g),k=h.next();return k.done?d([]):new b(function(l,m){function n(x){return function(v){r[x]=v;q--;0==q&&l(r)}}
var r=[],q=0;do r.push(void 0),q++,d(k.value).O(n(r.length-1),m),k=h.next();while(!k.done)})};
return b});
t("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
t("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
t("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==wa(this,b,"includes").indexOf(b,c||0)}});
t("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)A(b,d)&&c.push([d,b[d]]);return c}});
function ya(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
t("Array.prototype.keys",function(a){return a?a:function(){return ya(this,function(b){return b})}});
t("Array.prototype.values",function(a){return a?a:function(){return ya(this,function(b,c){return c})}});
t("Array.prototype.entries",function(a){return a?a:function(){return ya(this,function(b,c){return[b,c]})}});
t("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=u(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!A(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(m){if(m instanceof c)return m;Object.isExtensible(m)&&e(m);return l(m)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),m=new a([[k,2],[l,3]]);if(2!=m.get(k)||3!=m.get(l))return!1;m.delete(k);m.set(l,4);return!m.has(k)&&4==m.get(l)}catch(n){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!A(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&A(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&A(k,g)&&A(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&A(k,g)&&A(k[g],this.h)?delete k[g][this.h]:!1};
return b});
t("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
t("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.h;return ea(function(){if(l){for(;l.head!=h.h;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var m=h.i[l];if(m&&A(h.i,l))for(h=0;h<m.length;h++){var n=m[h];if(k!==k&&n.key!==n.key||k===n.key)return{id:l,list:m,index:h,v:n}}return{id:l,list:m,index:-1,v:void 0}}
function e(h){this.i={};this.h=b();this.size=0;if(h){h=u(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(u([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),m=l.next();if(m.done||m.value[0]!=h||"s"!=m.value[1])return!1;m=l.next();return m.done||4!=m.value[0].x||"t"!=m.value[1]||!l.next().done?!1:!0}catch(n){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.i[l.id]=[]);l.v?l.v.value=k:(l.v={next:this.h,previous:this.h.previous,head:this.h,key:h,value:k},l.list.push(l.v),this.h.previous.next=l.v,this.h.previous=l.v,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.v&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.i[h.id],h.v.previous.next=h.v.next,h.v.next.previous=h.v.previous,h.v.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.i={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).v};
e.prototype.get=function(h){return(h=d(this,h).v)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),m;!(m=l.next()).done;)m=m.value,h.call(k,m[1],m[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
t("Set",function(a){function b(c){this.h=new Map;if(c){c=u(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(u([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
var B=this||self;function C(a,b){a=a.split(".");b=b||B;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function za(){}
function Aa(a){var b=typeof a;b="object"!=b?b:a?Array.isArray(a)?"array":b:"null";return"array"==b||"object"==b&&"number"==typeof a.length}
function D(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ba(a){return Object.prototype.hasOwnProperty.call(a,Ca)&&a[Ca]||(a[Ca]=++Da)}
var Ca="closure_uid_"+(1E9*Math.random()>>>0),Da=0;function Ea(a,b,c){return a.call.apply(a.bind,arguments)}
function Fa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Ga(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Ga=Ea:Ga=Fa;return Ga.apply(null,arguments)}
function E(a,b){a=a.split(".");var c=B;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function G(a,b){function c(){}
c.prototype=b.prototype;a.A=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.Ja=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Ha(a){return a}
;function Ia(a){if(Error.captureStackTrace)Error.captureStackTrace(this,Ia);else{var b=Error().stack;b&&(this.stack=b)}a&&(this.message=String(a))}
G(Ia,Error);Ia.prototype.name="CustomError";function Ja(){var a=/[?&]dsh=1(&|$)/.test("/generate_204");this.j=!a&&/[?&]ae=1(&|$)/.test("/generate_204");this.l=!a&&/[?&]ae=2(&|$)/.test("/generate_204");if((this.h=/[?&]adurl=([^&]*)/.exec("/generate_204"))&&this.h[1]){try{var b=decodeURIComponent(this.h[1])}catch(c){b=null}this.i=b}}
;function Ka(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var La=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},H=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},Ma=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
H(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function Na(a,b){a:{for(var c=a.length,d="string"===typeof a?a.split(""):a,e=0;e<c;e++)if(e in d&&b.call(void 0,d[e],e,a)){b=e;break a}b=-1}return 0>b?null:"string"===typeof a?a.charAt(b):a[b]}
function Oa(a,b){b=La(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function Pa(a){return Array.prototype.concat.apply([],arguments)}
function Qa(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function Ra(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(Aa(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function Sa(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function Ta(a){var b=Ua,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function Va(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function Wa(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=Wa(a[c]);return b}
var Xa="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function Ya(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<Xa.length;f++)c=Xa[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var Za;var $a=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]},ab=/&/g,bb=/</g,cb=/>/g,db=/"/g,eb=/'/g,fb=/\x00/g,gb=/[\x00&<>"']/;var I;a:{var hb=B.navigator;if(hb){var ib=hb.userAgent;if(ib){I=ib;break a}}I=""}function J(a){return-1!=I.indexOf(a)}
;function jb(a){this.h=kb===kb?a:""}
jb.prototype.toString=function(){return this.h.toString()};
var kb={};var lb=/^(?:([^:/?#.]+):)?(?:\/\/(?:([^\\/?#]*)@)?([^\\/?#]*?)(?::([0-9]+))?(?=[\\/?#]|$))?([^?#]+)?(?:\?([^#]*))?(?:#([\s\S]*))?$/;function mb(a){return a?decodeURI(a):a}
function nb(a){return mb(a.match(lb)[3]||null)}
function ob(a){var b=a.match(lb);a=b[1];var c=b[2],d=b[3];b=b[4];var e="";a&&(e+=a+":");d&&(e+="//",c&&(e+=c+"@"),e+=d,b&&(e+=":"+b));return e}
function pb(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)pb(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function qb(a){var b=[],c;for(c in a)pb(c,a[c],b);return b.join("&")}
var rb=/#|$/;function sb(a,b){var c=a.search(rb);a:{var d=0;for(var e=b.length;0<=(d=a.indexOf(b,d))&&d<c;){var f=a.charCodeAt(d-1);if(38==f||63==f)if(f=a.charCodeAt(d+e),!f||61==f||38==f||35==f)break a;d+=e+1}d=-1}if(0>d)return null;e=a.indexOf("&",d);if(0>e||e>c)e=c;d+=b.length+1;return decodeURIComponent(a.substr(d,e-d).replace(/\+/g," "))}
;function K(a,b){var c=void 0;return new (c||(c=Promise))(function(d,e){function f(k){try{h(b.next(k))}catch(l){e(l)}}
function g(k){try{h(b["throw"](k))}catch(l){e(l)}}
function h(k){k.done?d(k.value):(new c(function(l){l(k.value)})).then(f,g)}
h((b=b.apply(a,void 0)).next())})}
;function tb(){return J("iPhone")&&!J("iPod")&&!J("iPad")}
;function ub(a){ub[" "](a);return a}
ub[" "]=za;var vb=J("Opera"),wb=J("Trident")||J("MSIE"),xb=J("Edge"),yb=J("Gecko")&&!(-1!=I.toLowerCase().indexOf("webkit")&&!J("Edge"))&&!(J("Trident")||J("MSIE"))&&!J("Edge"),zb=-1!=I.toLowerCase().indexOf("webkit")&&!J("Edge");function Ab(){var a=B.document;return a?a.documentMode:void 0}
var Bb;a:{var Cb="",Db=function(){var a=I;if(yb)return/rv:([^\);]+)(\)|;)/.exec(a);if(xb)return/Edge\/([\d\.]+)/.exec(a);if(wb)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(zb)return/WebKit\/(\S+)/.exec(a);if(vb)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
Db&&(Cb=Db?Db[1]:"");if(wb){var Eb=Ab();if(null!=Eb&&Eb>parseFloat(Cb)){Bb=String(Eb);break a}}Bb=Cb}var Fb=Bb,Gb;if(B.document&&wb){var Hb=Ab();Gb=Hb?Hb:parseInt(Fb,10)||void 0}else Gb=void 0;var Ib=Gb;var Jb=tb()||J("iPod"),Kb=J("iPad"),Lb=J("Safari")&&!((J("Chrome")||J("CriOS"))&&!J("Edge")||J("Coast")||J("Opera")||J("Edge")||J("Edg/")||J("OPR")||J("Firefox")||J("FxiOS")||J("Silk")||J("Android"))&&!(tb()||J("iPad")||J("iPod"));var Mb={},Nb=null;var L=window;function Ob(a,b){this.width=a;this.height=b}
p=Ob.prototype;p.clone=function(){return new Ob(this.width,this.height)};
p.aspectRatio=function(){return this.width/this.height};
p.isEmpty=function(){return!(this.width*this.height)};
p.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
p.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
p.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};function Pb(){var a=document;var b="IFRAME";"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function Qb(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Rb(a){var b=Sb;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a.call(void 0,b[c],c,b)}
function Tb(){var a=[];Rb(function(b){a.push(b)});
return a}
var Sb={wa:"allow-forms",xa:"allow-modals",ya:"allow-orientation-lock",za:"allow-pointer-lock",Aa:"allow-popups",Ba:"allow-popups-to-escape-sandbox",Ca:"allow-presentation",Da:"allow-same-origin",Ea:"allow-scripts",Fa:"allow-top-navigation",Ga:"allow-top-navigation-by-user-activation"},Ub=Ka(function(){return Tb()});
function Vb(){var a=Pb(),b={};H(Ub(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
;var Wb=(new Date).getTime();function Xb(a){if(!a)return"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==
c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function Yb(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;m=l=0}
function b(n){for(var r=g,q=0;64>q;q+=4)r[q/4]=n[q]<<24|n[q+1]<<16|n[q+2]<<8|n[q+3];for(q=16;80>q;q++)n=r[q-3]^r[q-8]^r[q-14]^r[q-16],r[q]=(n<<1|n>>>31)&4294967295;n=e[0];var x=e[1],v=e[2],w=e[3],O=e[4];for(q=0;80>q;q++){if(40>q)if(20>q){var F=w^x&(v^w);var P=1518500249}else F=x^v^w,P=1859775393;else 60>q?(F=x&v|w&(x|v),P=2400959708):(F=x^v^w,P=3395469782);F=((n<<5|n>>>27)&4294967295)+F+O+P+r[q]&4294967295;O=w;w=v;v=(x<<30|x>>>2)&4294967295;x=n;n=F}e[0]=e[0]+n&4294967295;e[1]=e[1]+x&4294967295;e[2]=
e[2]+v&4294967295;e[3]=e[3]+w&4294967295;e[4]=e[4]+O&4294967295}
function c(n,r){if("string"===typeof n){n=unescape(encodeURIComponent(n));for(var q=[],x=0,v=n.length;x<v;++x)q.push(n.charCodeAt(x));n=q}r||(r=n.length);q=0;if(0==l)for(;q+64<r;)b(n.slice(q,q+64)),q+=64,m+=64;for(;q<r;)if(f[l++]=n[q++],m++,64==l)for(l=0,b(f);q+64<r;)b(n.slice(q,q+64)),q+=64,m+=64}
function d(){var n=[],r=8*m;56>l?c(h,56-l):c(h,64-(l-56));for(var q=63;56<=q;q--)f[q]=r&255,r>>>=8;b(f);for(q=r=0;5>q;q++)for(var x=24;0<=x;x-=8)n[r++]=e[q]>>x&255;return n}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,m;a();return{reset:a,update:c,digest:d,ja:function(){for(var n=d(),r="",q=0;q<n.length;q++)r+="0123456789ABCDEF".charAt(Math.floor(n[q]/16))+"0123456789ABCDEF".charAt(n[q]%16);return r}}}
;function Zb(a,b,c){var d=String(B.location.href);return d&&a&&b?[b,$b(Xb(d),a,c||null)].join(" "):null}
function $b(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],H(d,function(h){e.push(h)}),ac(e.join(" "));
var f=[],g=[];H(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];H(d,function(h){e.push(h)});
a=ac(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function ac(a){var b=Yb();b.update(a);return b.ja().toLowerCase()}
;var bc={};function cc(a){this.h=a||{cookie:""}}
p=cc.prototype;p.isEnabled=function(){if(!B.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{S:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
p.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Qa;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.S}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);this.h.cookie=a+"="+b+(f?";domain="+f:"")+(g?";path="+g:"")+(0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString())+(d?";secure":"")+(null!=e?";samesite="+e:"")};
p.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=$a(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
p.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{S:0,path:b,domain:c});return d};
p.isEmpty=function(){return!this.h.cookie};
p.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=$a(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var dc=new cc("undefined"==typeof document?null:document);function ec(a){return!!bc.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function fc(a,b,c,d){(a=B[a])||(a=(new cc(document)).get(b));return a?Zb(a,c,d):null}
function gc(a){var b=void 0===b?!1:b;var c=Xb(String(B.location.href)),d=[];var e=b;e=void 0===e?!1:e;var f=B.__SAPISID||B.__APISID||B.__3PSAPISID||B.__OVERRIDE_SID;ec(e)&&(f=f||B.__1PSAPISID);if(f)e=!0;else{var g=new cc(document);f=g.get("SAPISID")||g.get("APISID")||g.get("__Secure-3PAPISID")||g.get("SID");ec(e)&&(f=f||g.get("__Secure-1PAPISID"));e=!!f}e&&(e=(c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:"))?B.__SAPISID:B.__APISID,e||(e=new cc(document),
e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID")),(e=e?Zb(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e),c&&ec(b)&&((b=fc("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=fc("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a)));return 0==d.length?null:d.join(" ")}
;function hc(){this.h=[];this.i=-1}
hc.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.h[a]!=b&&(this.h[a]=b,this.i=-1)};
hc.prototype.get=function(a){return!!this.h[a]};
function ic(a){-1==a.i&&(a.i=Ma(a.h,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.i}
;function jc(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
jc.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function kc(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;var lc;function mc(){var a=B.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!J("Presto")&&(a=function(){var e=Pb();e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Ga(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!J("Trident")&&!J("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.V;c.V=null;e()}};
return function(e){d.next={V:e};d=d.next;b.port2.postMessage(0)}}return function(e){B.setTimeout(e,0)}}
;function nc(a){B.setTimeout(function(){throw a;},0)}
;function oc(){this.i=this.h=null}
oc.prototype.add=function(a,b){var c=pc.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
oc.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var pc=new jc(function(){return new qc},function(a){return a.reset()});
function qc(){this.next=this.scope=this.h=null}
qc.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
qc.prototype.reset=function(){this.next=this.scope=this.h=null};function rc(a,b){sc||tc();uc||(sc(),uc=!0);vc.add(a,b)}
var sc;function tc(){if(B.Promise&&B.Promise.resolve){var a=B.Promise.resolve(void 0);sc=function(){a.then(wc)}}else sc=function(){var b=wc;
"function"!==typeof B.setImmediate||B.Window&&B.Window.prototype&&!J("Edge")&&B.Window.prototype.setImmediate==B.setImmediate?(lc||(lc=mc()),lc(b)):B.setImmediate(b)}}
var uc=!1,vc=new oc;function wc(){for(var a;a=vc.remove();){try{a.h.call(a.scope)}catch(b){nc(b)}kc(pc,a)}uc=!1}
;function xc(){this.i=-1}
;function yc(){this.i=64;this.h=[];this.o=[];this.s=[];this.l=[];this.l[0]=128;for(var a=1;a<this.i;++a)this.l[a]=0;this.m=this.j=0;this.reset()}
G(yc,xc);yc.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.m=this.j=0};
function zc(a,b,c){c||(c=0);var d=a.s;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
yc.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.i,d=0,e=this.o,f=this.j;d<b;){if(0==f)for(;d<=c;)zc(this,a,d),d+=this.i;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.i){zc(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.i){zc(this,e);f=0;break}}this.j=f;this.m+=b}};
yc.prototype.digest=function(){var a=[],b=8*this.m;56>this.j?this.update(this.l,56-this.j):this.update(this.l,this.i-(this.j-56));for(var c=this.i-1;56<=c;c--)this.o[c]=b&255,b/=256;zc(this,this.o);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};function Ac(a){var b=C("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||B.$googDebugFname||b}catch(g){e="Not available",c=!0}b=Bc(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,Cc[c])c=Cc[c];else{c=String(c);if(!Cc[c]){var f=/function\s+([^\(]+)/m.exec(c);Cc[c]=f?f[1]:"[Anonymous]"}c=Cc[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function Bc(a,b){b||(b={});b[Dc(a)]=!0;var c=a.stack||"";(a=a.La)&&!b[Dc(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=Bc(a,b));return c}
function Dc(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var Cc={};function Ec(){this.j=this.j;this.m=this.m}
Ec.prototype.j=!1;Ec.prototype.dispose=function(){this.j||(this.j=!0,this.K())};
Ec.prototype.K=function(){if(this.m)for(;this.m.length;)this.m.shift()()};var Fc="StopIteration"in B?B.StopIteration:{message:"StopIteration",stack:""};function Gc(){}
Gc.prototype.next=function(){throw Fc;};
Gc.prototype.D=function(){return this};
function Hc(a){if(a instanceof Gc)return a;if("function"==typeof a.D)return a.D(!1);if(Aa(a)){var b=0,c=new Gc;c.next=function(){for(;;){if(b>=a.length)throw Fc;if(b in a)return a[b++];b++}};
return c}throw Error("Not implemented");}
function Ic(a,b){if(Aa(a))try{H(a,b,void 0)}catch(c){if(c!==Fc)throw c;}else{a=Hc(a);try{for(;;)b.call(void 0,a.next(),void 0,a)}catch(c){if(c!==Fc)throw c;}}}
function Jc(a){if(Aa(a))return Qa(a);a=Hc(a);var b=[];Ic(a,function(c){b.push(c)});
return b}
;function Kc(a,b){this.i={};this.h=[];this.l=this.j=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof Kc)for(c=Lc(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function Lc(a){Mc(a);return a.h.concat()}
p=Kc.prototype;p.equals=function(a,b){if(this===a)return!0;if(this.j!=a.j)return!1;b=b||Nc;Mc(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function Nc(a,b){return a===b}
p.isEmpty=function(){return 0==this.j};
p.clear=function(){this.i={};this.l=this.j=this.h.length=0};
p.remove=function(a){return Object.prototype.hasOwnProperty.call(this.i,a)?(delete this.i[a],this.j--,this.l++,this.h.length>2*this.j&&Mc(this),!0):!1};
function Mc(a){if(a.j!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];Object.prototype.hasOwnProperty.call(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.j!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],Object.prototype.hasOwnProperty.call(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
p.get=function(a,b){return Object.prototype.hasOwnProperty.call(this.i,a)?this.i[a]:b};
p.set=function(a,b){Object.prototype.hasOwnProperty.call(this.i,a)||(this.j++,this.h.push(a),this.l++);this.i[a]=b};
p.forEach=function(a,b){for(var c=Lc(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
p.clone=function(){return new Kc(this)};
p.D=function(a){Mc(this);var b=0,c=this.l,d=this,e=new Gc;e.next=function(){if(c!=d.l)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)throw Fc;var f=d.h[b++];return a?f:d.i[f]};
return e};var Oc=function(){if(!B.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{B.addEventListener("test",za,b),B.removeEventListener("test",za,b)}catch(c){}return a}();function Pc(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
Pc.prototype.stopPropagation=function(){this.j=!0};
Pc.prototype.preventDefault=function(){this.defaultPrevented=!0};function Qc(a,b){Pc.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
G(Qc,Pc);var Rc={2:"touch",3:"pen",4:"mouse"};
Qc.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(yb){a:{try{ub(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:Rc[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&Qc.A.preventDefault.call(this)};
Qc.prototype.stopPropagation=function(){Qc.A.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
Qc.prototype.preventDefault=function(){Qc.A.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var Sc="closure_listenable_"+(1E6*Math.random()|0);var Tc=0;function Uc(a,b,c,d,e){this.listener=a;this.h=null;this.src=b;this.type=c;this.capture=!!d;this.P=e;this.key=++Tc;this.L=this.N=!1}
function Vc(a){a.L=!0;a.listener=null;a.h=null;a.src=null;a.P=null}
;function Wc(a){this.src=a;this.listeners={};this.h=0}
Wc.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=Xc(a,b,d,e);-1<g?(b=a[g],c||(b.N=!1)):(b=new Uc(b,this.src,f,!!d,e),b.N=c,a.push(b));return b};
Wc.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=Xc(e,b,c,d);return-1<b?(Vc(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function Yc(a,b){var c=b.type;c in a.listeners&&Oa(a.listeners[c],b)&&(Vc(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function Xc(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.L&&f.listener==b&&f.capture==!!c&&f.P==d)return e}return-1}
;var Zc="closure_lm_"+(1E6*Math.random()|0),$c={},ad=0;function bd(a,b,c,d,e){if(d&&d.once)cd(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)bd(a,b[f],c,d,e);else c=dd(c),a&&a[Sc]?ed(a,b,c,D(d)?!!d.capture:!!d,e):fd(a,b,c,!1,d,e)}
function fd(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=D(e)?!!e.capture:!!e,h=gd(a);h||(a[Zc]=h=new Wc(a));c=h.add(b,c,d,g,f);if(!c.h){d=hd();c.h=d;d.src=a;d.listener=c;if(a.addEventListener)Oc||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(id(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");ad++}}
function hd(){function a(c){return b.call(a.src,a.listener,c)}
var b=jd;return a}
function cd(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)cd(a,b[f],c,d,e);else c=dd(c),a&&a[Sc]?a.h.add(String(b),c,!0,D(d)?!!d.capture:!!d,e):fd(a,b,c,!0,d,e)}
function kd(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)kd(a,b[f],c,d,e);else(d=D(d)?!!d.capture:!!d,c=dd(c),a&&a[Sc])?a.h.remove(String(b),c,d,e):a&&(a=gd(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=Xc(b,c,d,e)),(c=-1<a?b[a]:null)&&ld(c))}
function ld(a){if("number"!==typeof a&&a&&!a.L){var b=a.src;if(b&&b[Sc])Yc(b.h,a);else{var c=a.type,d=a.h;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(id(c),d):b.addListener&&b.removeListener&&b.removeListener(d);ad--;(c=gd(b))?(Yc(c,a),0==c.h&&(c.src=null,b[Zc]=null)):Vc(a)}}}
function id(a){return a in $c?$c[a]:$c[a]="on"+a}
function jd(a,b){if(a.L)a=!0;else{b=new Qc(b,this);var c=a.listener,d=a.P||a.src;a.N&&ld(a);a=c.call(d,b)}return a}
function gd(a){a=a[Zc];return a instanceof Wc?a:null}
var md="__closure_events_fn_"+(1E9*Math.random()>>>0);function dd(a){if("function"===typeof a)return a;a[md]||(a[md]=function(b){return a.handleEvent(b)});
return a[md]}
;function M(){Ec.call(this);this.h=new Wc(this);this.J=this;this.o=null}
G(M,Ec);M.prototype[Sc]=!0;M.prototype.addEventListener=function(a,b,c,d){bd(this,a,b,c,d)};
M.prototype.removeEventListener=function(a,b,c,d){kd(this,a,b,c,d)};
function nd(a,b){var c=a.o;if(c){var d=[];for(var e=1;c;c=c.o)d.push(c),++e}a=a.J;c=b.type||b;"string"===typeof b?b=new Pc(b,a):b instanceof Pc?b.target=b.target||a:(e=b,b=new Pc(c,a),Ya(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=od(g,c,!0,b)&&e}b.j||(g=b.h=a,e=od(g,c,!0,b)&&e,b.j||(e=od(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=od(g,c,!1,b)&&e}
M.prototype.K=function(){M.A.K.call(this);if(this.h){var a=this.h,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,Vc(d[e]);delete a.listeners[c];a.h--}}this.o=null};
function ed(a,b,c,d,e){a.h.add(String(b),c,!1,d,e)}
function od(a,b,c,d){b=a.h.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.L&&g.capture==c){var h=g.listener,k=g.P||g.src;g.N&&Yc(a.h,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;var pd=B.JSON.stringify;function N(a){this.h=0;this.s=void 0;this.l=this.i=this.j=null;this.m=this.o=!1;if(a!=za)try{var b=this;a.call(void 0,function(c){qd(b,2,c)},function(c){qd(b,3,c)})}catch(c){qd(this,3,c)}}
function rd(){this.next=this.context=this.onRejected=this.i=this.h=null;this.j=!1}
rd.prototype.reset=function(){this.context=this.onRejected=this.i=this.h=null;this.j=!1};
var sd=new jc(function(){return new rd},function(a){a.reset()});
function td(a,b,c){var d=sd.get();d.i=a;d.onRejected=b;d.context=c;return d}
N.prototype.then=function(a,b,c){return ud(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
N.prototype.$goog_Thenable=!0;N.prototype.cancel=function(a){if(0==this.h){var b=new vd(a);rc(function(){wd(this,b)},this)}};
function wd(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?wd(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):xd(c),yd(c,e,3,b)))}a.j=null}else qd(a,3,b)}
function zd(a,b){a.i||2!=a.h&&3!=a.h||Ad(a);a.l?a.l.next=b:a.i=b;a.l=b}
function ud(a,b,c,d){var e=td(null,null,null);e.h=new N(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof vd?g(h):f(k)}catch(l){g(l)}}:g});
e.h.j=a;zd(a,e);return e.h}
N.prototype.C=function(a){this.h=0;qd(this,2,a)};
N.prototype.J=function(a){this.h=0;qd(this,3,a)};
function qd(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.C,f=a.J;if(d instanceof N){zd(d,td(e||za,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(D(d))try{var k=d.then;if("function"===typeof k){Bd(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.s=c,a.h=b,a.j=null,Ad(a),3!=b||c instanceof vd||Cd(a,c))}}
function Bd(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Ad(a){a.o||(a.o=!0,rc(a.u,a))}
function xd(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
N.prototype.u=function(){for(var a;a=xd(this);)yd(this,a,this.h,this.s);this.o=!1};
function yd(a,b,c,d){if(3==c&&b.onRejected&&!b.j)for(;a&&a.m;a=a.j)a.m=!1;if(b.h)b.h.j=null,Dd(b,c,d);else try{b.j?b.i.call(b.context):Dd(b,c,d)}catch(e){Ed.call(null,e)}kc(sd,b)}
function Dd(a,b,c){2==b?a.i.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Cd(a,b){a.m=!0;rc(function(){a.m&&Ed.call(null,b)})}
var Ed=nc;function vd(a){Ia.call(this,a)}
G(vd,Ia);vd.prototype.name="cancel";function Q(a){Ec.call(this);this.s=1;this.l=[];this.o=0;this.h=[];this.i={};this.u=!!a}
G(Q,Ec);p=Q.prototype;p.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.s;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.s=e+3;d.push(e);return e};
function Fd(a,b,c){var d=Gd;if(a=d.i[a]){var e=d.h;(a=Na(a,function(f){return e[f+1]==b&&e[f+2]==c}))&&d.M(a)}}
p.M=function(a){var b=this.h[a];if(b){var c=this.i[b];0!=this.o?(this.l.push(a),this.h[a+1]=za):(c&&Oa(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
p.I=function(a,b){var c=this.i[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.u)for(e=0;e<c.length;e++){var g=c[e];Hd(this.h[g+1],this.h[g+2],d)}else{this.o++;try{for(e=0,f=c.length;e<f;e++)g=c[e],this.h[g+1].apply(this.h[g+2],d)}finally{if(this.o--,0<this.l.length&&0==this.o)for(;c=this.l.pop();)this.M(c)}}return 0!=e}return!1};
function Hd(a,b,c){rc(function(){a.apply(b,c)})}
p.clear=function(a){if(a){var b=this.i[a];b&&(H(b,this.M,this),delete this.i[a])}else this.h.length=0,this.i={}};
p.K=function(){Q.A.K.call(this);this.clear();this.l.length=0};function Id(a){this.h=a}
Id.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,pd(b))};
Id.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Id.prototype.remove=function(a){this.h.remove(a)};function Jd(a){this.h=a}
G(Jd,Id);function Kd(a){this.data=a}
function Ld(a){return void 0===a||a instanceof Kd?a:new Kd(a)}
Jd.prototype.set=function(a,b){Jd.A.set.call(this,a,Ld(b))};
Jd.prototype.i=function(a){a=Jd.A.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Jd.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function Md(a){this.h=a}
G(Md,Jd);Md.prototype.set=function(a,b,c){if(b=Ld(b)){if(c){if(c<Date.now()){Md.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}Md.A.set.call(this,a,b)};
Md.prototype.i=function(a){var b=Md.A.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())Md.prototype.remove.call(this,a);else return b}};function Nd(){}
;function Od(){}
G(Od,Nd);Od.prototype.clear=function(){var a=Jc(this.D(!0)),b=this;H(a,function(c){b.remove(c)})};function Pd(a){this.h=a}
G(Pd,Od);p=Pd.prototype;p.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
p.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
p.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
p.remove=function(a){this.h.removeItem(a)};
p.D=function(a){var b=0,c=this.h,d=new Gc;d.next=function(){if(b>=c.length)throw Fc;var e=c.key(b++);if(a)return e;e=c.getItem(e);if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
p.clear=function(){this.h.clear()};
p.key=function(a){return this.h.key(a)};function Qd(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
G(Qd,Pd);function Rd(a,b){this.i=a;this.h=null;if(wb&&!(9<=Number(Ib))){Sd||(Sd=new Kc);this.h=Sd.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),Sd.set(a,this.h));try{this.h.load(this.i)}catch(c){this.h=null}}}
G(Rd,Od);var Td={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},Sd=null;function Ud(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return Td[b]})}
p=Rd.prototype;p.isAvailable=function(){return!!this.h};
p.set=function(a,b){this.h.setAttribute(Ud(a),b);Vd(this)};
p.get=function(a){a=this.h.getAttribute(Ud(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
p.remove=function(a){this.h.removeAttribute(Ud(a));Vd(this)};
p.D=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new Gc;d.next=function(){if(b>=c.length)throw Fc;var e=c[b++];if(a)return decodeURIComponent(e.nodeName.replace(/\./g,"%")).substr(1);e=e.nodeValue;if("string"!==typeof e)throw"Storage mechanism: Invalid value was encountered";return e};
return d};
p.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);Vd(this)};
function Vd(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function Wd(a,b){this.i=a;this.h=b+"::"}
G(Wd,Od);Wd.prototype.set=function(a,b){this.i.set(this.h+a,b)};
Wd.prototype.get=function(a){return this.i.get(this.h+a)};
Wd.prototype.remove=function(a){this.i.remove(this.h+a)};
Wd.prototype.D=function(a){var b=this.i.D(!0),c=this,d=new Gc;d.next=function(){for(var e=b.next();e.substr(0,c.h.length)!=c.h;)e=b.next();return a?e.substr(c.h.length):c.i.get(e)};
return d};var Xd=window.yt&&window.yt.config_||window.ytcfg&&window.ytcfg.data_||{};E("yt.config_",Xd);function Yd(a){var b=arguments;1<b.length?Xd[b[0]]=b[1]:1===b.length&&Object.assign(Xd,b[0])}
function R(a,b){return a in Xd?Xd[a]:b}
;var Zd=[];function $d(a){Zd.forEach(function(b){return b(a)})}
function ae(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){be(b),$d(b)}}:a}
function be(a){var b=C("yt.logging.errors.log");b?b(a,"ERROR",void 0,void 0,void 0):(b=R("ERRORS",[]),b.push([a,"ERROR",void 0,void 0,void 0]),Yd("ERRORS",b))}
function ce(a){var b=C("yt.logging.errors.log");b?b(a,"WARNING",void 0,void 0,void 0):(b=R("ERRORS",[]),b.push([a,"WARNING",void 0,void 0,void 0]),Yd("ERRORS",b))}
;function de(a,b){"function"===typeof a&&(a=ae(a));return window.setTimeout(a,b)}
function ee(a){"function"===typeof a&&(a=ae(a));return window.setInterval(a,250)}
;var fe=0;E("ytDomDomGetNextId",C("ytDomDomGetNextId")||function(){return++fe});var ge={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function he(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.clientY=this.clientX=0;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in ge||(this[b]=a[b]);var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==
this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey}}catch(e){}}
he.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
he.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
he.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var Ua=B.ytEventsEventsListeners||{};E("ytEventsEventsListeners",Ua);var ie=B.ytEventsEventsCounter||{count:0};E("ytEventsEventsCounter",ie);
function je(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return Ta(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=D(e[4])&&D(d)&&Va(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function ke(a){a&&("string"==typeof a&&(a=[a]),H(a,function(b){if(b in Ua){var c=Ua[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?le()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete Ua[b]}}))}
var le=Ka(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function me(a,b,c){var d=void 0===d?{}:d;if(a&&(a.addEventListener||a.attachEvent)){var e=je(a,b,c,d);if(!e){e=++ie.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new he(h);if(!Qb(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new he(h);
h.currentTarget=a;return c.call(a,h)};
g=ae(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),le()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);Ua[e]=[a,b,c,g,d]}}}
;var ne=/^[\w.]*$/,oe={q:!0,search_query:!0};function pe(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=qe(f[0]||""),h=qe(f[1]||"");g in c?Array.isArray(c[g])?Ra(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(n){var k=n,l=f[0],m=String(pe);k.args=[{key:l,value:f[1],query:a,method:re==m?"unchanged":m}];oe.hasOwnProperty(l)||ce(k)}}return c}
var re=String(pe);function se(a){var b=[];Sa(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];H(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function te(a){"?"==a.charAt(0)&&(a=a.substr(1));return pe(a,"&")}
function ue(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=te(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);b=a;a=qb(e);a?(c=b.indexOf("#"),0>c&&(c=b.length),f=b.indexOf("?"),0>f||f>c?(f=c,e=""):e=b.substring(f+1,c),b=[b.substr(0,f),e,b.substr(c)],c=b[1],b[1]=a?c?c+"&"+a:a:c,a=b[0]+(b[1]?"?"+b[1]:"")+b[2]):a=b;return a+d}
function ve(a){if(!b)var b=window.location.href;var c=a.match(lb)[1]||null,d=nb(a);c&&d?(a=a.match(lb),b=b.match(lb),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?nb(b)==d&&(Number(b.match(lb)[4]||null)||null)==(Number(a.match(lb)[4]||null)||null):!0;return a}
function qe(a){return a&&a.match(ne)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function S(a){a=we(a);return"string"===typeof a&&"false"===a?!1:!!a}
function xe(a,b){a=we(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function we(a){var b=R("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:R("EXPERIMENT_FLAGS",{})[a]}
;function ye(){}
function ze(a,b){return Ae(a,1,b)}
;function Be(){ye.apply(this,arguments)}
ma(Be,ye);function Ae(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=C("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):de(a,c||0)}
function Ce(a){if(void 0===a||!Number.isNaN(Number(a))){var b=C("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}}
Be.prototype.start=function(){var a=C("yt.scheduler.instance.start");a&&a()};
Be.h=void 0;Be.i=function(){Be.h||(Be.h=new Be)};
Be.i();function De(a){var b=Ee;a=void 0===a?C("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Wb;e.flash="0";a:{try{var f=b.h.top.location.href}catch(O){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?L:g;try{var h=g.history.length}catch(O){h=0}e.u_his=h;e.u_java=!!L.navigator&&"unknown"!==typeof L.navigator.javaEnabled&&!!L.navigator.javaEnabled&&L.navigator.javaEnabled();L.screen&&(e.u_h=L.screen.height,e.u_w=L.screen.width,
e.u_ah=L.screen.availHeight,e.u_aw=L.screen.availWidth,e.u_cd=L.screen.colorDepth);L.navigator&&L.navigator.plugins&&(e.u_nplug=L.navigator.plugins.length);L.navigator&&L.navigator.mimeTypes&&(e.u_nmime=L.navigator.mimeTypes.length);h=b.h;try{var k=h.screenX;var l=h.screenY}catch(O){}try{var m=h.outerWidth;var n=h.outerHeight}catch(O){}try{var r=h.innerWidth;var q=h.innerHeight}catch(O){}k=[h.screenLeft,h.screenTop,k,l,h.screen?h.screen.availWidth:void 0,h.screen?h.screen.availTop:void 0,m,n,r,q];
l=b.h.top;try{var x=(l||window).document,v="CSS1Compat"==x.compatMode?x.documentElement:x.body;var w=(new Ob(v.clientWidth,v.clientHeight)).round()}catch(O){w=new Ob(-12245933,-12245933)}x=w;w={};v=new hc;B.SVGElement&&B.document.createElementNS&&v.set(0);l=Vb();l["allow-top-navigation-by-user-activation"]&&v.set(1);l["allow-popups-to-escape-sandbox"]&&v.set(2);B.crypto&&B.crypto.subtle&&v.set(3);B.TextDecoder&&B.TextEncoder&&v.set(4);v=ic(v);w.bc=v;w.bih=x.height;w.biw=x.width;w.brdim=k.join();b=
b.i;b=(w.vis={visible:1,hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,w.wgl=!!L.WebGLRenderingContext,w);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var Ee=new function(){var a=window.document;this.h=window;this.i=a};
E("yt.ads_.signals_.getAdSignalsString",function(a){return se(De(a))});var Fe="XMLHttpRequest"in B?function(){return new XMLHttpRequest}:null;
function Ge(){if(!Fe)return null;var a=Fe();return"open"in a?a:null}
;var He={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL","X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},
Ie="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address client_dev_root_url".split(" "),Je=!1;
function Ke(a,b){b=void 0===b?{}:b;var c=ve(a),d=S("web_ajax_ignore_global_headers_if_set"),e;for(e in He){var f=R(He[e]);!f||!c&&nb(a)||d&&void 0!==b[e]||(b[e]=f)}if(c||!nb(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!nb(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||!nb(a))b["X-YouTube-Ad-Signals"]=se(De(void 0));return b}
function Le(a){var b=window.location.search,c=nb(a);S("debug_handle_relative_url_for_query_forward_killswitch")||c||!ve(a)||(c=document.location.hostname);var d=mb(a.match(lb)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=te(b),f={};H(Ie,function(g){e[g]&&(f[g]=e[g])});
return ue(a,f||{},!1)}
function Me(a,b){var c=b.format||"JSON";a=Ne(a,b);var d=Oe(a,b),e=!1,f=Pe(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);a:switch(k&&"status"in k?k.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:var l=!0;break a;default:l=!1}var m=null,n=400<=k.status&&500>k.status,r=500<=k.status&&600>k.status;if(l||n||r)m=Qe(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(m&&m.return_code,10);break a;case "RAW":l=!0;break a}l=
!!m}m=m||{};n=b.context||B;l?b.onSuccess&&b.onSuccess.call(n,k,m):b.onError&&b.onError.call(n,k,m);b.onFinish&&b.onFinish.call(n,k,m)}},b.method,d,b.headers,b.responseType,b.withCredentials);
if(b.onTimeout&&0<b.timeout){var g=b.onTimeout;var h=de(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||B,f))},b.timeout)}}
function Ne(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=R("XSRF_FIELD_NAME",void 0);if(b=b.urlParams)b[c]&&delete b[c],a=ue(a,b||{},!0);return a}
function Oe(a,b){var c=R("XSRF_FIELD_NAME",void 0),d=R("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.postParams,g=R("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||nb(a)&&!b.withCredentials&&nb(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=te(e),Ya(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):qb(e));if(!(a=e)&&(a=f)){a:{for(var k in f){f=
!1;break a}f=!0}a=!f}!Je&&a&&"POST"!=b.method&&(Je=!0,be(Error("AJAX request with postData should use POST")));return e}
function Qe(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,ce(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Re(a):null)e={},H(a.getElementsByTagName("*"),function(g){e[g.tagName]=Se(g)})}d&&Te(e);
return e}
function Te(a){if(D(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;var d=a[b];if(void 0===Za){var e=null;var f=B.trustedTypes;if(f&&f.createPolicy){try{e=f.createPolicy("goog#html",{createHTML:Ha,createScript:Ha,createScriptURL:Ha})}catch(g){B.console&&B.console.error(g.message)}Za=e}else Za=e}d=(e=Za)?e.createHTML(d):d;a[c]=new jb(d)}else Te(a[b])}}
function Re(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Se(a){var b="";H(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Pe(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&ae(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=Ge();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;S("debug_forward_web_query_parameters")&&(a=Le(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=Ke(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var Ue=Jb||Kb;var Ve={},We=0;function Xe(){var a=void 0===a?"":a;if(!Ye(a))if(a=void 0===a?"":a)Pe("/generate_204",void 0,"POST",a,void 0);else if(R("USE_NET_AJAX_FOR_PING_TRANSPORT",!1))Pe("/generate_204",void 0,"GET","",void 0);else{a:{try{var b=new Ja;if(b.j&&b.i||b.l){var c=mb("/generate_204".match(lb)[5]||null);var d=!(!c||!c.endsWith("/aclk")||"1"!==sb("/generate_204","ri"));break a}}catch(e){}d=!1}d&&Ye()||Ze()}}
function Ye(a){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon("/generate_204",void 0===a?"":a))return!0}catch(b){}return!1}
function Ze(){var a=new Image,b=""+We++;Ve[b]=a;a.onload=a.onerror=function(){delete Ve[b]};
a.src="/generate_204"}
;var $e=B.ytPubsubPubsubInstance||new Q,af=B.ytPubsubPubsubSubscribedKeys||{},bf=B.ytPubsubPubsubTopicToKeys||{},cf=B.ytPubsubPubsubIsSynchronous||{};Q.prototype.subscribe=Q.prototype.subscribe;Q.prototype.unsubscribeByKey=Q.prototype.M;Q.prototype.publish=Q.prototype.I;Q.prototype.clear=Q.prototype.clear;E("ytPubsubPubsubInstance",$e);E("ytPubsubPubsubTopicToKeys",bf);E("ytPubsubPubsubIsSynchronous",cf);E("ytPubsubPubsubSubscribedKeys",af);var df=window,T=df.ytcsi&&df.ytcsi.now?df.ytcsi.now:df.performance&&df.performance.timing&&df.performance.now&&df.performance.timing.navigationStart?function(){return df.performance.timing.navigationStart+df.performance.now()}:function(){return(new Date).getTime()};var ef=xe("initial_gel_batch_timeout",1E3),ff=Math.pow(2,16)-1,gf=null,hf=0,jf=void 0,kf=0,lf=0,mf=0,nf=!0,of=B.ytLoggingTransportGELQueue_||new Map;E("ytLoggingTransportGELQueue_",of);var pf=B.ytLoggingTransportTokensToCttTargetIds_||{};E("ytLoggingTransportTokensToCttTargetIds_",pf);
function qf(a,b){if("log_event"===a.endpoint){var c="";a.B&&(pf[a.B.token]=rf(a.B),c=a.B.token);var d=of.get(c)||[];of.set(c,d);d.push(a.payload);b&&(jf=new b);a=xe("web_logging_max_batch")||100;b=T();d.length>=a?sf({writeThenSend:!0}):10<=b-mf&&(tf(),mf=b)}}
function uf(a,b){if("log_event"===a.endpoint){var c="";a.B&&(pf[a.B.token]=rf(a.B),c=a.B.token);var d=new Map;d.set(c,[a.payload]);b&&(jf=new b);return new N(function(e){jf&&jf.isReady()?vf(d,e,{bypassNetworkless:!0}):e()})}}
function sf(a){a=void 0===a?{}:a;return new N(function(b){window.clearTimeout(kf);window.clearTimeout(lf);lf=0;jf&&jf.isReady()?(vf(of,b,a),of.clear()):(tf(),b())})}
function tf(){S("web_gel_timeout_cap")&&!lf&&(lf=de(sf,6E4));window.clearTimeout(kf);var a=R("LOGGING_BATCH_TIMEOUT",xe("web_gel_debounce_ms",1E4));S("shorten_initial_gel_batch_timeout")&&nf&&(a=ef);kf=de(function(){sf({writeThenSend:!0})},a)}
function vf(a,b,c){var d=jf;c=void 0===c?{}:c;var e=Math.round(T()),f=a.size;a=u(a);for(var g=a.next();!g.done;g=a.next()){var h=u(g.value);g=h.next().value;var k=h.next().value;h=Wa({context:wf(d.h||xf())});h.events=k;(k=pf[g])&&yf(h,g,k);delete pf[g];zf(h,e);S("send_beacon_before_gel")&&window.navigator&&window.navigator.sendBeacon&&!c.writeThenSend&&Xe();Af(d,"log_event",h,{retry:!0,onSuccess:function(){f--;f||b();hf=Math.round(T()-e)},
onError:function(){f--;f||b()},
aa:c});nf=!1}}
function zf(a,b){a.requestTimeMs=String(b);S("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);if(b=R("EVENT_ID",void 0)){var c=R("BATCH_CLIENT_COUNTER",void 0)||0;c||(c=Math.floor(Math.random()*ff/2));c++;c>ff&&(c=1);Yd("BATCH_CLIENT_COUNTER",c);b={serializedEventId:b,clientCounter:String(c)};a.serializedClientEventId=b;gf&&hf&&S("log_gel_rtt_web")&&(a.previousBatchInfo={serializedClientEventId:gf,roundtripMs:String(hf)});gf=b;hf=0}}
function yf(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function rf(a){var b={};a.videoId?b.videoId=a.videoId:a.playlistId&&(b.playlistId=a.playlistId);return b}
;var Bf=B.ytLoggingGelSequenceIdObj_||{};E("ytLoggingGelSequenceIdObj_",Bf);function Cf(){if(!B.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return B.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":B.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":B.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":B.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
;E("ytglobal.prefsUserPrefsPrefs_",C("ytglobal.prefsUserPrefsPrefs_")||{});var Df={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Ef={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};
function Ff(){var a=B.navigator;return a?a.connection:void 0}
;function Gf(){return"INNERTUBE_API_KEY"in Xd&&"INNERTUBE_API_VERSION"in Xd}
function xf(){return{innertubeApiKey:R("INNERTUBE_API_KEY",void 0),innertubeApiVersion:R("INNERTUBE_API_VERSION",void 0),ka:R("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),la:R("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),innertubeContextClientVersion:R("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),na:R("INNERTUBE_CONTEXT_HL",void 0),ma:R("INNERTUBE_CONTEXT_GL",void 0),oa:R("INNERTUBE_HOST_OVERRIDE",void 0)||"",qa:!!R("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),pa:!!R("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:R("SERIALIZED_CLIENT_CONFIG_DATA",void 0)}}
function wf(a){var b={client:{hl:a.na,gl:a.ma,clientName:a.la,clientVersion:a.innertubeContextClientVersion,configInfo:a.ka}},c=B.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=R("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=[];var d=R("EXPERIMENTS_FORCED_FLAGS",{});for(e in d)c.push({key:e,value:String(d[e])});var e=R("EXPERIMENT_FLAGS",{});for(var f in e)f.startsWith("force_")&&void 0===d[f]&&c.push({key:f,value:String(e[f])});0<c.length&&(b.request={internalExperimentFlags:c});
f=b.client.clientName;if("WEB"===f||"MWEB"===f||1===f||2===f){if(!S("web_include_display_mode_killswitch")){var g;b.client.mainAppWebInfo=null!=(g=b.client.mainAppWebInfo)?g:{};b.client.mainAppWebInfo.webDisplayMode=Cf()}}else if(g=b.client.clientName,("WEB_REMIX"===g||76===g)&&!S("music_web_display_mode_killswitch")){var h;b.client.Z=null!=(h=b.client.Z)?h:{};b.client.Z.webDisplayMode=Cf()}a.appInstallData&&(b.client.configInfo=b.client.configInfo||{},b.client.configInfo.appInstallData=a.appInstallData);
R("DELEGATED_SESSION_ID")&&!S("pageid_as_header_web")&&(b.user={onBehalfOfUser:R("DELEGATED_SESSION_ID")});a:{if(h=Ff()){a=Df[h.type||"unknown"]||"CONN_UNKNOWN";h=Df[h.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===a&&"CONN_UNKNOWN"!==h&&(a=h);if("CONN_UNKNOWN"!==a)break a;if("CONN_UNKNOWN"!==h){a=h;break a}}a=void 0}a&&(b.client.connectionType=a);S("web_log_effective_connection_type")&&(a=Ff(),a=null!==a&&void 0!==a&&a.effectiveType?Ef.hasOwnProperty(a.effectiveType)?Ef[a.effectiveType]:
"EFFECTIVE_CONNECTION_TYPE_UNKNOWN":void 0,a&&(b.client.effectiveConnectionType=a));a=Object;h=a.assign;g=b.client;f={};e=u(Object.entries(te(R("DEVICE",""))));for(c=e.next();!c.done;c=e.next())d=u(c.value),c=d.next().value,d=d.next().value,"cbrand"===c?f.deviceMake=d:"cmodel"===c?f.deviceModel=d:"cbr"===c?f.browserName=d:"cbrver"===c?f.browserVersion=d:"cos"===c?f.osName=d:"cosver"===c?f.osVersion=d:"cplatform"===c&&(f.platform=d);b.client=h.call(a,g,f);return b}
function Hf(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||R("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.Ia||R("AUTHORIZATION"))||(a?b="Bearer "+C("gapi.auth.getToken")().Ha:b=gc([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=R("SESSION_INDEX",0),S("pageid_as_header_web")&&(d["X-Goog-PageId"]=R("DELEGATED_SESSION_ID")));return d}
;function If(a){a=Object.assign({},a);delete a.Authorization;var b=gc();if(b){var c=new yc;c.update(R("INNERTUBE_API_KEY",void 0));c.update(b);b=c.digest();c=3;Aa(b);void 0===c&&(c=0);if(!Nb){Nb={};for(var d="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),e=["+/=","+/","-_=","-_.","-_"],f=0;5>f;f++){var g=d.concat(e[f].split(""));Mb[f]=g;for(var h=0;h<g.length;h++){var k=g[h];void 0===Nb[k]&&(Nb[k]=h)}}}c=Mb[c];d=[];for(e=0;e<b.length;e+=3){var l=b[e],m=(f=e+1<b.length)?
b[e+1]:0;k=(g=e+2<b.length)?b[e+2]:0;h=l>>2;l=(l&3)<<4|m>>4;m=(m&15)<<2|k>>6;k&=63;g||(k=64,f||(m=64));d.push(c[h],c[l],c[m]||"",c[k]||"")}a.hash=d.join("")}return a}
;function Jf(a){var b=new Qd;(b=b.isAvailable()?a?new Wd(b,a):b:null)||(a=new Rd(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new Md(a):null;this.i=document.domain||window.location.hostname}
Jf.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(pd(b))}catch(f){return}else e=escape(b);b=this.i;dc.set(""+a,e,{S:c,path:"/",domain:void 0===b?"youtube.com":b,secure:!1})};
Jf.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=dc.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Jf.prototype.remove=function(a){this.h&&this.h.remove(a);var b=this.i;dc.remove(""+a,"/",void 0===b?"youtube.com":b)};var Kf;function Lf(){Kf||(Kf=new Jf("yt.innertube"));return Kf}
function Mf(a,b,c,d){if(d)return null;d=Lf().get("nextId",!0)||1;var e=Lf().get("requests",!0)||{};e[d]={method:a,request:b,authState:If(c),requestTime:Math.round(T())};Lf().set("nextId",d+1,86400,!0);Lf().set("requests",e,86400,!0);return d}
function Nf(a){var b=Lf().get("requests",!0)||{};delete b[a];Lf().set("requests",b,86400,!0)}
function Of(a){var b=Lf().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(T())-d.requestTime)){var e=d.authState,f=If(Hf(!1));Va(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(T())),Af(a,d.method,e,{}));delete b[c]}}Lf().set("requests",b,86400,!0)}}
;var Pf=C("ytPubsub2Pubsub2Instance")||new Q;Q.prototype.subscribe=Q.prototype.subscribe;Q.prototype.unsubscribeByKey=Q.prototype.M;Q.prototype.publish=Q.prototype.I;Q.prototype.clear=Q.prototype.clear;E("ytPubsub2Pubsub2Instance",Pf);E("ytPubsub2Pubsub2SubscribedKeys",C("ytPubsub2Pubsub2SubscribedKeys")||{});E("ytPubsub2Pubsub2TopicToKeys",C("ytPubsub2Pubsub2TopicToKeys")||{});E("ytPubsub2Pubsub2IsAsync",C("ytPubsub2Pubsub2IsAsync")||{});E("ytPubsub2Pubsub2SkipSubKey",null);var Qf=[],Rf=!1;function Sf(a,b){Rf||(Qf.push({type:"EVENT",eventType:a,payload:b}),10<Qf.length&&Qf.shift())}
;var Tf=function(){var a;return function(){a||(a=new Jf("ytidb"));return a}}();
function Uf(a,b,c){var d;this.i=void 0===a?!1:a;this.failureMessage=b;this.j=c;this.h=null===(d=Tf())||void 0===d?void 0:d.get("LAST_RESULT_ENTRY_KEY",!0);this.h||(this.h={createdTimestampMs:T(),isSupported:this.i,resultCount:0});var e;if(Vf()){var f;this.h.isSupported===this.i?f=Object.assign(Object.assign({},this.h),{resultCount:this.h.resultCount+1}):f={isSupported:this.i,resultCount:1,createdTimestampMs:T()};null===(e=Tf())||void 0===e?void 0:e.set("LAST_RESULT_ENTRY_KEY",f,2592E3,!0)}}
function Wf(a,b){return new Uf(!1,a instanceof Error?a.message:"",void 0===b?!1:b)}
Uf.prototype.isSupported=function(){return this.i};
Uf.prototype.log=function(){Vf()&&Sf("IS_SUPPORTED_COMPLETED",{isSupported:this.i,lastIsSupported:this.h.isSupported,failureMessage:this.failureMessage,sameResultCount:this.h.resultCount,sameResultDurationMs:Math.floor(T()-this.h.createdTimestampMs),canDetectDataOnFailure:this.j})};
function Vf(){var a;return!!(S("ytidb_analyze_is_supported")&&(null===(a=Tf())||void 0===a?0:a.h))}
;function Xf(a,b){for(var c=[],d=1;d<arguments.length;++d)c[d-1]=arguments[d];d=Error.call(this,a);this.message=d.message;"stack"in d&&(this.stack=d.stack);d=[];var e=d.concat;if(!(c instanceof Array)){c=u(c);for(var f,g=[];!(f=c.next()).done;)g.push(f.value);c=g}this.args=e.call(d,c)}
ma(Xf,Error);function Yf(a){return a.substr(0,a.indexOf(":"))||a}
;var Zf={},$f=(Zf.AUTH_INVALID="No user identifier specified.",Zf.EXPLICIT_ABORT="Transaction was explicitly aborted.",Zf.IDB_NOT_SUPPORTED="IndexedDB is not supported.",Zf.MISSING_OBJECT_STORE="Object store not created.",Zf.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",Zf.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",Zf.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",Zf.EXECUTE_TRANSACTION_ON_CLOSED_DB=
"Can't start a transaction on a closed database",Zf),ag={},bg=(ag.AUTH_INVALID="ERROR",ag.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",ag.EXPLICIT_ABORT="IGNORED",ag.IDB_NOT_SUPPORTED="ERROR",ag.MISSING_OBJECT_STORE="ERROR",ag.QUOTA_EXCEEDED="WARNING",ag.QUOTA_MAYBE_EXCEEDED="WARNING",ag.UNKNOWN_ABORT="WARNING",ag),cg={},dg=(cg.AUTH_INVALID=!1,cg.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,cg.EXPLICIT_ABORT=!1,cg.IDB_NOT_SUPPORTED=!1,cg.MISSING_OBJECT_STORE=!1,cg.QUOTA_EXCEEDED=!1,cg.QUOTA_MAYBE_EXCEEDED=!0,
cg.UNKNOWN_ABORT=!0,cg);function U(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?$f[a]:c;d=void 0===d?bg[a]:d;e=void 0===e?dg[a]:e;Xf.call(this,c,Object.assign({name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,U.prototype)}
ma(U,Xf);function eg(a){U.call(this,"MISSING_OBJECT_STORE",{Oa:a},$f.MISSING_OBJECT_STORE);Object.setPrototypeOf(this,eg.prototype)}
ma(eg,U);var fg=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function gg(a,b,c){b=Yf(b);var d=a instanceof Error?a:Error("Unexpected error: "+a);if(d instanceof U)return d;if("QuotaExceededError"===d.name)return new U("QUOTA_EXCEEDED",{objectStoreNames:c,dbName:b});if(Lb&&"UnknownError"===d.name)return new U("QUOTA_MAYBE_EXCEEDED",{objectStoreNames:c,dbName:b});if("InvalidStateError"===d.name&&fg.some(function(e){return d.message.includes(e)}))return new U("EXECUTE_TRANSACTION_ON_CLOSED_DB",{objectStoreNames:c,
dbName:b});if("AbortError"===d.name)return new U("UNKNOWN_ABORT",{objectStoreNames:c,dbName:b},d.message);d.args=[{name:"IdbError",Pa:d.name,dbName:b,objectStoreNames:c}];d.level="WARNING";return d}
;function hg(a){if(!a)throw Error();throw a;}
function ig(a){return a}
function V(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=u(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=u(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.i=a;this.state={status:"PENDING"};this.h=[];this.onRejected=[];try{this.i(c,b)}catch(e){b(e)}}
V.all=function(a){return new V(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={G:0};f.G<a.length;f={G:f.G},++f.G)jg(V.resolve(a[f.G]).then(function(g){return function(h){d[g.G]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})})};
V.resolve=function(a){return new V(function(b,c){a instanceof V?a.then(b,c):b(a)})};
V.reject=function(a){return new V(function(b,c){c(a)})};
V.prototype.then=function(a,b){var c=this,d=null!==a&&void 0!==a?a:ig,e=null!==b&&void 0!==b?b:hg;return new V(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){kg(c,c,d,f,g)}),c.onRejected.push(function(){lg(c,c,e,f,g)})):"FULFILLED"===c.state.status?kg(c,c,d,f,g):"REJECTED"===c.state.status&&lg(c,c,e,f,g)})};
function jg(a,b){a.then(void 0,b)}
function kg(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof V?mg(a,b,f,d,e):d(f)}catch(g){e(g)}}
function lg(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof V?mg(a,b,f,d,e):d(f)}catch(g){e(g)}}
function mg(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof V?mg(a,b,f,d,e):d(f)},function(f){e(f)})}
;function ng(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function og(a){return new Promise(function(b,c){ng(a,b,c)})}
function W(a){return new V(function(b,c){ng(a,b,c)})}
;function pg(a,b){return new V(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()})}
;function qg(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(T());this.i=!1}
p=qg.prototype;p.add=function(a,b,c){return rg(this,[a],{mode:"readwrite",H:S("ytidb_transaction_enable_retries_core_and_nwl")},function(d){return sg(d,a).add(b,c)})};
p.clear=function(a){return rg(this,[a],{mode:"readwrite",H:S("ytidb_transaction_enable_retries_core_and_nwl")},function(b){return sg(b,a).clear()})};
p.close=function(){var a;this.h.close();(null===(a=this.options)||void 0===a?0:a.closed)&&this.options.closed()};
p.count=function(a,b){return rg(this,[a],{mode:"readonly",H:S("ytidb_transaction_enable_retries_core_and_nwl")},function(c){return sg(c,a).count(b)})};
p.delete=function(a,b){return rg(this,[a],{mode:"readwrite",H:S("ytidb_transaction_enable_retries_core_and_nwl")},function(c){return sg(c,a).delete(b)})};
p.get=function(a,b){return rg(this,[a],{mode:"readonly",H:S("ytidb_transaction_enable_retries_core_and_nwl")},function(c){return sg(c,a).get(b)})};
function rg(a,b,c,d){return K(a,function f(){var g=this,h,k,l,m,n,r,q,x,v,w,O;return z(f,function(F){switch(F.h){case 1:var P={mode:"readonly",H:!1};"string"===typeof c?P.mode=c:P=c;h=P;g.transactionCount++;k=h.H?xe("ytidb_transaction_try_count",1):1;case 2:if(l){F.h=3;break}k--;m=Math.round(T());F.j=4;n=g.h.transaction(b,h.mode);P=new tg(n);P=ug(P,d);return y(F,P,6);case 6:return r=F.i,q=Math.round(T()),vg(g,m,q,void 0,b.join(),h),F.return(r);case 4:x=qa(F);v=Math.round(T());w=gg(x,g.h.name,b.join());
if((O=w instanceof U&&!w.h)||0>=k)vg(g,m,v,w,b.join(),h),l=w;F.h=2;break;case 3:return F.return(Promise.reject(l))}})})}
function vg(a,b,c,d,e,f){b=c-b;d?(d instanceof U&&("QUOTA_EXCEEDED"===d.type||"QUOTA_MAYBE_EXCEEDED"===d.type)&&Sf("QUOTA_EXCEEDED",{dbName:Yf(a.h.name),objectStoreNames:e,transactionCount:a.transactionCount,transactionMode:f.mode}),d instanceof U&&"UNKNOWN_ABORT"===d.type&&(Sf("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:e,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c-a.j}),a.i=!0),wg(a,!1,e,b),Rf||(Qf.push({type:"ERROR",payload:d}),10<Qf.length&&Qf.shift())):wg(a,
!0,e,b)}
function wg(a,b,c,d){Sf("TRANSACTION_ENDED",{objectStoreNames:c,connectionHasUnknownAbortedTransaction:a.i,duration:d,isSuccessful:b})}
function xg(a){this.h=a}
p=xg.prototype;p.add=function(a,b){return W(this.h.add(a,b))};
p.clear=function(){return W(this.h.clear()).then(function(){})};
p.count=function(a){return W(this.h.count(a))};
function yg(a,b){return zg(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
p.delete=function(a){return a instanceof IDBKeyRange?yg(this,a):W(this.h.delete(a))};
p.get=function(a){return W(this.h.get(a))};
p.index=function(a){return new Ag(this.h.index(a))};
p.getName=function(){return this.h.name};
function zg(a,b,c){a=a.h.openCursor(b.query,b.direction);return Bg(a).then(function(d){return pg(d,c)})}
function tg(a){var b=this;this.h=a;this.i=new Map;this.aborted=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.aborted){e=U;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function ug(a,b){var c=new Promise(function(d,e){jg(b(a).then(function(f){a.commit();d(f)}),e)});
return Promise.all([c,a.done]).then(function(d){return u(d).next().value})}
tg.prototype.abort=function(){this.h.abort();this.aborted=!0;throw new U("EXPLICIT_ABORT");};
tg.prototype.commit=function(){var a=this.h;a.commit&&!this.aborted&&a.commit()};
function sg(a,b){b=a.h.objectStore(b);var c=a.i.get(b);c||(c=new xg(b),a.i.set(b,c));return c}
function Ag(a){this.h=a}
Ag.prototype.count=function(a){return W(this.h.count(a))};
Ag.prototype.delete=function(a){return Cg(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
Ag.prototype.get=function(a){return W(this.h.get(a))};
Ag.prototype.getKey=function(a){return W(this.h.getKey(a))};
function Cg(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Bg(a).then(function(d){return pg(d,c)})}
function Dg(a,b){this.request=a;this.cursor=b}
function Bg(a){return W(a).then(function(b){return null===b?null:new Dg(a,b)})}
p=Dg.prototype;p.advance=function(a){this.cursor.advance(a);return Bg(this.request)};
p.continue=function(a){this.cursor.continue(a);return Bg(this.request)};
p.delete=function(){return W(this.cursor.delete()).then(function(){})};
p.getKey=function(){return this.cursor.key};
p.update=function(a){return W(this.cursor.update(a))};function Eg(a,b,c){return K(this,function e(){var f,g,h,k,l,m,n,r,q,x;return z(e,function(v){if(1==v.h)return f=self.indexedDB.open(a,b),g=c,h=g.blocked,k=g.blocking,l=g.va,m=g.upgrade,n=g.closed,q=function(){r||(r=new qg(f.result,{closed:n}));return r},f.addEventListener("upgradeneeded",function(w){if(null===w.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");
if(null===f.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");w.dataLoss&&"none"!==w.dataLoss&&Sf("IDB_DATA_CORRUPTED",{reason:w.dataLossMessage||"unknown reason",dbName:Yf(a)});var O=q(),F=new tg(f.transaction);m&&m(O,w.oldVersion,w.newVersion,F)}),h&&f.addEventListener("blocked",function(){h()}),y(v,og(f),2);
x=v.i;k&&x.addEventListener("versionchange",function(){k(q())});
x.addEventListener("close",function(){Sf("IDB_UNEXPECTEDLY_CLOSED",{dbName:Yf(a),dbVersion:x.version});l&&l()});
return v.return(q())})})}
function Fg(a,b){b=void 0===b?{}:b;return K(this,function d(){var e,f,g;return z(d,function(h){e=self.indexedDB.deleteDatabase(a);f=b;(g=f.blocked)&&e.addEventListener("blocked",function(){g()});
return y(h,og(e),0)})})}
;function Gg(a){this.name="YtIdbMeta";this.options=a;this.i=!1}
function Hg(a,b,c){c=void 0===c?{}:c;c=void 0===c?{}:c;return Eg(a,b,c)}
Gg.prototype.delete=function(a){a=void 0===a?{}:a;return Fg(this.name,a)};
Gg.prototype.open=function(){var a=this;if(!this.h){var b,c=function(){a.h===b&&(a.h=void 0)},d={blocking:function(f){f.close()},
closed:c,va:c,upgrade:this.options.upgrade},e=function(){return K(a,function g(){var h=this,k,l,m;return z(g,function(n){switch(n.h){case 1:return n.j=2,y(n,Hg(h.name,h.options.version,d),4);case 4:k=n.i;a:{var r=u(Object.keys(h.options.ta));for(var q=r.next();!q.done;q=r.next())if(q=q.value,!k.h.objectStoreNames.contains(q)){r=q;break a}r=void 0}l=r;if(void 0===l){n.h=5;break}if(h.i){n.h=6;break}h.i=!0;return y(n,h.delete(),7);case 7:return n.return(e());case 6:throw new eg(l);case 5:return n.return(k);
case 2:m=qa(n);if(m instanceof DOMException?"VersionError"===m.name:"DOMError"in self&&m instanceof DOMError?"VersionError"===m.name:m instanceof Object&&"message"in m&&"An attempt was made to open a database using a lower version than the existing version."===m.message)return n.return(Hg(h.name,void 0,Object.assign(Object.assign({},d),{upgrade:void 0})));c();throw m;}})})};
this.h=b=e()}return this.h};var Ig=new Gg({ta:{databases:!0},upgrade:function(a,b){1>b&&a.h.createObjectStore("databases",{keyPath:"actualName"})}});
function Jg(a){return K(this,function c(){var d;return z(c,function(e){if(1==e.h)return y(e,Ig.open(),2);d=e.i;return e.return(rg(d,["databases"],"readwrite",function(f){var g=sg(f,"databases");return g.get(a.actualName).then(function(h){if(h?a.actualName!==h.actualName||a.publicName!==h.publicName||a.userIdentifier!==h.userIdentifier||a.clearDataOnAuthChange!==h.clearDataOnAuthChange:1)return W(g.h.put(a,void 0)).then(function(){})})}))})})}
function Kg(){return K(this,function b(){var c;return z(b,function(d){if(1==d.h)return y(d,Ig.open(),2);c=d.i;return d.return(c.delete("databases","yt-idb-test-do-not-use"))})})}
function Lg(){return K(this,function b(){var c,d;return z(b,function(e){if(1==e.h)return y(e,Ig.open(),2);if(3!=e.h)return c=e.i,y(e,c.count("databases"),3);d=e.i;return e.return(0<d)})})}
;var Mg;
function Ng(){return K(this,function b(){var c,d,e,f;return z(b,function(g){switch(g.h){case 1:var h;if(h=Ue)h=/WebKit\/([0-9]+)/.exec(I),h=!!(h&&600<=parseInt(h[1],10));h&&(h=/WebKit\/([0-9]+)/.exec(I),h=!(h&&602<=parseInt(h[1],10)));if(h)return g.return(Wf(Error("YtIdb is not supported on iOS 8 or 9")));if(xb)return g.return(Wf(Error("YtIdb is not supported on Edge")));try{if(c=self,!(c.indexedDB&&c.IDBIndex&&c.IDBKeyRange&&c.IDBObjectStore))return g.return(Wf(Error("Non-prefixed indexedDB APIs are missing")))}catch(k){return g.return(Wf(k))}if(!("IDBTransaction"in self&&
"objectStoreNames"in IDBTransaction.prototype))return g.return(Wf(Error("IDBTransaction.prototype.objectStoreNames is missing")));g.j=2;d={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return y(g,Jg(d),4);case 4:return y(g,Kg(),5);case 5:return g.return(new Uf(!0));case 2:e=qa(g);if(!Vf()){g.h=6;break}g.j=7;return y(g,Lg(),9);case 9:return f=g.i,g.return(Wf(e,f));case 7:return qa(g),g.return(Wf(e));case 6:return g.return(Wf(e))}})})}
function Og(){if(void 0!==Mg)return Mg;Rf=!0;return Mg=Ng().then(function(a){Rf=!1;a.log();return a.isSupported()})}
;var Pg;function Qg(){Pg||(Pg=new Jf("yt.offline"));return Pg}
;function Rg(){M.call(this);this.s=this.u=this.C=this.l=!1;this.i=Sg();this.s=S("validate_network_status");Tg(this);Ug(this)}
ma(Rg,M);function Sg(){var a=window.navigator.onLine;return void 0===a?!0:a}
function Ug(a){window.addEventListener("online",function(){return K(a,function c(){var d=this;return z(c,function(e){if(1==e.h){if(!d.s){d.i=!0;e.h=2;return}return y(e,Vg(d),3)}2!=e.h&&(d.i=e.i);d.l&&d.i&&nd(d,"ytnetworkstatus-online");Wg(d);if(d.u&&S("offline_error_handling")){var f=Qg().get("errors",!0);if(f){for(var g in f)if(f[g]){var h=new Xf(g,"sent via offline_errors");h.name=f[g].name;h.stack=f[g].stack;h.level=f[g].level;be(h)}Qg().set("errors",{},2592E3,!0)}}e.h=0})})})}
function Tg(a){window.addEventListener("offline",function(){return K(a,function c(){var d=this;return z(c,function(e){if(1==e.h){if(!d.s){d.i=!1;e.h=2;return}return y(e,Vg(d),3)}2!=e.h&&(d.i=e.i);d.l&&!d.i&&nd(d,"ytnetworkstatus-offline");Wg(d);e.h=0})})})}
function Wg(a){a.C&&(ce(new Xf("NetworkStatusManager state did not match poll",T()-0)),a.C=!1)}
function Vg(a){return K(a,function c(){var d;return z(c,function(e){switch(e.h){case 1:return e.j=2,y(e,fetch("/generate_204",{method:"HEAD"}),4);case 4:d=!0;e.h=3;e.j=0;break;case 2:qa(e),d=!1;case 3:return e.return(d)}})})}
;function Xg(a){a=void 0===a?{}:a;M.call(this);var b=this;this.l=this.u=0;Rg.h||(Rg.h=new Rg);this.i=Rg.h;this.i.l=!0;a.sa&&(this.i.u=!0);a.R?(this.R=a.R,ed(this.i,"ytnetworkstatus-online",function(){Yg(b,"publicytnetworkstatus-online")}),ed(this.i,"ytnetworkstatus-offline",function(){Yg(b,"publicytnetworkstatus-offline")})):(ed(this.i,"ytnetworkstatus-online",function(){nd(b,"publicytnetworkstatus-online")}),ed(this.i,"ytnetworkstatus-offline",function(){nd(b,"publicytnetworkstatus-offline")}))}
ma(Xg,M);function Yg(a,b){a.R?a.l?(Ce(a.u),a.u=ze(function(){a.s!==b&&(nd(a,b),a.s=b,a.l=T())},a.R-(T()-a.l))):(nd(a,b),a.s=b,a.l=T()):nd(a,b)}
;var Zg;function $g(a,b){b=void 0===b?{}:b;Og().then(function(){Zg||(Zg=new Xg({sa:!0}));Zg.i.i!==Sg()&&ce(new Xf("NetworkStatusManager isOnline does not match window status"));Me(a,b)})}
function ah(a,b){b=void 0===b?{}:b;Og().then(function(){Me(a,b)})}
;function bh(a){var b=this;this.h=null;a?this.h=a:Gf()&&(this.h=xf());Ae(function(){Of(b)},0,5E3)}
bh.prototype.isReady=function(){!this.h&&Gf()&&(this.h=xf());return!!this.h};
function Af(a,b,c,d){!R("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&ce(new Xf("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var e=new Xf("innertube xhrclient not ready",b,c,d);be(e);throw e;}var f={headers:{"Content-Type":"application/json"},method:"POST",postParams:c,postBodyFormat:"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(n,r){if(d.onSuccess)d.onSuccess(r)},
onFetchSuccess:function(n){if(d.onSuccess)d.onSuccess(n)},
onError:function(n,r){if(d.onError)d.onError(r)},
onFetchError:function(n){if(d.onError)d.onError(n)},
timeout:d.timeout,withCredentials:!0},g="";(e=a.h.oa)&&(g=e);var h=a.h.qa||!1,k=Hf(h,g,d);Object.assign(f.headers,k);f.headers.Authorization&&!g&&(f.headers["x-origin"]=window.location.origin);e="/youtubei/"+a.h.innertubeApiVersion+"/"+b;var l={alt:"json"};a.h.pa&&f.headers.Authorization||(l.key=a.h.innertubeApiKey);var m=ue(""+g+e,l||{},!0);(function(n){n=void 0===n?!1:n;var r;if(d.retry&&S("retry_web_logging_batches")&&"www.youtube-nocookie.com"!=g&&(n||(r=Mf(b,c,k,h)),r)){var q=f.onSuccess,x=f.onFetchSuccess;
f.onSuccess=function(v,w){Nf(r);q(v,w)};
c.onFetchSuccess=function(v,w){Nf(r);x(v,w)}}try{n&&d.retry&&!d.aa.bypassNetworkless?(f.method="POST",!d.aa.writeThenSend&&S("nwl_send_fast_on_unload")?ah(m,f):$g(m,f)):(f.method="POST",f.postParams||(f.postParams={}),Me(m,f))}catch(v){if("InvalidAccessError"==v.name)r&&(Nf(r),r=0),ce(Error("An extension is blocking network request."));
else throw v;}r&&Ae(function(){Of(a)},0,5E3)})(!1)}
;function ch(a,b){var c=void 0===c?{}:c;var d=bh;R("ytLoggingEventsDefaultDisabled",!1)&&bh==bh&&(d=null);c=void 0===c?{}:c;var e={};e.eventTimeMs=Math.round(c.timestamp||T());e[a]=b;a=C("_lact",window);a=null==a?-1:Math.max(Date.now()-a,0);e.context={lastActivityMs:String(c.timestamp||!isFinite(a)?-1:a)};S("log_sequence_info_on_gel_web")&&c.ca&&(a=e.context,b=c.ca,Bf[b]=b in Bf?Bf[b]+1:0,a.sequence={index:Bf[b],groupKey:b},c.Ma&&delete Bf[c.ca]);(c.Ra?uf:qf)({endpoint:"log_event",payload:e,B:c.B},
d)}
;var dh=[{Y:function(a){return"Cannot read property '"+a.key+"'"},
T:{TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,
groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]}],Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}]}},{Y:function(a){return"Cannot call '"+a.key+"'"},
T:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}}];function eh(){this.h=[];this.i=[]}
var fh;function gh(){fh||(fh=new eh);return fh}
;var hh=new Q;function ih(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=jh(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=jh(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=jh(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function jh(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function kh(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=lh(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=e;var g=a[e],h=b,k=c;f="string"!==typeof g||"clickTrackingParams"!==f&&"trackingParams"!==f?0:(g=ih(atob(g.replace(/-/g,"+").replace(/_/g,"/"))))?lh(f+".ve",g,h,k):0;d+=f;d+=lh(e,a[e],b,c);if(500<d)break}}else c[b]=mh(a),d+=c[b].length;else c[b]=mh(a),d+=c[b].length;return d}
function lh(a,b,c,d){c+="."+a;a=mh(b);d[c]=a;return c.length+a.length}
function mh(a){return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}
;var nh=new Set,oh=0,ph=0,qh=0,rh=[],sh=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];var th={};function uh(a){return th[a]||(th[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var vh={},wh=[],Gd=new Q,xh={};function yh(){for(var a=u(wh),b=a.next();!b.done;b=a.next())b=b.value,b()}
function zh(a,b){var c;"yt:"===a.tagName.toLowerCase().substr(0,3)?c=a.getAttribute(b):c=a?a.dataset?a.dataset[uh(b)]:a.getAttribute("data-"+b):null;return c}
function Ah(a,b){for(var c=1;c<arguments.length;++c);Gd.I.apply(Gd,arguments)}
;function Bh(a){this.j=this.h=!1;this.i=a||{};a=document.getElementById("www-widgetapi-script");if(this.h=!!("https:"===document.location.protocol||a&&0===a.src.indexOf("https:"))){a=[this.i,window.YTConfig||{}];for(var b=0;b<a.length;b++)a[b].host&&(a[b].host=a[b].host.toString().replace("http://","https://"))}}
function X(a,b){a=[a.i,window.YTConfig||{}];for(var c=0;c<a.length;c++){var d=a[c][b];if(void 0!==d)return d}return null}
function Ch(a,b,c){Dh||(Dh={},me(window,"message",function(d){a:{if(d.origin===X(a,"host")||d.origin===X(a,"host").toString().replace(/^http:/,"https:")){try{var e=JSON.parse(d.data)}catch(f){e=void 0;break a}a.j=!0;a.h||0!==d.origin.indexOf("https:")||(a.h=!0);if(d=Dh[e.id])d.s=!0,d.s&&(H(d.o,d.sendMessage,d),d.o.length=0),d.U(e)}e=void 0}return e}));
Dh[c]=b}
var Dh=null;function Y(a,b,c){this.m=this.h=this.i=null;this.j=0;this.s=!1;this.o=[];this.l=null;this.C={};this.id=Ba(this);this.u=c;this.setup(a,b)}
p=Y.prototype;p.setSize=function(a,b){this.h.width=a.toString();this.h.height=b.toString();return this};
p.ia=function(){return this.h};
p.U=function(a){Eh(this,a.event,a)};
p.addEventListener=function(a,b){var c=b;"string"===typeof b&&(c=function(){window[b].apply(window,arguments)});
if(!c)return this;this.l.subscribe(a,c);Fh(this,a);return this};
function Gh(a,b){b=b.split(".");if(2===b.length){var c=b[1];a.u===b[0]&&Fh(a,c)}}
p.destroy=function(){this.h&&this.h.id&&(vh[this.h.id]=null);var a=this.l;a&&"function"==typeof a.dispose&&a.dispose();if(this.m){a=this.h;var b=a.parentNode;b&&b.replaceChild(this.m,a)}else(a=this.h)&&a.parentNode&&a.parentNode.removeChild(a);Dh&&(Dh[this.id]=null);this.i=null;a=this.h;for(var c in Ua)Ua[c][0]==a&&ke(c);this.m=this.h=null};
p.W=function(){return{}};
function Hh(a,b,c){c=c||[];c=Array.prototype.slice.call(c);b={event:"command",func:b,args:c};a.s?a.sendMessage(b):a.o.push(b)}
function Eh(a,b,c){a.l.j||(c={target:a,data:c},a.l.I(b,c),Ah(a.u+"."+b,c))}
function Ih(a,b){var c=document.createElement("iframe");b=b.attributes;for(var d=0,e=b.length;d<e;d++){var f=b[d].value;null!=f&&""!==f&&"null"!==f&&c.setAttribute(b[d].name,f)}c.setAttribute("frameBorder","0");c.setAttribute("allowfullscreen","1");c.setAttribute("allow","accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture");c.setAttribute("title","YouTube "+X(a.i,"title"));(b=X(a.i,"width"))&&c.setAttribute("width",b.toString());(b=X(a.i,"height"))&&c.setAttribute("height",
b.toString());var g=a.W();g.enablejsapi=window.postMessage?1:0;window.location.host&&(g.origin=window.location.protocol+"//"+window.location.host);g.widgetid=a.id;window.location.href&&H(["debugjs","debugcss"],function(h){var k=sb(window.location.href,h);null!==k&&(g[h]=k)});
c.src=X(a.i,"host")+("/embed/"+X(a.i,"videoId"))+"?"+qb(g);return c}
p.ba=function(){this.h&&this.h.contentWindow?this.sendMessage({event:"listening"}):window.clearInterval(this.j)};
function Jh(a){Ch(a.i,a,a.id);a.j=ee(a.ba.bind(a));me(a.h,"load",function(){window.clearInterval(a.j);a.j=ee(a.ba.bind(a))})}
p.setup=function(a,b){var c=document;if(a="string"===typeof a?c.getElementById(a):a)if(c="iframe"===a.tagName.toLowerCase(),b.host||(b.host=c?ob(a.src):"https://www.youtube.com"),this.i=new Bh(b),c||(b=Ih(this,a),this.m=a,(c=a.parentNode)&&c.replaceChild(b,a),a=b),this.h=a,this.h.id||(this.h.id="widget"+Ba(this.h)),vh[this.h.id]=this,window.postMessage){this.l=new Q;Jh(this);b=X(this.i,"events");for(var d in b)b.hasOwnProperty(d)&&this.addEventListener(d,b[d]);for(var e in xh)xh.hasOwnProperty(e)&&
Gh(this,e)}};
function Fh(a,b){a.C[b]||(a.C[b]=!0,Hh(a,"addEventListener",[b]))}
p.sendMessage=function(a){a.id=this.id;a.channel="widget";a=pd(a);var b=this.i;var c=ob(this.h.src||"");b=0===c.indexOf("https:")?[c]:b.h?[c.replace("http:","https:")]:b.j?[c]:[c,c.replace("http:","https:")];if(this.h.contentWindow)for(c=0;c<b.length;c++)try{this.h.contentWindow.postMessage(a,b[c])}catch(w){if(w.name&&"SyntaxError"===w.name){if(!(w.message&&0<w.message.indexOf("target origin ''"))){var d=void 0,e=w;d=void 0===d?{}:d;d.name=R("INNERTUBE_CONTEXT_CLIENT_NAME",1);d.version=R("INNERTUBE_CONTEXT_CLIENT_VERSION",
void 0);var f=d||{};d="WARNING";d=void 0===d?"ERROR":d;if(e){e.level&&(d=e.level);if(S("console_log_js_exceptions")){var g=e,h=[];h.push("Name: "+g.name);h.push("Message: "+g.message);g.hasOwnProperty("params")&&h.push("Error Params: "+JSON.stringify(g.params));g.hasOwnProperty("args")&&h.push("Error args: "+JSON.stringify(g.args));h.push("File name: "+g.fileName);h.push("Stacktrace: "+g.stack);window.console.log(h.join("\n"),g)}if(!(5<=oh)){g=void 0;var k=f,l=Ac(e);f=l.message||"Unknown Error";h=
l.name||"UnknownError";var m=l.stack||e.i||"Not available";if(m.startsWith(h+": "+f)){var n=m.split("\n");n.shift();m=n.join("\n")}n=l.lineNumber||"Not available";l=l.fileName||"Not available";var r=0;if(e.hasOwnProperty("args")&&e.args&&e.args.length)for(g=0;g<e.args.length&&!(r=kh(e.args[g],"params."+g,k,r),500<=r);g++);else if(e.hasOwnProperty("params")&&e.params){var q=e.params;if("object"===typeof e.params)for(g in q){if(q[g]){var x="params."+g,v=mh(q[g]);k[x]=v;r+=x.length+v.length;if(500<r)break}}else k.params=
mh(q)}if(rh.length)for(g=0;g<rh.length&&!(r=kh(rh[g],"params.context."+g,k,r),500<=r);g++);navigator.vendor&&!k.hasOwnProperty("vendor")&&(k["device.vendor"]=navigator.vendor);g={message:f,name:h,lineNumber:n,fileName:l,stack:m,params:k,sampleWeight:1};f=Number(e.columnNumber);isNaN(f)||(g.lineNumber=g.lineNumber+":"+f);if("IGNORED"===e.level)e=0;else a:{e=gh();f=u(e.i);for(h=f.next();!h.done;h=f.next())if(h=h.value,g.message&&g.message.match(h.Na)){e=h.weight;break a}e=u(e.h);for(f=e.next();!f.done;f=
e.next())if(f=f.value,f.Ka(g)){e=f.weight;break a}e=1}g.sampleWeight=e;e=g;g=u(dh);for(f=g.next();!f.done;f=g.next())if(f=f.value,f.T[e.name])for(n=u(f.T[e.name]),h=n.next();!h.done;h=n.next())if(l=h.value,h=e.message.match(l.regexp)){e.params["params.error.original"]=h[0];n=l.groups;l={};for(m=0;m<n.length;m++)l[n[m]]=h[m+1],e.params["params.error."+n[m]]=h[m+1];e.message=f.Y(l);break}e.params||(e.params={});g=gh();e.params["params.errorServiceSignature"]="msg="+g.i.length+"&cb="+g.h.length;e.params["params.serviceWorker"]=
"false";B.document&&B.document.querySelectorAll&&(e.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));window.yterr&&"function"===typeof window.yterr&&window.yterr(e);if(0!==e.sampleWeight&&!nh.has(e.message)){"ERROR"===d?(hh.I("handleError",e),S("record_app_crashed_web")&&0===qh&&1===e.sampleWeight&&(qh++,ch("appCrashed",{appCrashType:"APP_CRASH_TYPE_BREAKPAD"})),ph++):"WARNING"===d&&hh.I("handleWarning",e);if(S("kevlar_gel_error_routing")){h=d;f=e;b:{g=u(sh);
for(n=g.next();!n.done;n=g.next())if((l=I)&&0<=l.toLowerCase().indexOf(n.value.toLowerCase())){g=!0;break b}g=!1}if(g)g=void 0;else{n={stackTrace:f.stack};f.fileName&&(n.filename=f.fileName);g=f.lineNumber&&f.lineNumber.split?f.lineNumber.split(":"):[];0!==g.length&&(1!==g.length||isNaN(Number(g[0]))?2!==g.length||isNaN(Number(g[0]))||isNaN(Number(g[1]))||(n.lineNumber=Number(g[0]),n.columnNumber=Number(g[1])):n.lineNumber=Number(g[0]));g={level:"ERROR_LEVEL_UNKNOWN",message:f.message,errorClassName:f.name,
sampleWeight:f.sampleWeight};"ERROR"===h?g.level="ERROR_LEVEL_ERROR":"WARNING"===h&&(g.level="ERROR_LEVEL_WARNNING");h={isObfuscated:!0,browserStackInfo:n};n={pageUrl:window.location.href,kvPairs:[]};R("FEXP_EXPERIMENTS")&&(n.experimentIds=R("FEXP_EXPERIMENTS"));if(f=f.params)for(l=u(Object.keys(f)),m=l.next();!m.done;m=l.next())m=m.value,n.kvPairs.push({key:"client."+m,value:String(f[m])});f=R("SERVER_NAME",void 0);l=R("SERVER_VERSION",void 0);f&&l&&(n.kvPairs.push({key:"server.name",value:f}),n.kvPairs.push({key:"server.version",
value:l}));g={errorMetadata:n,stackTrace:h,logMessage:g}}g&&(ch("clientError",g),sf())}if(!S("suppress_error_204_logging")){f=e;g=f.params||{};d={urlParams:{a:"logerror",t:"jserror",type:f.name,msg:f.message.substr(0,250),line:f.lineNumber,level:d,"client.name":g.name},postParams:{url:R("PAGE_NAME",window.location.href),file:f.fileName},method:"POST"};g.version&&(d["client.version"]=g.version);if(d.postParams){f.stack&&(d.postParams.stack=f.stack);f=u(Object.keys(g));for(h=f.next();!h.done;h=f.next())h=
h.value,d.postParams["client."+h]=g[h];if(g=R("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0))for(f=u(Object.keys(g)),h=f.next();!h.done;h=f.next())h=h.value,d.postParams[h]=g[h];g=R("SERVER_NAME",void 0);f=R("SERVER_VERSION",void 0);g&&f&&(d.postParams["server.name"]=g,d.postParams["server.version"]=f)}Me(R("ECATCHER_REPORT_HOST","")+"/error_204",d)}nh.add(e.message);oh++}}}}}else throw w;}else console&&console.warn&&console.warn("The YouTube player is not attached to the DOM. API calls should be made after the onReady event. See more: https://developers.google.com/youtube/iframe_api_reference#Events")};function Kh(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function Lh(a){return 0===a.search("get")||0===a.search("is")}
;function Z(a,b){if(!a)throw Error("YouTube player element ID required.");var c={title:"video player",videoId:"",width:640,height:360};if(b)for(var d in b)c[d]=b[d];Y.call(this,a,c,"player");this.F={};this.playerInfo={}}
ma(Z,Y);p=Z.prototype;p.W=function(){var a=X(this.i,"playerVars");if(a){var b={},c;for(c in a)b[c]=a[c];a=b}else a={};window!=window.top&&document.referrer&&(a.widget_referrer=document.referrer.substring(0,256));if(c=X(this.i,"embedConfig")){if(D(c))try{c=JSON.stringify(c)}catch(d){console.error("Invalid embed config JSON",d)}a.embed_config=c}return a};
p.U=function(a){var b=a.event;a=a.info;switch(b){case "apiInfoDelivery":if(D(a))for(var c in a)this.F[c]=a[c];break;case "infoDelivery":Mh(this,a);break;case "initialDelivery":window.clearInterval(this.j);this.playerInfo={};this.F={};Nh(this,a.apiInterface);Mh(this,a);break;default:Eh(this,b,a)}};
function Mh(a,b){if(D(b))for(var c in b)a.playerInfo[c]=b[c]}
function Nh(a,b){H(b,function(c){this[c]||("getCurrentTime"==c?this[c]=function(){var d=this.playerInfo.currentTime;if(1==this.playerInfo.playerState){var e=(Date.now()/1E3-this.playerInfo.currentTimeLastUpdated_)*this.playerInfo.playbackRate;0<e&&(d+=Math.min(e,1))}return d}:Kh(c)?this[c]=function(){this.playerInfo={};
this.F={};Hh(this,c,arguments);return this}:Lh(c)?this[c]=function(){var d=0;
0===c.search("get")?d=3:0===c.search("is")&&(d=2);return this.playerInfo[c.charAt(d).toLowerCase()+c.substr(d+1)]}:this[c]=function(){Hh(this,c,arguments);
return this})},a)}
p.getVideoEmbedCode=function(){var a=parseInt(X(this.i,"width"),10),b=parseInt(X(this.i,"height"),10),c=X(this.i,"host")+("/embed/"+X(this.i,"videoId"));gb.test(c)&&(-1!=c.indexOf("&")&&(c=c.replace(ab,"&amp;")),-1!=c.indexOf("<")&&(c=c.replace(bb,"&lt;")),-1!=c.indexOf(">")&&(c=c.replace(cb,"&gt;")),-1!=c.indexOf('"')&&(c=c.replace(db,"&quot;")),-1!=c.indexOf("'")&&(c=c.replace(eb,"&#39;")),-1!=c.indexOf("\x00")&&(c=c.replace(fb,"&#0;")));return'<iframe width="'+a+'" height="'+b+'" src="'+c+'" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>'};
p.getOptions=function(a){return this.F.namespaces?a?this.F[a].options||[]:this.F.namespaces||[]:[]};
p.getOption=function(a,b){if(this.F.namespaces&&a&&b)return this.F[a][b]};
function Oh(a){if("iframe"!=a.tagName.toLowerCase()){var b=zh(a,"videoid");b&&(b={videoId:b,width:zh(a,"width"),height:zh(a,"height")},new Z(a,b))}}
;E("YT.PlayerState.UNSTARTED",-1);E("YT.PlayerState.ENDED",0);E("YT.PlayerState.PLAYING",1);E("YT.PlayerState.PAUSED",2);E("YT.PlayerState.BUFFERING",3);E("YT.PlayerState.CUED",5);E("YT.get",function(a){return vh[a]});
E("YT.scan",yh);E("YT.subscribe",function(a,b,c){Gd.subscribe(a,b,c);xh[a]=!0;for(var d in vh)vh.hasOwnProperty(d)&&Gh(vh[d],a)});
E("YT.unsubscribe",function(a,b,c){Fd(a,b,c)});
E("YT.Player",Z);Y.prototype.destroy=Y.prototype.destroy;Y.prototype.setSize=Y.prototype.setSize;Y.prototype.getIframe=Y.prototype.ia;Y.prototype.addEventListener=Y.prototype.addEventListener;Z.prototype.getVideoEmbedCode=Z.prototype.getVideoEmbedCode;Z.prototype.getOptions=Z.prototype.getOptions;Z.prototype.getOption=Z.prototype.getOption;
wh.push(function(a){var b=a;b||(b=document);a=Qa(b.getElementsByTagName("yt:player"));var c=b||document;if(c.querySelectorAll&&c.querySelector)b=c.querySelectorAll(".yt-player");else{var d;c=document;b=b||c;if(b.querySelectorAll&&b.querySelector)b=b.querySelectorAll(".yt-player");else if(b.getElementsByClassName){var e=b.getElementsByClassName("yt-player");b=e}else{e=b.getElementsByTagName("*");var f={};for(c=d=0;b=e[c];c++){var g=b.className,h;if(h="function"==typeof g.split)h=0<=La(g.split(/\s+/),
"yt-player");h&&(f[d++]=b)}f.length=d;b=f}}b=Qa(b);H(Pa(a,b),Oh)});
"undefined"!=typeof YTConfig&&YTConfig.parsetags&&"onload"!=YTConfig.parsetags||yh();var Ph=B.onYTReady;Ph&&Ph();var Qh=B.onYouTubeIframeAPIReady;Qh&&Qh();var Rh=B.onYouTubePlayerAPIReady;Rh&&Rh();}).call(this);
