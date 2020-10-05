---
title: concrt140.dll | Microsoft Concurrency Runtime Library
excerpt: What is concrt140.dll?
---

# concrt140.dll 

* File Path: `C:\Program Files (x86)\Microsoft\Edge\Application\85.0.564.68\concrt140.dll`
* Description: Microsoft Concurrency Runtime Library

## Hashes

Type | Hash
-- | --
MD5 | `C67EA89D3743C61EB4F5021A18820EED`
SHA1 | `4543CBAC354D1501FF3219710BD25B2675CD4420`
SHA256 | `8DB33C1446C9EEAB1A0969C52654EC6509AD9D11FE1C20089F76B09E12EDF6B1`
SHA384 | `81EDC10E779C4BB9A5ED489DE7A77ABCB48D7DF46A771F2F678732A7A0B853A628978C688832BF8BC6930BBC6AC5EFF8`
SHA512 | `00444DA14605D194B027DBDB4CD731538E2BFA683B9032B81EDD5486C8B97C277ED5BCB383F68641119ED3F8F1CFC74F4A7DDBB5A0A9D174267BB5AC5556EF9B`
SSDEEP | `6144:2VwR2xhiXuz1BxUBE0I3umFKuLHqvqNXV4rnWzgCEcD:Vs9zGEj3saz7D`
IMP | `7F070C3864CE20E1B9879A9E3126CD30`
PESHA1 | `D63BC7184C32577FD3979EC8753E242AE377516B`
PE256 | `DF40E70817760002A3AE2E8D019588B8AFC84BF1E442AD4C069363D5B0A8C89D`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: static unsigned int __cdecl Concurrency::details::_CurrentScheduler::_Id(void)` | 194 | Exported Function
`public: static unsigned int __cdecl Concurrency::details::_SpinCount::_Value(void)` | 257 | Exported Function
`public: static unsigned int __cdecl Concurrency::CurrentScheduler::Id(void)` | 138 | Exported Function
`public: static unsigned int __cdecl Concurrency::details::_CurrentScheduler::_GetNumberOfVirtualProcessors(void)` | 192 | Exported Function
`public: static void __cdecl Concurrency::agent::wait_for_all(unsigned __int64,class Concurrency::agent * __ptr64 * __ptr64,enum Concurrency::agent_status * __ptr64,unsigned int)` | 289 | Exported Function
`public: static void __cdecl Concurrency::Context::Block(void)` | 112 | Exported Function
`public: static void __cdecl Concurrency::Context::Oversubscribe(bool)` | 146 | Exported Function
`public: static void __cdecl Concurrency::agent::wait_for_one(unsigned __int64,class Concurrency::agent * __ptr64 * __ptr64,enum Concurrency::agent_status & __ptr64,unsigned __int64 & __ptr64,unsigned int)` | 291 | Exported Function
`public: static void __cdecl Concurrency::Context::_SpinYield(void)` | 247 | Exported Function
`public: static class Concurrency::SchedulerPolicy __cdecl Concurrency::CurrentScheduler::GetPolicy(void)` | 131 | Exported Function
`public: static enum Concurrency::agent_status __cdecl Concurrency::agent::wait(class Concurrency::agent * __ptr64,unsigned int)` | 286 | Exported Function
`public: static class Concurrency::Scheduler * __ptr64 __cdecl Concurrency::CurrentScheduler::Get(void)` | 127 | Exported Function
`public: static class Concurrency::Scheduler * __ptr64 __cdecl Concurrency::Scheduler::Create(class Concurrency::SchedulerPolicy const & __ptr64)` | 118 | Exported Function
`public: static unsigned __int64 __cdecl Concurrency::event::wait_for_multiple(class Concurrency::event * __ptr64 * __ptr64,unsigned __int64,bool,unsigned int)` | 290 | Exported Function
`public: static unsigned int __cdecl Concurrency::Context::VirtualProcessorId(void)` | 162 | Exported Function
`public: static unsigned int __cdecl Concurrency::CurrentScheduler::GetNumberOfVirtualProcessors(void)` | 129 | Exported Function
`public: static unsigned int __cdecl Concurrency::Context::Id(void)` | 137 | Exported Function
`public: static unsigned int __cdecl Concurrency::Context::ScheduleGroupId(void)` | 154 | Exported Function
`public: unsigned __int64 __cdecl Concurrency::event::wait(unsigned int) __ptr64` | 287 | Exported Function
`public: unsigned int __cdecl Concurrency::details::_Scheduler::_Reference(void) __ptr64` | 222 | Exported Function
`public: static void __cdecl Concurrency::Scheduler::ResetDefaultSchedulerPolicy(void)` | 151 | Exported Function
`public: static void __cdecl Concurrency::Scheduler::SetDefaultSchedulerPolicy(class Concurrency::SchedulerPolicy const & __ptr64)` | 159 | Exported Function
`public: unsigned int __cdecl Concurrency::details::_Scheduler::_Release(void) __ptr64` | 228 | Exported Function
`public: virtual __cdecl Concurrency::agent::~agent(void) __ptr64` | 94 | Exported Function
`public: void __cdecl Concurrency::critical_section::lock(void) __ptr64` | 265 | Exported Function
`public: unsigned int __cdecl Concurrency::SchedulerPolicy::GetPolicyValue(enum Concurrency::PolicyElementKey)const __ptr64` | 132 | Exported Function
`public: unsigned int __cdecl Concurrency::SchedulerPolicy::SetPolicyValue(enum Concurrency::PolicyElementKey,unsigned int) __ptr64` | 160 | Exported Function
`public: static void __cdecl Concurrency::CurrentScheduler::Detach(void)` | 123 | Exported Function
`public: static void __cdecl Concurrency::CurrentScheduler::RegisterShutdownEvent(void * __ptr64)` | 150 | Exported Function
`public: static void __cdecl Concurrency::Context::Yield(void)` | 163 | Exported Function
`public: static void __cdecl Concurrency::CurrentScheduler::Create(class Concurrency::SchedulerPolicy const & __ptr64)` | 117 | Exported Function
`public: static void __cdecl Concurrency::CurrentScheduler::ScheduleTask(void (__cdecl*)(void * __ptr64),void * __ptr64)` | 155 | Exported Function
`public: static void __cdecl Concurrency::details::_Context::_Yield(void)` | 258 | Exported Function
`public: static void __cdecl Concurrency::details::_CurrentScheduler::_ScheduleTask(void (__cdecl*)(void * __ptr64),void * __ptr64)` | 239 | Exported Function
`public: static void __cdecl Concurrency::CurrentScheduler::ScheduleTask(void (__cdecl*)(void * __ptr64),void * __ptr64,class Concurrency::location & __ptr64)` | 156 | Exported Function
`public: static void __cdecl Concurrency::details::_Context::_Oversubscribe(bool)` | 221 | Exported Function
`public: bool __cdecl Concurrency::reader_writer_lock::try_lock(void) __ptr64` | 279 | Exported Function
`public: bool __cdecl Concurrency::reader_writer_lock::try_lock_read(void) __ptr64` | 281 | Exported Function
`public: bool __cdecl Concurrency::details::_StructuredTaskCollection::_IsCanceling(void) __ptr64` | 215 | Exported Function
`public: bool __cdecl Concurrency::details::_TaskCollection::_IsCanceling(void) __ptr64` | 216 | Exported Function
`public: class Concurrency::critical_section & __ptr64 __cdecl Concurrency::critical_section::native_handle(void) __ptr64` | 268 | Exported Function
`public: class Concurrency::details::_SpinWait<1> & __ptr64 __cdecl Concurrency::details::_SpinWait<1>::operator=(class Concurrency::details::_SpinWait<1> && __ptr64) __ptr64` | 101 | Exported Function
`public: class Concurrency::details::_SpinWait<1> & __ptr64 __cdecl Concurrency::details::_SpinWait<1>::operator=(class Concurrency::details::_SpinWait<1> const & __ptr64) __ptr64` | 102 | Exported Function
`public: class Concurrency::details::_SpinWait<0> & __ptr64 __cdecl Concurrency::details::_SpinWait<0>::operator=(class Concurrency::details::_SpinWait<0> && __ptr64) __ptr64` | 103 | Exported Function
`public: class Concurrency::details::_SpinWait<0> & __ptr64 __cdecl Concurrency::details::_SpinWait<0>::operator=(class Concurrency::details::_SpinWait<0> const & __ptr64) __ptr64` | 104 | Exported Function
`public: bool __cdecl Concurrency::details::_Context::_IsSynchronouslyBlocked(void)const __ptr64` | 217 | Exported Function
`public: bool __cdecl Concurrency::details::_NonReentrantBlockingLock::_TryAcquire(void) __ptr64` | 252 | Exported Function
`public: bool __cdecl Concurrency::details::_Cancellation_beacon::_Confirm_cancel(void) __ptr64` | 181 | Exported Function
`public: bool __cdecl Concurrency::details::_Condition_variable::wait_for(class Concurrency::critical_section & __ptr64,unsigned int) __ptr64` | 288 | Exported Function
`public: bool __cdecl Concurrency::details::_ReaderWriterLock::_TryAcquireWrite(void) __ptr64` | 255 | Exported Function
`public: bool __cdecl Concurrency::details::_SpinWait<0>::_SpinOnce(void) __ptr64` | 246 | Exported Function
`public: bool __cdecl Concurrency::details::_SpinWait<1>::_SpinOnce(void) __ptr64` | 245 | Exported Function
`public: bool __cdecl Concurrency::details::_ReentrantBlockingLock::_TryAcquire(void) __ptr64` | 253 | Exported Function
`public: bool __cdecl Concurrency::details::_ReentrantLock::_TryAcquire(void) __ptr64` | 254 | Exported Function
`public: static class Concurrency::details::_Context __cdecl Concurrency::details::_Context::_CurrentContext(void)` | 182 | Exported Function
`public: static class Concurrency::details::_Scheduler __cdecl Concurrency::details::_CurrentScheduler::_Get(void)` | 187 | Exported Function
`public: static class Concurrency::Context * __ptr64 __cdecl Concurrency::Context::CurrentContext(void)` | 122 | Exported Function
`public: static class Concurrency::details::_AsyncTaskCollection * __ptr64 __cdecl Concurrency::details::_AsyncTaskCollection::_NewCollection(class Concurrency::details::_CancellationTokenState * __ptr64)` | 218 | Exported Function
`public: static class Concurrency::location __cdecl Concurrency::location::_Current_node(void)` | 183 | Exported Function
`public: static class Concurrency::ScheduleGroup * __ptr64 __cdecl Concurrency::CurrentScheduler::CreateScheduleGroup(class Concurrency::location & __ptr64)` | 120 | Exported Function
`public: static class Concurrency::ScheduleGroup * __ptr64 __cdecl Concurrency::CurrentScheduler::CreateScheduleGroup(void)` | 121 | Exported Function
`public: static class Concurrency::location __cdecl Concurrency::location::current(void)` | 260 | Exported Function
`public: static class Concurrency::location __cdecl Concurrency::location::from_numa_node(unsigned short)` | 262 | Exported Function
`public: class Concurrency::SchedulerPolicy & __ptr64 __cdecl Concurrency::SchedulerPolicy::operator=(class Concurrency::SchedulerPolicy const & __ptr64) __ptr64` | 105 | Exported Function
`public: enum Concurrency::agent_status __cdecl Concurrency::agent::status(void) __ptr64` | 276 | Exported Function
`public: class Concurrency::ISource<enum Concurrency::agent_status> * __ptr64 __cdecl Concurrency::agent::status_port(void) __ptr64` | 277 | Exported Function
`public: class Concurrency::Scheduler * __ptr64 __cdecl Concurrency::details::_Scheduler::_GetScheduler(void) __ptr64` | 193 | Exported Function
`public: enum Concurrency::details::_TaskCollectionStatus __cdecl Concurrency::details::_StructuredTaskCollection::_RunAndWait(class Concurrency::details::_UnrealizedChore * __ptr64) __ptr64` | 233 | Exported Function
`public: static bool __cdecl Concurrency::Context::IsCurrentTaskCollectionCanceling(void)` | 140 | Exported Function
`public: static bool __cdecl Concurrency::CurrentScheduler::IsAvailableLocation(class Concurrency::location const & __ptr64)` | 139 | Exported Function
`public: enum Concurrency::details::_TaskCollectionStatus __cdecl Concurrency::details::_TaskCollection::_RunAndWait(class Concurrency::details::_UnrealizedChore * __ptr64) __ptr64` | 234 | Exported Function
`public: long __cdecl Concurrency::scheduler_resource_allocation_error::get_error_code(void)const __ptr64` | 263 | Exported Function
`public: void __cdecl Concurrency::critical_section::unlock(void) __ptr64` | 282 | Exported Function
`struct _GUID const Concurrency::VirtualProcessorEventGuid` | 161 | Exported Function
`struct Concurrency::details::_CONCRT_TRACE_INFO const * __ptr64 __cdecl Concurrency::_GetConcRTTraceInfo(void)` | 189 | Exported Function
`struct _GUID const Concurrency::ScheduleGroupEventGuid` | 153 | Exported Function
`struct _GUID const Concurrency::SchedulerEventGuid` | 157 | Exported Function
`struct Concurrency::IResourceManager * __ptr64 __cdecl Concurrency::CreateResourceManager(void)` | 119 | Exported Function
`unsigned char const * const Concurrency::details::_Byte_reverse_table` | 174 | Exported Function
`unsigned int __cdecl Concurrency::details::_GetConcurrency(void)` | 190 | Exported Function
`unsigned __int64 __cdecl Concurrency::details::_GetCombinableSize(void)` | 188 | Exported Function
`unsigned __int64 __cdecl Concurrency::details::NFS_GetLineSize(void)` | 145 | Exported Function
`struct _GUID const Concurrency::ConcRTEventGuid` | 114 | Exported Function
`struct _GUID const Concurrency::ContextEventGuid` | 116 | Exported Function
`struct _GUID const Concurrency::ChoreEventGuid` | 113 | Exported Function
`struct _GUID const Concurrency::ConcRT_ProviderGuid` | 115 | Exported Function
`struct _GUID const Concurrency::LockEventGuid` | 141 | Exported Function
`struct _GUID const Concurrency::PPLParallelInvokeEventGuid` | 149 | Exported Function
`struct _GUID const Concurrency::ResourceManagerEventGuid` | 152 | Exported Function
`struct _GUID const Concurrency::PPLParallelForeachEventGuid` | 148 | Exported Function
`struct _GUID const Concurrency::PPLParallelForEventGuid` | 147 | Exported Function
`void __cdecl Concurrency::details::_ConcRT_Trace(int,wchar_t const * __ptr64,...)` | 180 | Exported Function
`void __cdecl Concurrency::details::_UnderlyingYield(void)` | 256 | Exported Function
`void __cdecl Concurrency::_Trace_ppl_function(struct _GUID const & __ptr64,unsigned char,enum Concurrency::ConcRT_EventType)` | 251 | Exported Function
`void __cdecl Concurrency::details::_ConcRT_CoreAssert(char const * __ptr64,char const * __ptr64,int)` | 179 | Exported Function
`void __cdecl Concurrency::details::NFS_Free(void * __ptr64)` | 144 | Exported Function
`void __cdecl Concurrency::set_task_execution_resources(unsigned short,struct _GROUP_AFFINITY * __ptr64)` | 273 | Exported Function
`void __cdecl Concurrency::wait(unsigned int)` | 284 | Exported Function
`void __cdecl Concurrency::Free(void * __ptr64)` | 126 | Exported Function
`void __cdecl Concurrency::set_task_execution_resources(unsigned __int64)` | 274 | Exported Function
`unsigned int __cdecl Concurrency::GetProcessorNodeCount(void)` | 134 | Exported Function
`unsigned int __cdecl Concurrency::GetSchedulerId(void)` | 135 | Exported Function
`unsigned int __cdecl Concurrency::GetExecutionContextId(void)` | 128 | Exported Function
`unsigned int __cdecl Concurrency::GetProcessorCount(void)` | 133 | Exported Function
`unsigned long __cdecl Concurrency::details::Log2(unsigned __int64)` | 142 | Exported Function
`void * __ptr64 __cdecl Concurrency::details::NFS_Allocate(unsigned __int64,unsigned __int64,void * __ptr64)` | 143 | Exported Function
`void __cdecl Concurrency::_Trace_agents(enum Concurrency::Agents_EventType,__int64,...)` | 250 | Exported Function
`void * __ptr64 __cdecl Concurrency::Alloc(unsigned __int64)` | 111 | Exported Function
`void * __ptr64 __cdecl Concurrency::details::GetSharedTimerQueue(void)` | 136 | Exported Function
`public: void __cdecl Concurrency::details::_ReaderWriterLock::_ReleaseWrite(void) __ptr64` | 230 | Exported Function
`public: void __cdecl Concurrency::details::_ReentrantBlockingLock::_Acquire(void) __ptr64` | 167 | Exported Function
`public: void __cdecl Concurrency::details::_ReaderWriterLock::_AcquireWrite(void) __ptr64` | 171 | Exported Function
`public: void __cdecl Concurrency::details::_ReaderWriterLock::_ReleaseRead(void) __ptr64` | 229 | Exported Function
`public: void __cdecl Concurrency::details::_ReentrantBlockingLock::_Release(void) __ptr64` | 225 | Exported Function
`public: void __cdecl Concurrency::details::_ReentrantPPLLock::_Acquire(void * __ptr64) __ptr64` | 169 | Exported Function
`public: void __cdecl Concurrency::details::_ReentrantPPLLock::_Release(void) __ptr64` | 227 | Exported Function
`public: void __cdecl Concurrency::details::_ReentrantLock::_Acquire(void) __ptr64` | 168 | Exported Function
`public: void __cdecl Concurrency::details::_ReentrantLock::_Release(void) __ptr64` | 226 | Exported Function
`public: void __cdecl Concurrency::details::_Condition_variable::wait(class Concurrency::critical_section & __ptr64) __ptr64` | 285 | Exported Function
`public: void __cdecl Concurrency::details::_Context::``default constructor closure'(void) __ptr64` | 108 | Exported Function
`public: void __cdecl Concurrency::details::_Condition_variable::notify_all(void) __ptr64` | 269 | Exported Function
`public: void __cdecl Concurrency::details::_Condition_variable::notify_one(void) __ptr64` | 270 | Exported Function
`public: void __cdecl Concurrency::details::_NonReentrantBlockingLock::_Acquire(void) __ptr64` | 165 | Exported Function
`public: void __cdecl Concurrency::details::_NonReentrantPPLLock::_Release(void) __ptr64` | 224 | Exported Function
`public: void __cdecl Concurrency::details::_ReaderWriterLock::_AcquireRead(void) __ptr64` | 170 | Exported Function
`public: void __cdecl Concurrency::details::_NonReentrantBlockingLock::_Release(void) __ptr64` | 223 | Exported Function
`public: void __cdecl Concurrency::details::_NonReentrantPPLLock::_Acquire(void * __ptr64) __ptr64` | 166 | Exported Function
`public: void __cdecl Concurrency::event::reset(void) __ptr64` | 271 | Exported Function
`public: void __cdecl Concurrency::event::set(void) __ptr64` | 272 | Exported Function
`public: void __cdecl Concurrency::details::_TaskCollection::_Schedule(class Concurrency::details::_UnrealizedChore * __ptr64) __ptr64` | 237 | Exported Function
`public: void __cdecl Concurrency::details::_TaskCollection::_Schedule(class Concurrency::details::_UnrealizedChore * __ptr64,class Concurrency::location * __ptr64) __ptr64` | 238 | Exported Function
`public: void __cdecl Concurrency::reader_writer_lock::lock(void) __ptr64` | 266 | Exported Function
`public: void __cdecl Concurrency::SchedulerPolicy::SetConcurrencyLimits(unsigned int,unsigned int) __ptr64` | 158 | Exported Function
`struct _GUID const Concurrency::AgentEventGuid` | 110 | Exported Function
`public: void __cdecl Concurrency::reader_writer_lock::lock_read(void) __ptr64` | 267 | Exported Function
`public: void __cdecl Concurrency::reader_writer_lock::unlock(void) __ptr64` | 283 | Exported Function
`public: void __cdecl Concurrency::details::_SpinWait<0>::``default constructor closure'(void) __ptr64` | 107 | Exported Function
`public: void __cdecl Concurrency::details::_SpinWait<1>::_SetSpinCount(unsigned int) __ptr64` | 241 | Exported Function
`public: void __cdecl Concurrency::details::_Scheduler::``default constructor closure'(void) __ptr64` | 109 | Exported Function
`public: void __cdecl Concurrency::details::_SpinWait<0>::_SetSpinCount(unsigned int) __ptr64` | 242 | Exported Function
`public: void __cdecl Concurrency::details::_SpinWait<1>::``default constructor closure'(void) __ptr64` | 106 | Exported Function
`public: void __cdecl Concurrency::details::_StructuredTaskCollection::_Schedule(class Concurrency::details::_UnrealizedChore * __ptr64,class Concurrency::location * __ptr64) __ptr64` | 236 | Exported Function
`public: void __cdecl Concurrency::details::_TaskCollection::_Cancel(void) __ptr64` | 176 | Exported Function
`public: void __cdecl Concurrency::details::_StructuredTaskCollection::_Cancel(void) __ptr64` | 175 | Exported Function
`public: void __cdecl Concurrency::details::_StructuredTaskCollection::_Schedule(class Concurrency::details::_UnrealizedChore * __ptr64) __ptr64` | 235 | Exported Function
`public: bool __cdecl Concurrency::critical_section::try_lock_for(unsigned int) __ptr64` | 280 | Exported Function
`protected: void __cdecl Concurrency::details::_Timer::_Start(void) __ptr64` | 248 | Exported Function
`protected: void __cdecl Concurrency::details::_Timer::_Stop(void) __ptr64` | 249 | Exported Function
`protected: void __cdecl Concurrency::details::_SpinWait<1>::_DoYield(void) __ptr64` | 185 | Exported Function
`protected: void __cdecl Concurrency::details::_SpinWait<1>::_Reset(void) __ptr64` | 231 | Exported Function
`protected: void __cdecl Concurrency::details::_UnrealizedChore::_CheckTaskCollection(void) __ptr64` | 177 | Exported Function
`public: __cdecl Concurrency::agent::agent(void) __ptr64` | 29 | Exported Function
`public: __cdecl Concurrency::bad_target::bad_target(char const * __ptr64) __ptr64` | 30 | Exported Function
`public: __cdecl Concurrency::agent::agent(class Concurrency::ScheduleGroup & __ptr64) __ptr64` | 27 | Exported Function
`public: __cdecl Concurrency::agent::agent(class Concurrency::Scheduler & __ptr64) __ptr64` | 28 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Internal_copy(class Concurrency::details::_Concurrent_vector_base_v4 const & __ptr64,unsigned __int64,void (__cdecl*)(void * __ptr64,void const * __ptr64,unsigned __int64)) __ptr64` | 199 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Internal_reserve(unsigned __int64,unsigned __int64,unsigned __int64) __ptr64` | 208 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_queue_iterator_base_v4::_Assign(class Concurrency::details::_Concurrent_queue_iterator_base_v4 const & __ptr64) __ptr64` | 173 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Internal_assign(class Concurrency::details::_Concurrent_vector_base_v4 const & __ptr64,unsigned __int64,void (__cdecl*)(void * __ptr64,unsigned __int64),void (__cdecl*)(void * __ptr64,void const * __ptr64,unsigned __int64),void (__cdecl*)(void * __ptr64,void const * __ptr64,unsigned __int64)) __ptr64` | 195 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Internal_resize(unsigned __int64,unsigned __int64,unsigned __int64,void (__cdecl*)(void * __ptr64,unsigned __int64),void (__cdecl*)(void * __ptr64,void const * __ptr64,unsigned __int64),void const * __ptr64) __ptr64` | 209 | Exported Function
`protected: void __cdecl Concurrency::details::_SpinWait<0>::_DoYield(void) __ptr64` | 186 | Exported Function
`protected: void __cdecl Concurrency::details::_SpinWait<0>::_Reset(void) __ptr64` | 232 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Internal_swap(class Concurrency::details::_Concurrent_vector_base_v4 & __ptr64) __ptr64` | 212 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Internal_throw_exception(unsigned __int64)const __ptr64` | 214 | Exported Function
`public: __cdecl Concurrency::details::_Cancellation_beacon::_Cancellation_beacon(void) __ptr64` | 6 | Exported Function
`public: __cdecl Concurrency::details::_Cancellation_beacon::~_Cancellation_beacon(void) __ptr64` | 81 | Exported Function
`public: __cdecl Concurrency::default_scheduler_exists::default_scheduler_exists(char const * __ptr64) __ptr64` | 37 | Exported Function
`public: __cdecl Concurrency::default_scheduler_exists::default_scheduler_exists(void) __ptr64` | 38 | Exported Function
`public: __cdecl Concurrency::details::_Condition_variable::_Condition_variable(void) __ptr64` | 9 | Exported Function
`public: __cdecl Concurrency::details::_NonReentrantBlockingLock::_NonReentrantBlockingLock(void) __ptr64` | 11 | Exported Function
`public: __cdecl Concurrency::details::_NonReentrantBlockingLock::~_NonReentrantBlockingLock(void) __ptr64` | 86 | Exported Function
`public: __cdecl Concurrency::details::_Condition_variable::~_Condition_variable(void) __ptr64` | 85 | Exported Function
`public: __cdecl Concurrency::details::_Context::_Context(class Concurrency::Context * __ptr64) __ptr64` | 10 | Exported Function
`public: __cdecl Concurrency::context_self_unblock::context_self_unblock(void) __ptr64` | 33 | Exported Function
`public: __cdecl Concurrency::context_unblock_unbalanced::context_unblock_unbalanced(char const * __ptr64) __ptr64` | 34 | Exported Function
`public: __cdecl Concurrency::bad_target::bad_target(void) __ptr64` | 31 | Exported Function
`public: __cdecl Concurrency::context_self_unblock::context_self_unblock(char const * __ptr64) __ptr64` | 32 | Exported Function
`public: __cdecl Concurrency::context_unblock_unbalanced::context_unblock_unbalanced(void) __ptr64` | 35 | Exported Function
`public: __cdecl Concurrency::critical_section::scoped_lock::~scoped_lock(void) __ptr64` | 98 | Exported Function
`public: __cdecl Concurrency::critical_section::~critical_section(void) __ptr64` | 95 | Exported Function
`public: __cdecl Concurrency::critical_section::critical_section(void) __ptr64` | 36 | Exported Function
`public: __cdecl Concurrency::critical_section::scoped_lock::scoped_lock(class Concurrency::critical_section & __ptr64) __ptr64` | 75 | Exported Function
`protected: __cdecl Concurrency::details::_Concurrent_vector_base_v4::~_Concurrent_vector_base_v4(void) __ptr64` | 84 | Exported Function
`protected: __cdecl Concurrency::details::_Timer::_Timer(unsigned int,bool) __ptr64` | 26 | Exported Function
`protected: __cdecl Concurrency::details::_Concurrent_queue_iterator_base_v4::_Concurrent_queue_iterator_base_v4(class Concurrency::details::_Concurrent_queue_base_v4 const & __ptr64) __ptr64` | 8 | Exported Function
`protected: __cdecl Concurrency::details::_Concurrent_queue_iterator_base_v4::~_Concurrent_queue_iterator_base_v4(void) __ptr64` | 83 | Exported Function
`protected: bool __cdecl Concurrency::agent::done(void) __ptr64` | 261 | Exported Function
`protected: bool __cdecl Concurrency::details::_SpinWait<0>::_ShouldSpinAgain(void) __ptr64` | 244 | Exported Function
`protected: bool __cdecl Concurrency::details::_SpinWait<1>::_ShouldSpinAgain(void) __ptr64` | 243 | Exported Function
`protected: bool __cdecl Concurrency::details::_Concurrent_queue_base_v4::_Internal_empty(void)const __ptr64` | 200 | Exported Function
`protected: bool __cdecl Concurrency::details::_Concurrent_queue_base_v4::_Internal_pop_if_present(void * __ptr64) __ptr64` | 205 | Exported Function
`long __cdecl Concurrency::DisableTracing(void)` | 124 | Exported Function
`long __cdecl Concurrency::EnableTracing(void)` | 125 | Exported Function
`bool __cdecl Concurrency::is_current_task_group_canceling(void)` | 264 | Exported Function
`enum Concurrency::IResourceManager::OSVersion __cdecl Concurrency::GetOSVersion(void)` | 130 | Exported Function
`private: static unsigned __int64 & __ptr64 __cdecl Concurrency::details::_StackGuard::_GetCurrentInlineDepth(void)` | 191 | Exported Function
`private: void __cdecl Concurrency::details::_StructuredTaskCollection::_CleanupToken(void) __ptr64` | 178 | Exported Function
`protected: __cdecl Concurrency::details::_Concurrent_queue_base_v4::_Concurrent_queue_base_v4(unsigned __int64) __ptr64` | 7 | Exported Function
`private: virtual void __cdecl Concurrency::details::_AsyncTaskCollection::_Destroy(void) __ptr64` | 184 | Exported Function
`private: void __cdecl Concurrency::details::_StructuredTaskCollection::_Abort(void) __ptr64` | 164 | Exported Function
`protected: void * __ptr64 __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Internal_push_back(unsigned __int64,unsigned __int64 & __ptr64) __ptr64` | 207 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_queue_base_v4::_Internal_finish_clear(void) __ptr64` | 201 | Exported Function
`protected: virtual __cdecl Concurrency::details::_Timer::~_Timer(void) __ptr64` | 93 | Exported Function
`protected: void * __ptr64 __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Internal_compact(unsigned __int64,void * __ptr64,void (__cdecl*)(void * __ptr64,unsigned __int64),void (__cdecl*)(void * __ptr64,void const * __ptr64,unsigned __int64)) __ptr64` | 198 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_queue_base_v4::_Internal_move_push(void * __ptr64) __ptr64` | 204 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_queue_base_v4::_Internal_throw_exception(void)const __ptr64` | 213 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_queue_iterator_base_v4::_Advance(void) __ptr64` | 172 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_queue_base_v4::_Internal_push(void const * __ptr64) __ptr64` | 206 | Exported Function
`protected: void __cdecl Concurrency::details::_Concurrent_queue_base_v4::_Internal_swap(class Concurrency::details::_Concurrent_queue_base_v4 & __ptr64) __ptr64` | 211 | Exported Function
`protected: unsigned __int64 __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Internal_capacity(void)const __ptr64` | 196 | Exported Function
`protected: unsigned __int64 __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Internal_clear(void (__cdecl*)(void * __ptr64,unsigned __int64)) __ptr64` | 197 | Exported Function
`protected: static unsigned __int64 __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Segment_index_of(unsigned __int64)` | 240 | Exported Function
`protected: unsigned __int64 __cdecl Concurrency::details::_Concurrent_queue_base_v4::_Internal_size(void)const __ptr64` | 210 | Exported Function
`protected: unsigned __int64 __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Internal_grow_by(unsigned __int64,unsigned __int64,void (__cdecl*)(void * __ptr64,void const * __ptr64,unsigned __int64),void const * __ptr64) __ptr64` | 202 | Exported Function
`protected: unsigned long __cdecl Concurrency::details::_SpinWait<1>::_NumberOfSpins(void) __ptr64` | 219 | Exported Function
`protected: virtual __cdecl Concurrency::details::_Concurrent_queue_base_v4::~_Concurrent_queue_base_v4(void) __ptr64` | 82 | Exported Function
`protected: unsigned __int64 __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Internal_grow_to_at_least_with_result(unsigned __int64,unsigned __int64,void (__cdecl*)(void * __ptr64,void const * __ptr64,unsigned __int64),void const * __ptr64) __ptr64` | 203 | Exported Function
`protected: unsigned long __cdecl Concurrency::details::_SpinWait<0>::_NumberOfSpins(void) __ptr64` | 220 | Exported Function
`public: __cdecl Concurrency::details::_NonReentrantPPLLock::_NonReentrantPPLLock(void) __ptr64` | 12 | Exported Function
`public: __cdecl Concurrency::nested_scheduler_missing_detach::nested_scheduler_missing_detach(char const * __ptr64) __ptr64` | 64 | Exported Function
`public: __cdecl Concurrency::nested_scheduler_missing_detach::nested_scheduler_missing_detach(void) __ptr64` | 65 | Exported Function
`public: __cdecl Concurrency::missing_wait::missing_wait(char const * __ptr64) __ptr64` | 62 | Exported Function
`public: __cdecl Concurrency::missing_wait::missing_wait(void) __ptr64` | 63 | Exported Function
`public: __cdecl Concurrency::operation_timed_out::operation_timed_out(char const * __ptr64) __ptr64` | 66 | Exported Function
`public: __cdecl Concurrency::reader_writer_lock::scoped_lock::scoped_lock(class Concurrency::reader_writer_lock & __ptr64) __ptr64` | 76 | Exported Function
`public: __cdecl Concurrency::reader_writer_lock::scoped_lock::~scoped_lock(void) __ptr64` | 99 | Exported Function
`public: __cdecl Concurrency::operation_timed_out::operation_timed_out(void) __ptr64` | 67 | Exported Function
`public: __cdecl Concurrency::reader_writer_lock::reader_writer_lock(void) __ptr64` | 68 | Exported Function
`public: __cdecl Concurrency::invalid_scheduler_policy_key::invalid_scheduler_policy_key(void) __ptr64` | 55 | Exported Function
`public: __cdecl Concurrency::invalid_scheduler_policy_thread_specification::invalid_scheduler_policy_thread_specification(char const * __ptr64) __ptr64` | 56 | Exported Function
`public: __cdecl Concurrency::invalid_oversubscribe_operation::invalid_oversubscribe_operation(void) __ptr64` | 53 | Exported Function
`public: __cdecl Concurrency::invalid_scheduler_policy_key::invalid_scheduler_policy_key(char const * __ptr64) __ptr64` | 54 | Exported Function
`public: __cdecl Concurrency::invalid_scheduler_policy_thread_specification::invalid_scheduler_policy_thread_specification(void) __ptr64` | 57 | Exported Function
`public: __cdecl Concurrency::message_not_found::message_not_found(char const * __ptr64) __ptr64` | 60 | Exported Function
`public: __cdecl Concurrency::message_not_found::message_not_found(void) __ptr64` | 61 | Exported Function
`public: __cdecl Concurrency::invalid_scheduler_policy_value::invalid_scheduler_policy_value(char const * __ptr64) __ptr64` | 58 | Exported Function
`public: __cdecl Concurrency::invalid_scheduler_policy_value::invalid_scheduler_policy_value(void) __ptr64` | 59 | Exported Function
`public: __cdecl Concurrency::SchedulerPolicy::SchedulerPolicy(void) __ptr64` | 4 | Exported Function
`public: __cdecl Concurrency::SchedulerPolicy::~SchedulerPolicy(void) __ptr64` | 80 | Exported Function
`public: __cdecl Concurrency::SchedulerPolicy::SchedulerPolicy(class Concurrency::SchedulerPolicy const & __ptr64) __ptr64` | 3 | Exported Function
`public: __cdecl Concurrency::SchedulerPolicy::SchedulerPolicy(unsigned __int64,...) __ptr64` | 5 | Exported Function
`public: __cdecl Concurrency::unsupported_os::unsupported_os(char const * __ptr64) __ptr64` | 78 | Exported Function
`public: bool __cdecl Concurrency::agent::start(void) __ptr64` | 275 | Exported Function
`public: bool __cdecl Concurrency::critical_section::try_lock(void) __ptr64` | 278 | Exported Function
`public: __cdecl Concurrency::unsupported_os::unsupported_os(void) __ptr64` | 79 | Exported Function
`public: bool __cdecl Concurrency::agent::cancel(void) __ptr64` | 259 | Exported Function
`public: __cdecl Concurrency::reader_writer_lock::~reader_writer_lock(void) __ptr64` | 97 | Exported Function
`public: __cdecl Concurrency::scheduler_not_attached::scheduler_not_attached(char const * __ptr64) __ptr64` | 69 | Exported Function
`public: __cdecl Concurrency::reader_writer_lock::scoped_lock_read::scoped_lock_read(class Concurrency::reader_writer_lock & __ptr64) __ptr64` | 77 | Exported Function
`public: __cdecl Concurrency::reader_writer_lock::scoped_lock_read::~scoped_lock_read(void) __ptr64` | 100 | Exported Function
`public: __cdecl Concurrency::scheduler_not_attached::scheduler_not_attached(void) __ptr64` | 70 | Exported Function
`public: __cdecl Concurrency::scheduler_worker_creation_error::scheduler_worker_creation_error(char const * __ptr64,long) __ptr64` | 74 | Exported Function
`public: __cdecl Concurrency::scheduler_worker_creation_error::scheduler_worker_creation_error(long) __ptr64` | 73 | Exported Function
`public: __cdecl Concurrency::scheduler_resource_allocation_error::scheduler_resource_allocation_error(char const * __ptr64,long) __ptr64` | 72 | Exported Function
`public: __cdecl Concurrency::scheduler_resource_allocation_error::scheduler_resource_allocation_error(long) __ptr64` | 71 | Exported Function
`public: __cdecl Concurrency::details::_Scheduler::_Scheduler(class Concurrency::Scheduler * __ptr64) __ptr64` | 19 | Exported Function
`public: __cdecl Concurrency::details::_SpinLock::_SpinLock(long volatile & __ptr64) __ptr64` | 22 | Exported Function
`public: __cdecl Concurrency::details::_Runtime_object::_Runtime_object(int) __ptr64` | 17 | Exported Function
`public: __cdecl Concurrency::details::_Runtime_object::_Runtime_object(void) __ptr64` | 18 | Exported Function
`public: __cdecl Concurrency::details::_SpinLock::~_SpinLock(void) __ptr64` | 90 | Exported Function
`public: __cdecl Concurrency::details::_StructuredTaskCollection::_StructuredTaskCollection(class Concurrency::details::_CancellationTokenState * __ptr64) __ptr64` | 23 | Exported Function
`public: __cdecl Concurrency::details::_StructuredTaskCollection::~_StructuredTaskCollection(void) __ptr64` | 91 | Exported Function
`public: __cdecl Concurrency::details::_SpinWait<0>::_SpinWait<0>(void (__cdecl*)(void)) __ptr64` | 2 | Exported Function
`public: __cdecl Concurrency::details::_SpinWait<1>::_SpinWait<1>(void (__cdecl*)(void)) __ptr64` | 1 | Exported Function
`public: __cdecl Concurrency::details::_ReaderWriterLock::_ReaderWriterLock(void) __ptr64` | 13 | Exported Function
`public: __cdecl Concurrency::details::_ReentrantBlockingLock::_ReentrantBlockingLock(void) __ptr64` | 14 | Exported Function
`public: __cdecl Concurrency::details::_NonReentrantPPLLock::_Scoped_lock::_Scoped_lock(class Concurrency::details::_NonReentrantPPLLock & __ptr64) __ptr64` | 20 | Exported Function
`public: __cdecl Concurrency::details::_NonReentrantPPLLock::_Scoped_lock::~_Scoped_lock(void) __ptr64` | 88 | Exported Function
`public: __cdecl Concurrency::details::_ReentrantBlockingLock::~_ReentrantBlockingLock(void) __ptr64` | 87 | Exported Function
`public: __cdecl Concurrency::details::_ReentrantPPLLock::_Scoped_lock::_Scoped_lock(class Concurrency::details::_ReentrantPPLLock & __ptr64) __ptr64` | 21 | Exported Function
`public: __cdecl Concurrency::details::_ReentrantPPLLock::_Scoped_lock::~_Scoped_lock(void) __ptr64` | 89 | Exported Function
`public: __cdecl Concurrency::details::_ReentrantLock::_ReentrantLock(void) __ptr64` | 15 | Exported Function
`public: __cdecl Concurrency::details::_ReentrantPPLLock::_ReentrantPPLLock(void) __ptr64` | 16 | Exported Function
`public: __cdecl Concurrency::improper_scheduler_reference::improper_scheduler_reference(char const * __ptr64) __ptr64` | 46 | Exported Function
`public: __cdecl Concurrency::improper_scheduler_reference::improper_scheduler_reference(void) __ptr64` | 47 | Exported Function
`public: __cdecl Concurrency::improper_scheduler_detach::improper_scheduler_detach(char const * __ptr64) __ptr64` | 44 | Exported Function
`public: __cdecl Concurrency::improper_scheduler_detach::improper_scheduler_detach(void) __ptr64` | 45 | Exported Function
`public: __cdecl Concurrency::invalid_link_target::invalid_link_target(char const * __ptr64) __ptr64` | 48 | Exported Function
`public: __cdecl Concurrency::invalid_multiple_scheduling::invalid_multiple_scheduling(void) __ptr64` | 51 | Exported Function
`public: __cdecl Concurrency::invalid_oversubscribe_operation::invalid_oversubscribe_operation(char const * __ptr64) __ptr64` | 52 | Exported Function
`public: __cdecl Concurrency::invalid_link_target::invalid_link_target(void) __ptr64` | 49 | Exported Function
`public: __cdecl Concurrency::invalid_multiple_scheduling::invalid_multiple_scheduling(char const * __ptr64) __ptr64` | 50 | Exported Function
`public: __cdecl Concurrency::details::_TaskCollection::~_TaskCollection(void) __ptr64` | 92 | Exported Function
`public: __cdecl Concurrency::event::event(void) __ptr64` | 39 | Exported Function
`public: __cdecl Concurrency::details::_TaskCollection::_TaskCollection(class Concurrency::details::_CancellationTokenState * __ptr64) __ptr64` | 24 | Exported Function
`public: __cdecl Concurrency::details::_TaskCollection::_TaskCollection(void) __ptr64` | 25 | Exported Function
`public: __cdecl Concurrency::event::~event(void) __ptr64` | 96 | Exported Function
`public: __cdecl Concurrency::improper_scheduler_attach::improper_scheduler_attach(char const * __ptr64) __ptr64` | 42 | Exported Function
`public: __cdecl Concurrency::improper_scheduler_attach::improper_scheduler_attach(void) __ptr64` | 43 | Exported Function
`public: __cdecl Concurrency::improper_lock::improper_lock(char const * __ptr64) __ptr64` | 40 | Exported Function
`public: __cdecl Concurrency::improper_lock::improper_lock(void) __ptr64` | 41 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000001529B409F5056997588000000000152`
* Thumbprint: `711AF71DC4C4952C8ED65BB4BA06826ED3922A32`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: concrt140.dll
* Product Name: Microsoft Visual Studio
* Company Name: Microsoft Corporation
* File Version: 14.26.28720.3 built by: vcwrkspc
* Product Version: 14.26.28720.3
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/8db33c1446c9eeab1a0969c52654ec6509ad9d11fe1c20089f76b09e12edf6b1/detection/




MIT License. Copyright (c) 2020 Strontic.


