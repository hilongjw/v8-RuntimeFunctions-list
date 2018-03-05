# V8 RuntimeFunctions List

## Usage

```bash
node --allow-natives-syntax

v8 --allow-natives-syntax
```

```bash
%GetHeapUsage()
5335344
%CollectGarbage(1)
undefined
%GetHeapUsage()
5353008
```

## Source

[https://github.com/v8/v8/blob/master/src/runtime/runtime.h](https://github.com/v8/v8/blob/master/src/runtime/runtime.h)

## List

```

%TransitionElementsKind
number of arguments: 2
number of values: 1


%RemoveArrayHoles
number of arguments: 2
number of values: 1


%MoveArrayContents
number of arguments: 2
number of values: 1


%EstimateNumberOfElements
number of arguments: 1
number of values: 1


%GetArrayKeys
number of arguments: 2
number of values: 1


%TrySliceSimpleNonFastElements
number of arguments: 3
number of values: 1


%NewArray
number of arguments: -1 /* >= 3 */
number of values: 1


%NormalizeElements
number of arguments: 1
number of values: 1


%GrowArrayElements
number of arguments: 2
number of values: 1


%HasComplexElements
number of arguments: 1
number of values: 1


%IsArray
number of arguments: 1
number of values: 1


%ArrayIsArray
number of arguments: 1
number of values: 1


%ArraySpeciesConstructor
number of arguments: 1
number of values: 1


%ArrayIncludes_Slow
number of arguments: 3
number of values: 1


%ArrayIndexOf
number of arguments: 3
number of values: 1


%AtomicsExchange
number of arguments: 3
number of values: 1


%AtomicsCompareExchange
number of arguments: 4
number of values: 1


%AtomicsAdd
number of arguments: 3
number of values: 1


%AtomicsSub
number of arguments: 3
number of values: 1


%AtomicsAnd
number of arguments: 3
number of values: 1


%AtomicsOr
number of arguments: 3
number of values: 1


%AtomicsXor
number of arguments: 3
number of values: 1


%AtomicsNumWaitersForTesting
number of arguments: 2
number of values: 1


%SetAllowAtomicsWait
number of arguments: 1
number of values: 1


%BigIntBinaryOp
number of arguments: 3
number of values: 1


%BigIntCompareToBigInt
number of arguments: 3
number of values: 1


%BigIntCompareToNumber
number of arguments: 3
number of values: 1


%BigIntEqualToBigInt
number of arguments: 2
number of values: 1


%BigIntEqualToNumber
number of arguments: 2
number of values: 1


%BigIntEqualToString
number of arguments: 2
number of values: 1


%BigIntToBoolean
number of arguments: 1
number of values: 1


%BigIntToNumber
number of arguments: 1
number of values: 1


%BigIntUnaryOp
number of arguments: 2
number of values: 1


%ToBigInt
number of arguments: 1
number of values: 1


%ThrowUnsupportedSuperError
number of arguments: 0
number of values: 1


%ThrowConstructorNonCallableError
number of arguments: 1
number of values: 1


%ThrowStaticPrototypeError
number of arguments: 0
number of values: 1


%ThrowSuperAlreadyCalledError
number of arguments: 0
number of values: 1


%ThrowSuperNotCalled
number of arguments: 0
number of values: 1


%ThrowNotSuperConstructor
number of arguments: 2
number of values: 1


%HomeObjectSymbol
number of arguments: 0
number of values: 1


%DefineClass
number of arguments: -1 /* >= 3 */
number of values: 1


%LoadFromSuper
number of arguments: 3
number of values: 1


%LoadKeyedFromSuper
number of arguments: 3
number of values: 1


%StoreToSuper_Strict
number of arguments: 4
number of values: 1


%StoreToSuper_Sloppy
number of arguments: 4
number of values: 1


%StoreKeyedToSuper_Strict
number of arguments: 4
number of values: 1


%StoreKeyedToSuper_Sloppy
number of arguments: 4
number of values: 1


%GetSuperConstructor
number of arguments: 1
number of values: 1


%TheHole
number of arguments: 0
number of values: 1


%SetGrow
number of arguments: 1
number of values: 1


%SetShrink
number of arguments: 1
number of values: 1


%SetIteratorClone
number of arguments: 1
number of values: 1


%MapShrink
number of arguments: 1
number of values: 1


%MapGrow
number of arguments: 1
number of values: 1


%MapIteratorClone
number of arguments: 1
number of values: 1


%GetWeakMapEntries
number of arguments: 2
number of values: 1


%WeakCollectionDelete
number of arguments: 3
number of values: 1


%WeakCollectionSet
number of arguments: 4
number of values: 1


%GetWeakSetValues
number of arguments: 2
number of values: 1


%IsJSMap
number of arguments: 1
number of values: 1


%IsJSSet
number of arguments: 1
number of values: 1


%IsJSWeakMap
number of arguments: 1
number of values: 1


%IsJSWeakSet
number of arguments: 1
number of values: 1


%CompileLazy
number of arguments: 1
number of values: 1


%CompileOptimized_Concurrent
number of arguments: 1
number of values: 1


%FunctionFirstExecution
number of arguments: 1
number of values: 1


%CompileOptimized_NotConcurrent
number of arguments: 1
number of values: 1


%EvictOptimizedCodeSlot
number of arguments: 1
number of values: 1


%NotifyDeoptimized
number of arguments: 0
number of values: 1


%CompileForOnStackReplacement
number of arguments: 1
number of values: 1


%ResolvePossiblyDirectEval
number of arguments: 6
number of values: 1


%InstantiateAsmJs
number of arguments: 4
number of values: 1


%IsDate
number of arguments: 1
number of values: 1


%DateCurrentTime
number of arguments: 0
number of values: 1


%HandleDebuggerStatement
number of arguments: 0
number of values: 1


%ScheduleBreak
number of arguments: 0
number of values: 1


%DebugGetInternalProperties
number of arguments: 1
number of values: 1


%DebugGetPropertyDetails
number of arguments: 2
number of values: 1


%DebugGetProperty
number of arguments: 2
number of values: 1


%DebugPropertyKindFromDetails
number of arguments: 1
number of values: 1


%DebugPropertyAttributesFromDetails
number of arguments: 1
number of values: 1


%CheckExecutionState
number of arguments: 1
number of values: 1


%GetFrameCount
number of arguments: 1
number of values: 1


%GetFrameDetails
number of arguments: 2
number of values: 1


%GetScopeCount
number of arguments: 2
number of values: 1


%GetScopeDetails
number of arguments: 4
number of values: 1


%GetAllScopesDetails
number of arguments: 4
number of values: 1


%GetFunctionScopeCount
number of arguments: 1
number of values: 1


%GetFunctionScopeDetails
number of arguments: 2
number of values: 1


%GetGeneratorScopeCount
number of arguments: 1
number of values: 1


%GetGeneratorScopeDetails
number of arguments: 2
number of values: 1


%SetScopeVariableValue
number of arguments: 6
number of values: 1


%GetBreakLocations
number of arguments: 1
number of values: 1


%ChangeBreakOnException
number of arguments: 2
number of values: 1


%IsBreakOnException
number of arguments: 1
number of values: 1


%PrepareStep
number of arguments: 2
number of values: 1


%ClearStepping
number of arguments: 0
number of values: 1


%DebugEvaluate
number of arguments: 5
number of values: 1


%DebugEvaluateGlobal
number of arguments: 2
number of values: 1


%DebugGetLoadedScripts
number of arguments: 0
number of values: 1


%DebugReferencedBy
number of arguments: 3
number of values: 1


%DebugConstructedBy
number of arguments: 2
number of values: 1


%DebugGetPrototype
number of arguments: 1
number of values: 1


%DebugSetScriptSource
number of arguments: 2
number of values: 1


%FunctionGetInferredName
number of arguments: 1
number of values: 1


%FunctionGetDebugName
number of arguments: 1
number of values: 1


%GetDebugContext
number of arguments: 0
number of values: 1


%CollectGarbage
number of arguments: 1
number of values: 1


%GetHeapUsage
number of arguments: 0
number of values: 1


%GetScript
number of arguments: 1
number of values: 1


%ScriptLineCount
number of arguments: 1
number of values: 1


%ScriptLocationFromLine
number of arguments: 4
number of values: 1


%ScriptLocationFromLine2
number of arguments: 4
number of values: 1


%ScriptPositionInfo
number of arguments: 3
number of values: 1


%ScriptPositionInfo2
number of arguments: 3
number of values: 1


%DebugOnFunctionCall
number of arguments: 1
number of values: 1


%DebugPrepareStepInSuspendedGenerator
number of arguments: 0
number of values: 1


%DebugPushPromise
number of arguments: 1
number of values: 1


%DebugPopPromise
number of arguments: 0
number of values: 1


%DebugAsyncFunctionPromiseCreated
number of arguments: 1
number of values: 1


%DebugIsActive
number of arguments: 0
number of values: 1


%DebugCollectCoverage
number of arguments: 0
number of values: 1


%DebugTogglePreciseCoverage
number of arguments: 1
number of values: 1


%DebugToggleBlockCoverage
number of arguments: 1
number of values: 1


%IncBlockCounter
number of arguments: 2
number of values: 1


%ErrorToString
number of arguments: 1
number of values: 1


%ForInEnumerate
number of arguments: 1
number of values: 1


%ForInHasProperty
number of arguments: 2
number of values: 1


%InterpreterTraceBytecodeEntry
number of arguments: 3
number of values: 1


%InterpreterTraceBytecodeExit
number of arguments: 3
number of values: 1


%InterpreterTraceUpdateFeedback
number of arguments: 3
number of values: 1


%InterpreterDeserializeLazy
number of arguments: 2
number of values: 1


%FunctionGetName
number of arguments: 1
number of values: 1


%FunctionGetScript
number of arguments: 1
number of values: 1


%FunctionGetScriptId
number of arguments: 1
number of values: 1


%FunctionGetSourceCode
number of arguments: 1
number of values: 1


%FunctionGetScriptSourcePosition
number of arguments: 1
number of values: 1


%FunctionGetContextData
number of arguments: 1
number of values: 1


%FunctionIsAPIFunction
number of arguments: 1
number of values: 1


%SetCode
number of arguments: 2
number of values: 1


%SetNativeFlag
number of arguments: 1
number of values: 1


%IsConstructor
number of arguments: 1
number of values: 1


%Call
number of arguments: -1 /* >= 2 */
number of values: 1


%IsFunction
number of arguments: 1
number of values: 1


%FunctionToString
number of arguments: 1
number of values: 1


%CreateJSGeneratorObject
number of arguments: 2
number of values: 1


%GeneratorClose
number of arguments: 1
number of values: 1


%GeneratorGetFunction
number of arguments: 1
number of values: 1


%GeneratorGetReceiver
number of arguments: 1
number of values: 1


%GeneratorGetInputOrDebugPos
number of arguments: 1
number of values: 1


%AsyncFunctionAwaitCaught
number of arguments: 3
number of values: 1


%AsyncFunctionAwaitUncaught
number of arguments: 3
number of values: 1


%AsyncGeneratorResolve
number of arguments: 3
number of values: 1


%AsyncGeneratorReject
number of arguments: 2
number of values: 1


%AsyncGeneratorYield
number of arguments: 3
number of values: 1


%AsyncGeneratorAwaitCaught
number of arguments: 2
number of values: 1


%AsyncGeneratorAwaitUncaught
number of arguments: 2
number of values: 1


%GeneratorGetContinuation
number of arguments: 1
number of values: 1


%GeneratorGetSourcePosition
number of arguments: 1
number of values: 1


%GeneratorGetResumeMode
number of arguments: 1
number of values: 1


%AsyncGeneratorHasCatchHandlerForPC
number of arguments: 1
number of values: 1


%CanonicalizeLanguageTag
number of arguments: 1
number of values: 1


%AvailableLocalesOf
number of arguments: 1
number of values: 1


%GetDefaultICULocale
number of arguments: 0
number of values: 1


%IsInitializedIntlObject
number of arguments: 1
number of values: 1


%IsInitializedIntlObjectOfType
number of arguments: 2
number of values: 1


%MarkAsInitializedIntlObjectOfType
number of arguments: 2
number of values: 1


%CreateDateTimeFormat
number of arguments: 3
number of values: 1


%InternalDateFormat
number of arguments: 2
number of values: 1


%InternalDateFormatToParts
number of arguments: 2
number of values: 1


%CreateNumberFormat
number of arguments: 3
number of values: 1


%InternalNumberFormat
number of arguments: 2
number of values: 1


%CurrencyDigits
number of arguments: 1
number of values: 1


%CreateCollator
number of arguments: 3
number of values: 1


%InternalCompare
number of arguments: 3
number of values: 1


%CreatePluralRules
number of arguments: 3
number of values: 1


%PluralRulesSelect
number of arguments: 2
number of values: 1


%CreateBreakIterator
number of arguments: 3
number of values: 1


%BreakIteratorAdoptText
number of arguments: 2
number of values: 1


%BreakIteratorFirst
number of arguments: 1
number of values: 1


%BreakIteratorNext
number of arguments: 1
number of values: 1


%BreakIteratorCurrent
number of arguments: 1
number of values: 1


%BreakIteratorBreakType
number of arguments: 1
number of values: 1


%StringToLowerCaseIntl
number of arguments: 1
number of values: 1


%StringToUpperCaseIntl
number of arguments: 1
number of values: 1


%StringLocaleConvertCase
number of arguments: 3
number of values: 1


%DateCacheVersion
number of arguments: 0
number of values: 1


%AllocateInNewSpace
number of arguments: 1
number of values: 1


%AllocateInTargetSpace
number of arguments: 2
number of values: 1


%AllocateSeqOneByteString
number of arguments: 1
number of values: 1


%AllocateSeqTwoByteString
number of arguments: 1
number of values: 1


%CheckIsBootstrapping
number of arguments: 0
number of values: 1


%CreateAsyncFromSyncIterator
number of arguments: 1
number of values: 1


%CreateListFromArrayLike
number of arguments: 1
number of values: 1


%DeserializeLazy
number of arguments: 1
number of values: 1


%GetAndResetRuntimeCallStats
number of arguments: -1 /* <= 2 */
number of values: 1


%ExportFromRuntime
number of arguments: 1
number of values: 1


%IncrementUseCounter
number of arguments: 1
number of values: 1


%IncrementUseCounterConstructorReturnNonUndefinedPrimitive
number of arguments: 0
number of values: 1


%InstallToContext
number of arguments: 1
number of values: 1


%Interrupt
number of arguments: 0
number of values: 1


%IS_VAR
number of arguments: 1
number of values: 1


%NewReferenceError
number of arguments: 2
number of values: 1


%NewSyntaxError
number of arguments: 2
number of values: 1


%NewTypeError
number of arguments: 2
number of values: 1


%OrdinaryHasInstance
number of arguments: 2
number of values: 1


%PromoteScheduledException
number of arguments: 0
number of values: 1


%ReThrow
number of arguments: 1
number of values: 1


%RunMicrotasks
number of arguments: 0
number of values: 1


%RunMicrotaskCallback
number of arguments: 2
number of values: 1


%StackGuard
number of arguments: 0
number of values: 1


%Throw
number of arguments: 1
number of values: 1


%ThrowApplyNonFunction
number of arguments: 1
number of values: 1


%ThrowCalledNonCallable
number of arguments: 1
number of values: 1


%ThrowConstructedNonConstructable
number of arguments: 1
number of values: 1


%ThrowConstructorReturnedNonObject
number of arguments: 0
number of values: 1


%ThrowInvalidStringLength
number of arguments: 0
number of values: 1


%ThrowInvalidTypedArrayAlignment
number of arguments: 2
number of values: 1


%ThrowIteratorResultNotAnObject
number of arguments: 1
number of values: 1


%ThrowThrowMethodMissing
number of arguments: 0
number of values: 1


%ThrowSymbolIteratorInvalid
number of arguments: 0
number of values: 1


%ThrowNotConstructor
number of arguments: 1
number of values: 1


%ThrowRangeError
number of arguments: -1 /* >= 1 */
number of values: 1


%ThrowReferenceError
number of arguments: 1
number of values: 1


%ThrowStackOverflow
number of arguments: 0
number of values: 1


%ThrowSymbolAsyncIteratorInvalid
number of arguments: 0
number of values: 1


%ThrowTypeError
number of arguments: -1 /* >= 1 */
number of values: 1


%Typeof
number of arguments: 1
number of values: 1


%UnwindAndFindExceptionHandler
number of arguments: 0
number of values: 1


%AllowDynamicFunction
number of arguments: 1
number of values: 1


%CreateTemplateObject
number of arguments: 1
number of values: 1


%ReportMessage
number of arguments: 1
number of values: 1


%CreateRegExpLiteral
number of arguments: 4
number of values: 1


%CreateObjectLiteral
number of arguments: 4
number of values: 1


%CreateArrayLiteral
number of arguments: 4
number of values: 1


%LiveEditFindSharedFunctionInfosForScript
number of arguments: 1
number of values: 1


%LiveEditGatherCompileInfo
number of arguments: 2
number of values: 1


%LiveEditReplaceScript
number of arguments: 3
number of values: 1


%LiveEditFunctionSourceUpdated
number of arguments: 2
number of values: 1


%LiveEditReplaceFunctionCode
number of arguments: 2
number of values: 1


%LiveEditFixupScript
number of arguments: 2
number of values: 1


%LiveEditFunctionSetScript
number of arguments: 2
number of values: 1


%LiveEditReplaceRefToNestedFunction
number of arguments: 3
number of values: 1


%LiveEditPatchFunctionPositions
number of arguments: 2
number of values: 1


%LiveEditCheckAndDropActivations
number of arguments: 3
number of values: 1


%LiveEditCompareStrings
number of arguments: 2
number of values: 1


%LiveEditRestartFrame
number of arguments: 2
number of values: 1


%GenerateRandomNumbers
number of arguments: 0
number of values: 1


%DynamicImportCall
number of arguments: 2
number of values: 1


%GetImportMetaObject
number of arguments: 0
number of values: 1


%GetModuleNamespace
number of arguments: 1
number of values: 1


%IsValidSmi
number of arguments: 1
number of values: 1


%StringToNumber
number of arguments: 1
number of values: 1


%StringParseInt
number of arguments: 2
number of values: 1


%StringParseFloat
number of arguments: 1
number of values: 1


%NumberToStringSkipCache
number of arguments: 1
number of values: 1


%NumberToSmi
number of arguments: 1
number of values: 1


%SmiLexicographicCompare
number of arguments: 2
number of values: 1


%MaxSmi
number of arguments: 0
number of values: 1


%IsSmi
number of arguments: 1
number of values: 1


%GetHoleNaNUpper
number of arguments: 0
number of values: 1


%GetHoleNaNLower
number of arguments: 0
number of values: 1


%AddDictionaryProperty
number of arguments: 3
number of values: 1


%GetPrototype
number of arguments: 1
number of values: 1


%ObjectKeys
number of arguments: 1
number of values: 1


%ObjectHasOwnProperty
number of arguments: 2
number of values: 1


%ObjectCreate
number of arguments: 2
number of values: 1


%InternalSetPrototype
number of arguments: 2
number of values: 1


%OptimizeObjectForAddingMultipleProperties
number of arguments: 2
number of values: 1


%ObjectValues
number of arguments: 1
number of values: 1


%ObjectValuesSkipFastPath
number of arguments: 1
number of values: 1


%ObjectEntries
number of arguments: 1
number of values: 1


%ObjectEntriesSkipFastPath
number of arguments: 1
number of values: 1


%GetProperty
number of arguments: 2
number of values: 1


%KeyedGetProperty
number of arguments: 2
number of values: 1


%AddNamedProperty
number of arguments: 4
number of values: 1


%SetProperty
number of arguments: 4
number of values: 1


%AddElement
number of arguments: 3
number of values: 1


%AppendElement
number of arguments: 2
number of values: 1


%DeleteProperty
number of arguments: 3
number of values: 1


%ShrinkPropertyDictionary
number of arguments: 1
number of values: 1


%HasProperty
number of arguments: 2
number of values: 1


%GetOwnPropertyKeys
number of arguments: 2
number of values: 1


%GetInterceptorInfo
number of arguments: 1
number of values: 1


%ToFastProperties
number of arguments: 1
number of values: 1


%AllocateHeapNumber
number of arguments: 0
number of values: 1


%NewObject
number of arguments: 2
number of values: 1


%CompleteInobjectSlackTrackingForMap
number of arguments: 1
number of values: 1


%TryMigrateInstance
number of arguments: 1
number of values: 1


%DefineAccessorPropertyUnchecked
number of arguments: 5
number of values: 1


%DefineDataPropertyInLiteral
number of arguments: 6
number of values: 1


%CollectTypeProfile
number of arguments: 3
number of values: 1


%HasFastPackedElements
number of arguments: 1
number of values: 1


%ValueOf
number of arguments: 1
number of values: 1


%IsJSReceiver
number of arguments: 1
number of values: 1


%ClassOf
number of arguments: 1
number of values: 1


%CopyDataProperties
number of arguments: 2
number of values: 1


%CopyDataPropertiesWithExcludedProperties
number of arguments: -1 /* >= 1 */
number of values: 1


%DefineGetterPropertyUnchecked
number of arguments: 4
number of values: 1


%DefineSetterPropertyUnchecked
number of arguments: 4
number of values: 1


%DefineMethodsInternal
number of arguments: 3
number of values: 1


%ToObject
number of arguments: 1
number of values: 1


%ToPrimitive
number of arguments: 1
number of values: 1


%ToPrimitive_Number
number of arguments: 1
number of values: 1


%ToNumber
number of arguments: 1
number of values: 1


%ToNumeric
number of arguments: 1
number of values: 1


%ToInteger
number of arguments: 1
number of values: 1


%ToLength
number of arguments: 1
number of values: 1


%ToString
number of arguments: 1
number of values: 1


%ToName
number of arguments: 1
number of values: 1


%SameValue
number of arguments: 2
number of values: 1


%SameValueZero
number of arguments: 2
number of values: 1


%HasInPrototypeChain
number of arguments: 2
number of values: 1


%CreateIterResultObject
number of arguments: 2
number of values: 1


%CreateDataProperty
number of arguments: 3
number of values: 1


%AddPrivateField
number of arguments: 3
number of values: 1


%IterableToListCanBeElided
number of arguments: 1
number of values: 1


%GetOwnPropertyDescriptor
number of arguments: 2
number of values: 1


%Add
number of arguments: 2
number of values: 1


%Equal
number of arguments: 2
number of values: 1


%NotEqual
number of arguments: 2
number of values: 1


%StrictEqual
number of arguments: 2
number of values: 1


%StrictNotEqual
number of arguments: 2
number of values: 1


%LessThan
number of arguments: 2
number of values: 1


%GreaterThan
number of arguments: 2
number of values: 1


%LessThanOrEqual
number of arguments: 2
number of values: 1


%GreaterThanOrEqual
number of arguments: 2
number of values: 1


%EnqueueMicrotask
number of arguments: 1
number of values: 1


%PromiseHookInit
number of arguments: 2
number of values: 1


%PromiseHookBefore
number of arguments: 1
number of values: 1


%PromiseHookAfter
number of arguments: 1
number of values: 1


%PromiseMarkAsHandled
number of arguments: 1
number of values: 1


%PromiseRejectEventFromStack
number of arguments: 2
number of values: 1


%PromiseRevokeReject
number of arguments: 1
number of values: 1


%PromiseResult
number of arguments: 1
number of values: 1


%PromiseStatus
number of arguments: 1
number of values: 1


%RejectPromise
number of arguments: 3
number of values: 1


%ResolvePromise
number of arguments: 2
number of values: 1


%IsJSProxy
number of arguments: 1
number of values: 1


%JSProxyGetTarget
number of arguments: 1
number of values: 1


%JSProxyGetHandler
number of arguments: 1
number of values: 1


%GetPropertyWithReceiver
number of arguments: 2
number of values: 1


%CheckProxyHasTrap
number of arguments: 2
number of values: 1


%SetPropertyWithReceiver
number of arguments: 5
number of values: 1


%CheckProxyGetSetTrapResult
number of arguments: 2
number of values: 1


%IsRegExp
number of arguments: 1
number of values: 1


%RegExpExec
number of arguments: 4
number of values: 1


%RegExpExecMultiple
number of arguments: 4
number of values: 1


%RegExpInitializeAndCompile
number of arguments: 3
number of values: 1


%RegExpInternalReplace
number of arguments: 3
number of values: 1


%RegExpReplace
number of arguments: 3
number of values: 1


%RegExpSplit
number of arguments: 3
number of values: 1


%StringReplaceNonGlobalRegExpWithFunction
number of arguments: 3
number of values: 1


%StringSplit
number of arguments: 3
number of values: 1


%ThrowConstAssignError
number of arguments: 0
number of values: 1


%DeclareGlobals
number of arguments: 3
number of values: 1


%DeclareGlobalsForInterpreter
number of arguments: 3
number of values: 1


%DeclareEvalFunction
number of arguments: 2
number of values: 1


%DeclareEvalVar
number of arguments: 1
number of values: 1


%NewSloppyArguments_Generic
number of arguments: 1
number of values: 1


%NewStrictArguments
number of arguments: 1
number of values: 1


%NewRestParameter
number of arguments: 1
number of values: 1


%NewSloppyArguments
number of arguments: 3
number of values: 1


%NewArgumentsElements
number of arguments: 3
number of values: 1


%NewClosure
number of arguments: 2
number of values: 1


%NewClosure_Tenured
number of arguments: 2
number of values: 1


%NewScriptContext
number of arguments: 2
number of values: 1


%NewFunctionContext
number of arguments: 2
number of values: 1


%PushModuleContext
number of arguments: 3
number of values: 1


%PushWithContext
number of arguments: 3
number of values: 1


%PushCatchContext
number of arguments: 4
number of values: 1


%PushBlockContext
number of arguments: 2
number of values: 1


%DeleteLookupSlot
number of arguments: 1
number of values: 1


%LoadLookupSlot
number of arguments: 1
number of values: 1


%LoadLookupSlotInsideTypeof
number of arguments: 1
number of values: 1


%StoreLookupSlot_Sloppy
number of arguments: 2
number of values: 1


%StoreLookupSlot_SloppyHoisting
number of arguments: 2
number of values: 1


%StoreLookupSlot_Strict
number of arguments: 2
number of values: 1


%GetSubstitution
number of arguments: 5
number of values: 1


%StringReplaceOneCharWithString
number of arguments: 3
number of values: 1


%StringIncludes
number of arguments: 3
number of values: 1


%StringTrim
number of arguments: 2
number of values: 1


%StringIndexOf
number of arguments: 3
number of values: 1


%StringIndexOfUnchecked
number of arguments: 3
number of values: 1


%StringLastIndexOf
number of arguments: 2
number of values: 1


%StringSubstring
number of arguments: 3
number of values: 1


%StringAdd
number of arguments: 2
number of values: 1


%InternalizeString
number of arguments: 1
number of values: 1


%StringCharCodeAt
number of arguments: 2
number of values: 1


%StringBuilderConcat
number of arguments: 3
number of values: 1


%StringBuilderJoin
number of arguments: 3
number of values: 1


%SparseJoinWithSeparator
number of arguments: 3
number of values: 1


%StringToArray
number of arguments: 2
number of values: 1


%StringLessThan
number of arguments: 2
number of values: 1


%StringLessThanOrEqual
number of arguments: 2
number of values: 1


%StringGreaterThan
number of arguments: 2
number of values: 1


%StringGreaterThanOrEqual
number of arguments: 2
number of values: 1


%StringEqual
number of arguments: 2
number of values: 1


%StringNotEqual
number of arguments: 2
number of values: 1


%FlattenString
number of arguments: 1
number of values: 1


%StringCharFromCode
number of arguments: 1
number of values: 1


%StringMaxLength
number of arguments: 0
number of values: 1


%CreatePrivateSymbol
number of arguments: -1 /* <= 1 */
number of values: 1


%CreatePrivateFieldSymbol
number of arguments: 0
number of values: 1


%SymbolDescription
number of arguments: 1
number of values: 1


%SymbolDescriptiveString
number of arguments: 1
number of values: 1


%SymbolIsPrivate
number of arguments: 1
number of values: 1


%Abort
number of arguments: 1
number of values: 1


%AbortJS
number of arguments: 1
number of values: 1


%ClearFunctionFeedback
number of arguments: 1
number of values: 1


%CompleteInobjectSlackTracking
number of arguments: 1
number of values: 1


%ConstructConsString
number of arguments: 2
number of values: 1


%ConstructDouble
number of arguments: 2
number of values: 1


%DebugPrint
number of arguments: 1
number of values: 1


%DebugTrace
number of arguments: 0
number of values: 1


%DebugTrackRetainingPath
number of arguments: -1
number of values: 1


%DeoptimizeFunction
number of arguments: 1
number of values: 1


%DeoptimizeNow
number of arguments: 0
number of values: 1


%DeserializeWasmModule
number of arguments: 2
number of values: 1


%DisallowCodegenFromStrings
number of arguments: 1
number of values: 1


%DisallowWasmCodegen
number of arguments: 1
number of values: 1


%DisassembleFunction
number of arguments: 1
number of values: 1


%FreezeWasmLazyCompilation
number of arguments: 1
number of values: 1


%GetCallable
number of arguments: 0
number of values: 1


%GetDeoptCount
number of arguments: 1
number of values: 1


%GetOptimizationStatus
number of arguments: -1
number of values: 1


%GetUndetectable
number of arguments: 0
number of values: 1


%GetWasmRecoveredTrapCount
number of arguments: 0
number of values: 1


%GlobalPrint
number of arguments: 1
number of values: 1


%HasDictionaryElements
number of arguments: 1
number of values: 1


%HasDoubleElements
number of arguments: 1
number of values: 1


%HasFastElements
number of arguments: 1
number of values: 1


%HasFastProperties
number of arguments: 1
number of values: 1


%HasFixedBigInt64Elements
number of arguments: 1
number of values: 1


%HasFixedBigUint64Elements
number of arguments: 1
number of values: 1


%HasFixedFloat32Elements
number of arguments: 1
number of values: 1


%HasFixedFloat64Elements
number of arguments: 1
number of values: 1


%HasFixedInt16Elements
number of arguments: 1
number of values: 1


%HasFixedInt32Elements
number of arguments: 1
number of values: 1


%HasFixedInt8Elements
number of arguments: 1
number of values: 1


%HasFixedUint16Elements
number of arguments: 1
number of values: 1


%HasFixedUint32Elements
number of arguments: 1
number of values: 1


%HasFixedUint8ClampedElements
number of arguments: 1
number of values: 1


%HasFixedUint8Elements
number of arguments: 1
number of values: 1


%HasHoleyElements
number of arguments: 1
number of values: 1


%IsJSError
number of arguments: 1
number of values: 1


%IsJSGeneratorObject
number of arguments: 1
number of values: 1


%IsJSMapIterator
number of arguments: 1
number of values: 1


%IsScriptWrapper
number of arguments: 1
number of values: 1


%IsJSSetIterator
number of arguments: 1
number of values: 1


%HasObjectElements
number of arguments: 1
number of values: 1


%HasSloppyArgumentsElements
number of arguments: 1
number of values: 1


%HasSmiElements
number of arguments: 1
number of values: 1


%HasSmiOrObjectElements
number of arguments: 1
number of values: 1


%HaveSameMap
number of arguments: 2
number of values: 1


%HeapObjectVerify
number of arguments: 1
number of values: 1


%InNewSpace
number of arguments: 1
number of values: 1


%IsAsmWasmCode
number of arguments: 1
number of values: 1


%IsConcurrentRecompilationSupported
number of arguments: 0
number of values: 1


%IsLiftoffFunction
number of arguments: 1
number of values: 1


%IsWasmCode
number of arguments: 1
number of values: 1


%IsWasmTrapHandlerEnabled
number of arguments: 0
number of values: 1


%NativeScriptsCount
number of arguments: 0
number of values: 1


%NeverOptimizeFunction
number of arguments: 1
number of values: 1


%NotifyContextDisposed
number of arguments: 0
number of values: 1


%OptimizeFunctionOnNextCall
number of arguments: -1
number of values: 1


%OptimizeOsr
number of arguments: -1
number of values: 1


%PrintWithNameForAssert
number of arguments: 2
number of values: 1


%RedirectToWasmInterpreter
number of arguments: 2
number of values: 1


%RunningInSimulator
number of arguments: 0
number of values: 1


%SerializeWasmModule
number of arguments: 1
number of values: 1


%SetAllocationTimeout
number of arguments: -1 /* 2 || 3 */
number of values: 1


%SetFlags
number of arguments: 1
number of values: 1


%SetForceSlowPath
number of arguments: 1
number of values: 1


%SetWasmCompileControls
number of arguments: 2
number of values: 1


%SetWasmInstantiateControls
number of arguments: 0
number of values: 1


%SpeciesProtector
number of arguments: 0
number of values: 1


%SystemBreak
number of arguments: 0
number of values: 1


%TraceEnter
number of arguments: 0
number of values: 1


%TraceExit
number of arguments: 1
number of values: 1


%UnblockConcurrentRecompilation
number of arguments: 0
number of values: 1


%ValidateWasmInstancesChain
number of arguments: 2
number of values: 1


%ValidateWasmModuleState
number of arguments: 1
number of values: 1


%ValidateWasmOrphanedInstance
number of arguments: 1
number of values: 1


%WasmNumInterpretedCalls
number of arguments: 1
number of values: 1


%WasmTraceMemory
number of arguments: 1
number of values: 1


%ArrayBufferNeuter
number of arguments: 1
number of values: 1


%TypedArrayCopyElements
number of arguments: 3
number of values: 1


%ArrayBufferViewWasNeutered
number of arguments: 1
number of values: 1


%TypedArrayGetLength
number of arguments: 1
number of values: 1


%TypedArrayGetBuffer
number of arguments: 1
number of values: 1


%TypedArraySortFast
number of arguments: 1
number of values: 1


%TypedArraySet
number of arguments: 2
number of values: 1


%IsTypedArray
number of arguments: 1
number of values: 1


%WasmGrowMemory
number of arguments: 1
number of values: 1


%ThrowWasmError
number of arguments: 1
number of values: 1


%ThrowWasmStackOverflow
number of arguments: 0
number of values: 1


%WasmThrowTypeError
number of arguments: 0
number of values: 1


%WasmThrowCreate
number of arguments: 2
number of values: 1


%WasmThrow
number of arguments: 0
number of values: 1


%WasmGetExceptionRuntimeId
number of arguments: 0
number of values: 1


%WasmExceptionSetElement
number of arguments: 2
number of values: 1


%WasmExceptionGetElement
number of arguments: 1
number of values: 1


%WasmRunInterpreter
number of arguments: 2
number of values: 1


%WasmStackGuard
number of arguments: 0
number of values: 1


%WasmCompileLazy
number of arguments: 0
number of values: 1


%LoadLookupSlotForCall
number of arguments: 1
number of values: 2


%DebugBreakOnBytecode
number of arguments: 1
number of values: 2


%ElementsTransitionAndStoreIC_Miss
number of arguments: 6
number of values: 1


%KeyedLoadIC_Miss
number of arguments: 4
number of values: 1


%KeyedStoreIC_Miss
number of arguments: 5
number of values: 1


%KeyedStoreIC_Slow
number of arguments: 5
number of values: 1


%LoadElementWithInterceptor
number of arguments: 2
number of values: 1


%LoadGlobalIC_Miss
number of arguments: 3
number of values: 1


%LoadGlobalIC_Slow
number of arguments: 3
number of values: 1


%LoadIC_Miss
number of arguments: 4
number of values: 1


%LoadPropertyWithInterceptor
number of arguments: 5
number of values: 1


%StoreInArrayLiteralIC_Slow
number of arguments: 5
number of values: 1


%StoreCallbackProperty
number of arguments: 6
number of values: 1


%StoreGlobalIC_Miss
number of arguments: 4
number of values: 1


%StoreGlobalIC_Slow
number of arguments: 5
number of values: 1


%StoreIC_Miss
number of arguments: 5
number of values: 1


%StorePropertyWithInterceptor
number of arguments: 5
number of values: 1
```

