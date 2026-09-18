## Senior/Principal Angular + TypeScript + RxJS interviews

# 1. JavaScript Fundamentals

### Core JavaScript

1. What are `var`, `let`, and `const`?
2. What is hoisting?
3. What is the Temporal Dead Zone?
4. What is scope in JavaScript?
5. What is lexical scope?
6. What is a closure?
7. Give a real-world use case for closures.
8. What is an execution context?
9. What is the call stack?
10. How does JavaScript execute synchronous code?
11. What is the difference between primitive and reference types?
12. What is pass-by-value vs pass-by-reference?
13. What is shallow copy vs deep copy?
14. What are spread and rest operators?
15. What is destructuring?
16. What is `this` in JavaScript?
17. How does `this` behave in arrow functions?
18. What are `call`, `apply`, and `bind`?
19. What are prototypes?
20. What is the prototype chain?
21. How does JavaScript inheritance work?
22. What is the difference between class inheritance and prototype inheritance?
23. What are ES modules?
24. What is the difference between CommonJS and ES modules?
25. What are optional chaining and nullish coalescing?

### Array/Object

26. Difference between `map()` and `forEach()`?
27. Difference between `filter()` and `find()`?
28. How does `reduce()` work?
29. Difference between `slice()` and `splice()`?
30. What do `some()` and `every()` do?
31. How does `sort()` behave?
32. How would you remove duplicates from an array?
33. How would you group an array of objects?
34. How would you flatten a nested array?
35. What is `flatMap()`?

---

# 2. JavaScript Async / Event Loop

36. What is the JavaScript Event Loop?
37. What are microtasks and macrotasks?
38. What is the Microtask Queue?
39. What is the Task/Macrotask Queue?
40. Where do Promises execute?
41. Where does `setTimeout()` execute?
42. What is the execution order of Promise and `setTimeout()`?
43. What is a Promise?
44. What are the states of a Promise?
45. What is `async/await`?
46. What happens internally when using `await`?
47. Difference between Promise and Observable?
48. What is `Promise.all()`?
49. What is `Promise.allSettled()`?
50. What is `Promise.race()`?
51. What is `Promise.any()`?
52. How do you handle errors with `async/await`?
53. What happens when a Promise rejects without a catch?
54. How can you cancel asynchronous JavaScript operations?
55. Explain this output:

```js
console.log('A');

setTimeout(() => console.log('B'));

Promise.resolve().then(() => console.log('C'));

console.log('D');
```

---

# 3. TypeScript Fundamentals

56. What is TypeScript?
57. What are the advantages of TypeScript?
58. What are the disadvantages of TypeScript?
59. How does TypeScript become JavaScript?
60. What is static typing?
61. What are TypeScript primitive types?
62. What is type inference?
63. What is an interface?
64. How do you create a TypeScript interface?
65. Interface vs type?
66. Can interfaces extend interfaces?
67. Can types extend types?
68. Can a class implement an interface?
69. What are optional properties?
70. What are readonly properties?
71. How do you define arrays in TypeScript?
72. How do you define tuples?
73. What are union types?
74. What are intersection types?
75. What are literal types?
76. What is an enum?
77. Numeric enum vs string enum?
78. Enum vs union type?
79. What is a custom type?
80. What is type assertion?
81. Does type assertion perform runtime conversion?
82. What is `unknown`?
83. What is `any`?
84. Why is `any` considered dangerous?
85. `unknown` vs `any`?
86. What is `void`?
87. What is `never`?
88. `void` vs `never`?
89. `null` vs `undefined`?
90. What is function type annotation?
91. How do you define optional/default function parameters?
92. How do you type an async function?
93. What is `tsconfig.json`?
94. What does `strict` mode do?
95. What is `strictNullChecks`?
96. What is `noImplicitAny`?
97. What is module resolution?

---

# 4. Advanced TypeScript

98. What are generics?
99. Why are generics useful?
100. How do you create a generic function?
101. How do you create a generic interface?
102. How do you constrain a generic?
103. What is `keyof`?
104. What is `typeof` in a type context?
105. What are indexed access types?
106. What are conditional types?
107. What are mapped types?
108. What are template literal types?
109. What is a type guard?
110. What is type narrowing?
111. How does `typeof` narrowing work?
112. How does `instanceof` narrowing work?
113. How does the `in` operator narrow types?
114. What is a user-defined type guard?
115. What is a discriminated union?
116. How do you achieve exhaustive checking?
117. What does `as const` do?
118. What is the `satisfies` operator?
119. What is structural typing?
120. What are utility types?
121. Explain `Partial<T>`.
122. Explain `Required<T>`.
123. Explain `Readonly<T>`.
124. Explain `Pick<T>`.
125. Explain `Omit<T>`.
126. Explain `Record<K,T>`.
127. Explain `Exclude<T,U>`.
128. Explain `Extract<T,U>`.
129. Explain `NonNullable<T>`.
130. Explain `ReturnType<T>`.
131. Explain `Parameters<T>`.
132. Explain `Awaited<T>`.
133. What are declaration files (`.d.ts`)?
134. What is module augmentation?
135. What are type-only imports?

---

# 5. RxJS Fundamentals

136. What is RxJS?
137. What problem does RxJS solve?
138. What are the advantages of RxJS?
139. What are the disadvantages of RxJS?
140. What is an Observable?
141. What are the three types of Observable notifications?
142. What are `next`, `error`, and `complete`?
143. What does lazy execution mean?
144. How do you create an Observable?
145. What is `of()`?
146. What is `from()`?
147. What is `interval()`?
148. What is `timer()`?
149. What is `defer()`?
150. What are `EMPTY`, `NEVER`, and `throwError()`?
151. What is an Observable subscription?
152. What happens when you subscribe?
153. What happens when you unsubscribe?
154. What is an operator?
155. What is the `pipe()` function?

---

# 6. RxJS Transformation & Filtering

156. How does `map()` work?
157. RxJS `map()` vs JavaScript `map()`?
158. How does `filter()` work?
159. RxJS `filter()` vs JavaScript `filter()`?
160. What is `scan()`?
161. What is `reduce()`?
162. What is `tap()`?
163. When should `tap()` be used?
164. Why should business transformation generally not be done inside `tap()`?
165. What is `distinctUntilChanged()`?
166. What is `take()`?
167. What is `takeUntil()`?
168. What is `takeWhile()`?
169. What is `first()`?
170. What is `skip()`?

---

# 7. RxJS Higher-Order Mapping

171. What is a higher-order Observable?
172. What is `switchMap()`?
173. When should you use `switchMap()`?
174. What does cancellation mean in `switchMap()`?
175. What is `mergeMap()`?
176. When should you use `mergeMap()`?
177. What is `concatMap()`?
178. When should you use `concatMap()`?
179. What is `exhaustMap()`?
180. When should you use `exhaustMap()`?
181. `switchMap` vs `mergeMap`?
182. `mergeMap` vs `concatMap`?
183. `concatMap` vs `exhaustMap`?
184. `switchMap` vs `exhaustMap`?
185. When should you NOT use `switchMap()`?
186. Why can nested subscriptions be problematic?
187. How would you refactor nested subscriptions?

### Memorize this

```text
map       → transform
switchMap → latest
mergeMap  → parallel
concatMap → sequential
exhaustMap → ignore while busy
```

---

# 8. RxJS Combination Operators

188. What is `combineLatest()`?
189. When does `combineLatest()` emit?
190. What happens if one Observable hasn't emitted?
191. What is `forkJoin()`?
192. When does `forkJoin()` emit?
193. Why can `forkJoin()` fail to emit?
194. `forkJoin()` vs `combineLatest()`?
195. What is `zip()`?
196. `zip()` vs `combineLatest()`?
197. What is `withLatestFrom()`?
198. `withLatestFrom()` vs `combineLatest()`?
199. What is `merge()`?
200. What is `concat()`?

---

# 9. RxJS Subjects / Multicasting

201. Observable vs Subject?
202. What is a Subject?
203. What is a BehaviorSubject?
204. Subject vs BehaviorSubject?
205. What is ReplaySubject?
206. BehaviorSubject vs ReplaySubject?
207. What is AsyncSubject?
208. Subject vs BehaviorSubject vs ReplaySubject?
209. What does `asObservable()` do?
210. What is multicasting?
211. What are hot Observables?
212. What are cold Observables?
213. Give examples of hot and cold Observables.
214. How can a cold Observable be made shared?
215. What is `share()`?
216. What is `shareReplay()`?
217. How does `shareReplay()` help with HTTP caching?
218. What is `refCount`?

---

# 10. RxJS Error Handling

219. How do you handle errors in RxJS?
220. How does `catchError()` work?
221. What should `catchError()` return?
222. How do you rethrow an error?
223. What is `throwError()`?
224. What is `retry()`?
225. When should retry NOT be used?
226. What is `retryWhen()`?
227. What is `finalize()`?
228. Difference between `catchError()` and `finalize()`?
229. How do you implement API fallback data?
230. How do you handle HTTP errors globally in Angular?

---

# 11. RxJS Timing / Search

231. What is `debounceTime()`?
232. What is `throttleTime()`?
233. `debounceTime()` vs `throttleTime()`?
234. What is `auditTime()`?
235. How would you implement an autocomplete search?
236. Why is `switchMap()` commonly used with search?
237. How do you prevent duplicate searches?
238. How do you cancel an HTTP request when the user changes the search term?

---

# 12. Angular Fundamentals

239. What is Angular?
240. What is an SPA?
241. Angular vs React?
242. What are Angular's major building blocks?
243. How does Angular application bootstrapping work?
244. What happens when an Angular application starts?
245. What is a component?
246. What is a template?
247. What is metadata?
248. What is a selector?
249. What is a standalone component?
250. Standalone component vs NgModule?
251. Why were standalone APIs introduced?
252. What is Angular CLI?
253. What is `angular.json`?
254. What is `main.ts`?
255. What is `app.config.ts`?
256. What is the role of `bootstrapApplication()`?

---

# 13. Angular Templates & Binding

257. What is Angular template syntax?
258. What is interpolation?
259. What is property binding?
260. What is event binding?
261. What is two-way binding?
262. Explain `[(ngModel)]`.
263. What is one-way data flow?
264. What are template reference variables?
265. What is the `as` syntax in Angular templates?
266. What is optional chaining in Angular templates?
267. What is safe navigation?
268. What is the difference between `[property]` and `{{ }}`?
269. What is the difference between `(event)` and `[(...)]`?

---

# 14. Angular Components & Communication

270. How do you pass data from parent to child?
271. How do you pass data from child to parent?
272. How do sibling components communicate?
273. How do unrelated components communicate?
274. What is `@Input()`?
275. What is `@Output()`?
276. What is `EventEmitter`?
277. What are signal inputs?
278. What is `input()`?
279. What is `input.required()`?
280. What is `output()`?
281. What is `model()`?
282. What is two-way binding with `model()`?
283. What are input transforms?
284. How do you share state through a service?
285. When should you use a shared service vs NgRx?

---

# 15. Angular Lifecycle

286. What are Angular lifecycle hooks?
287. What is `ngOnChanges()`?
288. What is `ngOnInit()`?
289. What is `ngDoCheck()`?
290. What is `ngAfterContentInit()`?
291. What is `ngAfterContentChecked()`?
292. What is `ngAfterViewInit()`?
293. What is `ngAfterViewChecked()`?
294. What is `ngOnDestroy()`?
295. Constructor vs `ngOnInit()`?
296. When is `ngOnChanges()` called?
297. Why should heavy logic not be placed in lifecycle hooks unnecessarily?

---

# 16. Angular Dependency Injection

298. What is Dependency Injection?
299. Why does Angular use DI?
300. How does Angular DI work?
301. What is an Injector?
302. What is `providedIn: 'root'`?
303. What is the injector hierarchy?
304. What is the root injector?
305. What is an EnvironmentInjector?
306. What is an ElementInjector?
307. What happens when a service is provided at component level?
308. What happens when the same service is provided at root and component level?
309. What is `InjectionToken`?
310. What is `useClass`?
311. What is `useValue`?
312. What is `useFactory`?
313. What is `useExisting`?
314. What are `@Optional`, `@Self`, `@SkipSelf`, and `@Host`?
315. What is `inject()`?
316. Constructor injection vs `inject()`?

---

# 17. Angular Directives

317. What is a directive?
318. Component vs directive?
319. What is an attribute directive?
320. What is a structural directive?
321. What was `*ngIf` internally doing?
322. What was `*ngFor` internally doing?
323. What is the difference between structural and attribute directives?
324. How do you create a custom directive?
325. What are `ElementRef`, `Renderer2`, `TemplateRef`, and `ViewContainerRef`?
326. What is `HostListener`?
327. What is `HostBinding`?
328. What is the Directive Composition API?
329. Create a directive that changes the background color.
330. How would you make a reusable tooltip directive?

---

# 18. Angular Template Primitives

331. What is `ng-container`?
332. What is `ng-template`?
333. What is `ng-content`?
334. What is `ngTemplateOutlet`?
335. `ng-container` vs `ng-template`?
336. `ng-template` vs `ng-content`?
337. What is content projection?
338. What is multi-slot content projection?
339. What are `ContentChild` and `ContentChildren`?
340. `ViewChild` vs `ContentChild`?
341. `ViewChildren` vs `ContentChildren`?

---

# 19. ViewChild / Dynamic Components

342. What is `ViewChild`?
343. What is `ViewChildren`?
344. When are ViewChild queries available?
345. What are signal-based queries?
346. What is `viewChild()`?
347. What is `viewChildren()`?
348. What is `ViewContainerRef`?
349. How do you dynamically create a component?
350. How do you pass inputs to a dynamically created component?
351. How do you listen to outputs from a dynamic component?
352. What is `ComponentRef`?
353. What is `EnvironmentInjector` in dynamic component creation?

---

# 20. Angular Pipes

354. What is a pipe?
355. What are built-in pipes?
356. How do you create a custom pipe?
357. What is a pure pipe?
358. What is an impure pipe?
359. Pure vs impure pipe?
360. Why are impure pipes potentially expensive?
361. How does the AsyncPipe work?
362. Does AsyncPipe unsubscribe automatically?
363. What happens if an Observable used by AsyncPipe errors?
364. Why can AsyncPipe initially return `null`?
365. How do you handle errors when using AsyncPipe?

---

# 21. Angular Forms

366. What are Angular forms?
367. Template-driven vs reactive forms?
368. When should you use reactive forms?
369. What is `FormControl`?
370. What is `FormGroup`?
371. What is `FormArray`?
372. What is `FormBuilder`?
373. What are validators?
374. How do you create a custom validator?
375. What is an async validator?
376. How do you implement cross-field validation?
377. `setValue()` vs `patchValue()`?
378. What does `reset()` do?
379. What are `dirty`, `pristine`, `touched`, and `untouched`?
380. What are `valid`, `invalid`, and `pending`?
381. What are `valueChanges` and `statusChanges`?
382. How do you create dynamic forms?
383. How do you disable a form control?
384. How do you implement conditional validation?

---

# 22. ControlValueAccessor

385. What is ControlValueAccessor?
386. Why is ControlValueAccessor required?
387. What is `writeValue()`?
388. What is `registerOnChange()`?
389. What is `registerOnTouched()`?
390. What is `setDisabledState()`?
391. How do you create a custom form control?
392. How does Angular connect `FormControl` to a custom component?
393. How do you make a custom dropdown work with Reactive Forms?
394. ControlValueAccessor vs normal `@Input()`/`@Output()`?

---

# 23. Angular Routing

395. What is Angular Router?
396. How do you configure routes?
397. What is `router-outlet`?
398. What is `routerLink`?
399. What is `ActivatedRoute`?
400. What is `Router`?
401. What are route parameters?
402. What are query parameters?
403. What are fragments?
404. What are child routes?
405. What is lazy loading?
406. What is `loadComponent()`?
407. What is `loadChildren()`?
408. What is route-level dependency injection?
409. What are route guards?
410. What is `canActivate`?
411. What is `canActivateChild`?
412. What is `canDeactivate`?
413. What is `canMatch`?
414. `canMatch` vs `canActivate`?
415. What are route resolvers?
416. What is route data?
417. What are navigation events?
418. What are preloading strategies?
419. How would you protect an admin route?

---

# 24. Angular HTTP

420. How do you make an HTTP request?
421. What is `HttpClient`?
422. How do you make GET/POST/PUT/PATCH/DELETE requests?
423. How do you type an HTTP response?
424. How do you send query parameters?
425. How do you send HTTP headers?
426. What is `HttpContext`?
427. What is an HTTP interceptor?
428. Functional interceptor vs class interceptor?
429. How do you attach JWT to requests?
430. How do you handle global HTTP errors?
431. How do you implement a loading indicator?
432. How do you retry failed requests?
433. How do you implement request caching?
434. How do you upload a file?
435. How do you track upload/download progress?

---

# 25. Angular Authentication & Security

436. Authentication vs authorization?
437. What is JWT?
438. How does JWT authentication work?
439. Access token vs refresh token?
440. Where should tokens be stored?
441. What are HttpOnly cookies?
442. What is SameSite?
443. What is CORS?
444. What is CSRF?
445. What is XSS?
446. How does Angular protect against XSS?
447. What is Angular sanitization?
448. What is `DomSanitizer`?
449. Why can `innerHTML` be dangerous?
450. How do you implement RBAC?
451. Can Angular route guards secure an application?
452. Why must authorization also be implemented on the backend?

---

# 26. Angular Change Detection

453. What is change detection?
454. How does Angular change detection work?
455. What is the default change detection strategy?
456. What is `OnPush`?
457. Why does OnPush improve performance?
458. What triggers change detection for an OnPush component?
459. How do signals interact with change detection?
460. What is `ChangeDetectorRef`?
461. What does `markForCheck()` do?
462. What does `detectChanges()` do?
463. What do `detach()` and `reattach()` do?
464. What is `ExpressionChangedAfterItHasBeenCheckedError`?
465. Why should immutable updates be preferred?
466. Why can mutating an array cause problems with OnPush?
467. How would you optimize a component with thousands of rows?

---

# 27. Angular Signals

468. What are Signals?
469. Why were Signals introduced?
470. What is `signal()`?
471. What is `computed()`?
472. What is `effect()`?
473. `set()` vs `update()`?
474. What is a writable signal?
475. What is a readonly signal?
476. What is `asReadonly()`?
477. How does dependency tracking work?
478. What are signal inputs?
479. What are signal queries?
480. How do Signals affect change detection?
481. Signals vs RxJS?
482. Signals vs BehaviorSubject?
483. Signals vs NgRx?
484. When should you NOT use an effect?
485. How do you convert Observable → Signal?
486. How do you convert Signal → Observable?
487. What are `toSignal()` and `toObservable()`?

---

# 28. Angular Control Flow

488. What is the new Angular control flow?
489. What is `@if`?
490. What is `@else`?
491. What is `@for`?
492. What is `track`?
493. Why is `track` important?
494. What are `$index`, `$first`, `$last`, `$even`, and `$odd`?
495. What is `@empty`?
496. What is `@switch`?
497. What is `@case`?
498. What is `@default`?
499. New control flow vs `*ngIf`/`*ngFor`?

---

# 29. Angular `@defer`

500. What is `@defer`?
501. Why use deferrable views?
502. What is `@placeholder`?
503. What is `@loading`?
504. What is `@error`?
505. What is `on viewport`?
506. What is `on interaction`?
507. What is `on hover`?
508. What is `on idle`?
509. What is `on immediate`?
510. What is `when`?
511. What is prefetching with `@defer`?
512. How does `@defer` affect bundle size?
513. When should you NOT use `@defer`?

---

# 30. Angular Zone / Rendering

514. What is Zone.js?
515. Why did Angular use Zone.js?
516. What is `NgZone`?
517. How does Zone.js trigger Angular change detection?
518. What is `runOutsideAngular()`?
519. When would you use `runOutsideAngular()`?
520. What is zoneless Angular?
521. Signals vs Zone.js?
522. How does modern Angular reduce unnecessary change detection?
523. What is the Angular rendering pipeline?

---

# 31. Angular Performance

524. How do you optimize an Angular application?
525. How does OnPush improve performance?
526. How do Signals improve rendering efficiency?
527. How does lazy loading improve performance?
528. How does `@defer` improve initial loading?
529. Why should you avoid functions in templates?
530. What are pure pipes?
531. What is memoization?
532. How do you optimize large lists?
533. What is virtual scrolling?
534. Why is `track` important?
535. How do you reduce bundle size?
536. What is tree shaking?
537. What is code splitting?
538. How do you optimize images?
539. How do you identify Angular performance bottlenecks?
540. How do Angular DevTools help?
541. What are Core Web Vitals?
542. When would you use Web Workers?
543. When would you use SSR for performance?

---

# 32. Angular SSR / Hydration

544. What is SSR?
545. SSR vs CSR?
546. SSR vs SSG?
547. What are the benefits of SSR?
548. What are the disadvantages of SSR?
549. What is hydration?
550. What is event replay?
551. What happens when server and browser environments differ?
552. How do you handle `window`/`document` in SSR?
553. How does SSR affect SEO?
554. When should you avoid SSR?

---

# 33. Angular Testing

555. How do you test Angular applications?
556. What is TestBed?
557. What is ComponentFixture?
558. What is DebugElement?
559. How do you test a component?
560. How do you test a service?
561. How do you test a pipe?
562. How do you test a directive?
563. How do you mock a service?
564. What are spies?
565. What is `fakeAsync()`?
566. What is `tick()`?
567. How do you test HTTP calls?
568. How do you test routing?
569. How do you test asynchronous Observables?
570. What should be unit tested vs integration tested?

---

# 34. NgRx

571. What is NgRx?
572. Why use NgRx?
573. When should you NOT use NgRx?
574. What is Store?
575. What is an Action?
576. What is a Reducer?
577. What is a Selector?
578. What is an Effect?
579. What is Feature Store?
580. What is NgRx Entity?
581. What is selector memoization?
582. Why should reducers be pure?
583. What belongs in a reducer?
584. What belongs in an effect?
585. Why shouldn't API calls happen inside reducers?
586. How does NgRx handle API calls?
587. How do you handle errors in Effects?
588. What is optimistic update?
589. What is pessimistic update?
590. What is a Facade?
591. NgRx vs BehaviorSubject?
592. NgRx vs Signals?
593. NgRx vs service-based state?
594. How would you structure NgRx in a large application?

---

# 35. Angular Architecture

595. How would you structure a large Angular application?
596. Feature-based vs layer-based architecture?
597. What belongs in Core?
598. What belongs in Shared?
599. What belongs in a Feature?
600. Smart vs presentational components?
601. Container vs presentational components?
602. What is the Facade pattern?
603. What is the Repository pattern?
604. How should services be structured?
605. Where should API calls live?
606. Where should business logic live?
607. Where should state live?
608. How do you prevent components from becoming too large?
609. How do you define feature boundaries?
610. How do you create reusable UI components?
611. How do you build an enterprise Angular component library?
612. How do you handle cross-feature dependencies?
613. How do you architect authentication?
614. How do you architect authorization?
615. How do you architect global error handling?
616. How do you architect application configuration?

---

# 36. Dynamic / Plugin Architecture

617. How do you dynamically load Angular components?
618. How does `ViewContainerRef` work?
619. How would you implement a plugin system?
620. How would you render a UI dynamically from JSON metadata?
621. How would you map metadata to Angular components?
622. How would you safely render configurable components?
623. How would you pass inputs to dynamically created components?
624. How would you handle dynamic component events?
625. How would you isolate plugin failures?

This section is especially useful for **low-code/platform architecture interviews**.

---

# 37. Micro Frontends

626. What is a microfrontend?
627. Why use microfrontends?
628. What are the disadvantages?
629. What is Module Federation?
630. What is a host?
631. What is a remote?
632. How are remote modules loaded?
633. How do shared dependencies work?
634. How do you share authentication?
635. How do microfrontends communicate?
636. How do you share state?
637. Should microfrontends share a global store?
638. How do you handle routing?
639. How do you handle version mismatches?
640. How do you independently deploy microfrontends?
641. How do you handle failures in a remote?
642. Microfrontend vs monolith?
643. Microfrontend vs modular monolith?
644. When should you NOT use microfrontends?

---

# 38. Browser Internals

645. How does a browser render a webpage?
646. What is the DOM?
647. What is CSSOM?
648. What is the Render Tree?
649. What is layout/reflow?
650. What is repaint?
651. What is compositing?
652. Reflow vs repaint?
653. What is the Critical Rendering Path?
654. What is `requestAnimationFrame()`?
655. Main thread vs Web Worker?
656. What blocks the main thread?
657. How does JavaScript interact with browser rendering?
658. How does the Event Loop interact with rendering?

---

# 39. Web Fundamentals

659. What happens when you enter a URL into a browser?
660. What is HTTP?
661. What is HTTPS?
662. HTTP vs HTTPS?
663. What are HTTP methods?
664. GET vs POST?
665. PUT vs PATCH?
666. What are HTTP status codes?
667. 401 vs 403?
668. 400 vs 422?
669. 500 vs 503?
670. What are HTTP headers?
671. What are cookies?
672. localStorage vs sessionStorage?
673. localStorage vs IndexedDB?
674. What is Service Worker?
675. What is Cache API?
676. What is WebSocket?
677. WebSocket vs SSE?
678. What is CDN?
679. What is browser caching?
680. What is ETag?
681. What is cache-control?

---

# 40. Offline-First / IndexedDB

682. What is IndexedDB?
683. IndexedDB vs localStorage?
684. How does IndexedDB work?
685. What are object stores?
686. What are indexes?
687. What are transactions?
688. How would you design offline-first Angular architecture?
689. How would you synchronize offline data with a backend?
690. How would you handle conflict resolution?
691. What is optimistic synchronization?
692. What are Service Workers used for?
693. How would you cache API responses?
694. How would you handle stale data?

---

# 41. API / Backend Integration

695. How should Angular communicate with a REST API?
696. How would you implement pagination?
697. How would you implement server-side filtering?
698. How would you implement sorting?
699. How would you implement search?
700. How would you debounce search requests?
701. How would you cache API responses?
702. How would you retry failed requests?
703. How would you handle API timeouts?
704. How would you handle partial API failure?
705. What is idempotency?
706. What is API versioning?
707. How should frontend and backend handle errors consistently?
708. How would you design an API response model?

---

# 42. System Design / Principal-Level Angular

709. Design an enterprise Angular application for 5M+ users.
710. Design a scalable Angular dashboard.
711. Design a configurable low-code platform.
712. Design a metadata-driven UI framework.
713. Design a dynamic form builder.
714. Design a role/permission management system.
715. Design a notification system.
716. Design an offline-first application.
717. Design a large reporting application.
718. Design a multi-tenant Angular application.
719. Design a microfrontend platform.
720. Design frontend authentication architecture.
721. Design frontend authorization/RBAC.
722. Design a frontend caching strategy.
723. Design a global error-handling architecture.
724. Design a frontend observability strategy.
725. How would you reduce the initial bundle size of a huge Angular application?
726. How would you migrate a large NgModule application to standalone?
727. How would you migrate an older Angular application to modern Angular?
728. How would you decide between Signals, RxJS and NgRx?
729. How would you divide responsibilities between components, services and state?
730. How would you handle millions of records in a UI?
731. How would you design frontend architecture for independent team ownership?
732. How would you decide whether to use microfrontends?

---

# 43. Design Patterns

733. What is the Singleton pattern?
734. What is Factory?
735. What is Strategy?
736. What is Adapter?
737. What is Repository?
738. What is Facade?
739. What is Observer?
740. What is Dependency Inversion?
741. How are design patterns used in Angular?
742. Which Angular features naturally implement the Observer pattern?
743. How does Dependency Injection support SOLID?
744. What is the Single Responsibility Principle?
745. What is Open/Closed Principle?
746. What is Liskov Substitution?
747. What is Interface Segregation?
748. What is Dependency Inversion?

---

# 44. DSA / Coding

749. What is Big O notation?
750. Solve Two Sum.
751. Find duplicate elements.
752. Find the first non-repeating character.
753. Reverse a string.
754. Check whether a string is a palindrome.
755. Find the largest/smallest element.
756. Find the second-largest element.
757. Remove duplicates from an array.
758. Merge two sorted arrays.
759. Binary search.
760. Implement debounce.
761. Implement throttle.
762. Implement `map()`.
763. Implement `filter()`.
764. Implement `reduce()`.
765. Flatten a nested array.
766. Group objects by property.
767. Implement a simple Observable.
768. Implement a simple EventEmitter.
769. Implement memoization.
770. Implement a cache with expiration.

---

# 45. Most Important Questions for Your Target Role

You now have a **770-question bank**, but you absolutely should **not try to memorize all 770 equally**.

For your Senior/Principal Angular preparation, I'd mark these as the core:

### 🔥 Tier 1

```text
JavaScript
├── Closure
├── this
├── Prototype
├── Event Loop
├── Microtask/Macrotask
└── Promise

TypeScript
├── Interface vs Type
├── Generics
├── Utility Types
├── Union/Intersection
├── Type Guards
├── Narrowing
└── Conditional/Mapped Types

RxJS
├── Observable
├── Subject
├── BehaviorSubject
├── Hot/Cold
├── map
├── switchMap
├── mergeMap
├── concatMap
├── exhaustMap
├── forkJoin
├── combineLatest
├── withLatestFrom
├── shareReplay
├── catchError
└── Subscription Management
```

### 🔥 Tier 2

```text
Angular
├── Standalone
├── Components
├── Input/Output
├── DI
├── Lifecycle
├── Change Detection
├── OnPush
├── Signals
├── RxJS + Signals
├── Forms
├── ControlValueAccessor
├── Routing
├── Guards
├── HTTP
├── Interceptors
├── Directives
├── Pipes
├── Dynamic Components
├── Control Flow
└── @defer
```

### 🔥 Tier 3 — Senior/Principal

```text
Architecture
├── Enterprise Angular Architecture
├── State Architecture
├── NgRx Architecture
├── Performance
├── SSR/Hydration
├── Security
├── Testing
├── Microfrontends
├── Module Federation
├── Offline-first
├── API Architecture
└── System Design
```

### One important distinction

The **770 questions are your question bank**.

Your actual preparation should have three layers:

```text
QUESTION
   ↓
CONCEPT
   ↓
CODE
   ↓
REAL-WORLD SCENARIO
   ↓
ARCHITECTURAL TRADE-OFF
```

For example, don't prepare only:

> "What is `switchMap()`?"

Prepare:

> What is `switchMap()` → how does cancellation work → implement autocomplete → compare with `mergeMap()` → what happens to the HTTP request → when would you choose another operator → how would this fit into an enterprise Angular search feature?

That approach will prepare you much better for **L1/L2 and Principal-level interviews** than simply completing a large question list.
