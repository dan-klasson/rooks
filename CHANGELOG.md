# v3 
 - Critical bug with useKey with refs not detected was fixed
 - `useWindowSize` now returns `innerHeight`, `innerWidth`, `outerHeight` and `outerWidth`. It no longer returns `height` and `width` which were ambiguous.
 - `useWorker` has a new signature.
 - `useInterval` had issues with `useState` which have been resolved
 - `usePrevious` has a much simpler implementation using `useRef`
 - `typescript` types have been added to all the hooks
 - Storybook website has been added
 - Uniform major package version for all packages. It makes development easier and it also helps tracking compatibility.