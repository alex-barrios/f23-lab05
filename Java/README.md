Which is more dependent on the implementation details of the SortedIntList, delegation or inheritance?
Inheritance because it is tightly coupled with the SortedIntList class by inheriting its implemenation details, while delagation does not inherit its implemenation.

If the add method in SortedIntList is significantly modified or its behavior changes, which implementation is more likely to break?
The delegation implemenation because it uses the implemenation of SortedIntList.

What issues does using delegation solve that might have been problematic with inheritance?
- Tight coupling -- delegation reduces coupling
- Limited code reuse -- delegation allows you to be selective with code reuse
- Information hiding -- delegation has more control over what's exposed


Based on the provided implementations, when would it be more appropriate to use inheritance and when to use delegation?
It would be more appropriate to use inheritance if we just want to overide certain methods. It would be more appropriate to use delegation if when we want to inherit the interface.
