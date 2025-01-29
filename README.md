# Awesome Mixin!!

Collection of various libraries that help [SpongePowered Mixin](https://github.com/SpongePowered/Mixin) do more.

## [MixinConstraints](https://github.com/Moulberry/MixinConstraints)

### Sugar
- `@IfModLoaded` - Checks if a mod is loaded
- `@IfModAbsent` - Checks if a mod is absent
- `@IfMinecraftVersion` - Checks if the Minecraft version matches a range
- `@IfDevEnvironment` - Checks if the game is running inside a development environment

## [MixinExtras](https://github.com/LlamaLad7/MixinExtras)

### Injectors
- [`@ModifyExpressionValue`](https://github.com/LlamaLad7/MixinExtras/wiki/ModifyExpressionValue) - Allows tweaking the resultant value of a method call, field get, constant, or new object instantiation
- [`@ModifyReceiver`](https://github.com/LlamaLad7/MixinExtras/wiki/ModifyReceiver) - Allows modifying the receiver of a non-static method call or field get/set
- [`@ModifyReturnValue`](https://github.com/LlamaLad7/MixinExtras/wiki/ModifyReturnValue) - Allows tweaking the value being returned from a method
- [`@WrapMethod`](https://github.com/LlamaLad7/MixinExtras/wiki/WrapMethod) - Allows wrapping a whole method
- [`@WrapOperation`](https://github.com/LlamaLad7/MixinExtras/wiki/WrapOperation) - Allows wrapping a method call, field get/set, `instanceof` check, or object instantiation
- [`@WrapWithCondition`](https://github.com/LlamaLad7/MixinExtras/wiki/WrapWithCondition) - Allows wrapping a field write or void method call with a conditional check

### Sugar
- [`@Cancellable`](https://github.com/LlamaLad7/MixinExtras/wiki/Cancellable) - Allows receiving a cancellable `CallbackInfo` or `CallbackInfoReturnable` as appropriate from any kind of injector, instead of only `@Inject`
- [`@Local`](https://github.com/LlamaLad7/MixinExtras/wiki/Local) - Allows capturing local variables wherever you need them
- [`@Share`](https://github.com/LlamaLad7/MixinExtras/wiki/Share) - Allows sharing values between handler methods in the same target method
- [`@Expression`](https://github.com/LlamaLad7/MixinExtras/wiki/Expressions) (beta) - Allows using Java-like strings to target complex pieces of bytecode

## [MixinSquared](https://github.com/Bawnorton/MixinSquared)

### Sugar
- [`@TargetHandler`](https://github.com/Bawnorton/MixinSquared/wiki) - Allows any injector to target the handler of another (previously applied) injector

### Misc
- [`MixinAnnotationAdjuster`](https://github.com/Bawnorton/MixinSquared/wiki/Mixin-Annotation-Adjuster) - Allows manipulation of the annotations used in mixins that would normally be out of a user's control
- [`MixinCanceller`](https://github.com/Bawnorton/MixinSquared/wiki/Mixin-Canceller) - Allows canceling the application of Mixins that would normally be out of a user's control

## [Lib39 (Core)](https://git.sleeping.town/unascribed-mods/Lib39)

### Sugar
- [`@AutoMixinEligible`](https://git.sleeping.town/unascribed-mods/Lib39/src/branch/1.20.1/src/main/java/com/unascribed/lib39/core/mixinsupport/AutoMixinEligible.java) - Allows loading mixins via AutoMixin (see below) conditionally - implements checks for loaded mods, system properties, config values, and environment type

### Misc
- [`AutoMixin`](https://git.sleeping.town/unascribed-mods/Lib39/wiki/Core#automixin) - Pre-implemented `IMixinConfigPlugin` that discovers mixins in your mod jar automatically
