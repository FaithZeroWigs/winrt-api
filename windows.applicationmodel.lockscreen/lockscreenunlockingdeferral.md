---
-api-id: T:Windows.ApplicationModel.LockScreen.LockScreenUnlockingDeferral
-api-type: winrt class
---

<!-- Class syntax.
public class LockScreenUnlockingDeferral : Windows.ApplicationModel.LockScreen.ILockScreenUnlockingDeferral
-->

# Windows.ApplicationModel.LockScreen.LockScreenUnlockingDeferral

## -description
Represents an unlock deferral.
To show an unlock animation, your lock screen app must:

+ Register to be notified of unlocking via the [Unlocking](lockapplicationhost_unlocking.md) event.
+ In the Unlocking event handler, call [GetDeferral](lockscreenunlockingeventargs_getdeferral.md).
+ Kick off an animation.+ When that animation completes, call [Complete](lockscreenunlockingdeferral_complete.md) on the deferral to end the deferral.
+ Note: If the animation takes too long, your lock screen app will be terminated by the system and potentially removed as the user’s default lock app.



## -remarks


## -examples

## -see-also
