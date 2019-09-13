# -fetch

1. event returnValue
    L: event.returnValue //true

2. event bubbles
    L: event.bubbles //true

3. event cancelBubble
    L: event.cancelBubble //false

4. event cancelable
    L: event.cancelable //false

5. event composed
    L: event.composed //false

6. event currentTarget
    L: event.currentTarget //#Document

7. event defaultPrevented
    L: event.defaultPrevented //false

8. event eventPhase
    L: event.eventPhase //2

9. event isTrusted
    L: event.isTrusted //true

10. event path
    L: event.path[0] //Document

11. event path
    L: event.path[1] //Window

12. event path
    L: event.path[0].activeElement //<body></body>

13. event path
    L: event.path[1].alert //ƒ alert() { [native code] }

14. event returnValue
    L: event.path[1].blur //ƒ () { [native code] }

15. event returnValue
    L: event.path[1].caches //CacheStorage {}

16. event returnValue
    L: event.path[1].cancelAnimationFrame //ƒ cancelAnimationFrame() { [native code] }

17. event returnValue
    L: event.path[1].cancelIdleCallback //ƒ cancelIdleCallback() { [native code] }

18. event type
    L: event.type //DOMContentLoaded

19. event target Body
    L: event.target.body //<body></body>

20. event returnValue
    L: event.returnValue //true
