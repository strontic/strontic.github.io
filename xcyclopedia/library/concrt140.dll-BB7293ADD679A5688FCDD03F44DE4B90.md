---
title: concrt140.dll | Microsoft Concurrency Runtime Library
excerpt: What is concrt140.dll?
---

# concrt140.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\concrt140.dll`
* Description: Microsoft Concurrency Runtime Library

## Hashes

Type | Hash
-- | --
MD5 | `BB7293ADD679A5688FCDD03F44DE4B90`
SHA1 | `4FFB7D8ACD1BFEC663D99694172C0C8C28A92900`
SHA256 | `F3093CB216BF8ECC8D869E46D8CDA3AACA28A326CB865CCBEF329E1B13ABC834`
SHA384 | `A691221B9C0CE9B77D3B76B5CE31AD1F29ECD822D559550D7AEC99FFA810FA7B797284CF6ED0570AC0D8889A428326BC`
SHA512 | `EA094064C1454CCEEC03B4F54AD122BE169C8BBFA6EECE9B4F58EB6D59CBEFA16AF3A9B6F04461E438E4C208B6224A69A15C10CCA6CF4CD5527CF0FE90052711`
SSDEEP | `6144:dTOKU/JVSHU3eFBp0xRe1o7qu0NdtB0ria/greG5Ioh812z/vyRAq:VUm1Zu0b0eaI5IkzET`
IMP | `9C31CF018A51D705B4FD0E596D3AC71D`
PESHA1 | `6643F5F25F34DDF3D6142A1BB6C47CE43E15B80C`
PE256 | `55638C16D01BFBABD6D476B27D5710B21B54B33CEAE8B8E9B7A3F1339C4C75A3`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: static unsigned int __cdecl Concurrency::details::_SpinCount::_Value(void)` | 257 | Exported Function
`public: static unsigned int __cdecl Concurrency::event::wait_for_multiple(class Concurrency::event * *,unsigned int,bool,unsigned int)` | 290 | Exported Function
`public: static unsigned int __cdecl Concurrency::details::_CurrentScheduler::_GetNumberOfVirtualProcessors(void)` | 192 | Exported Function
`public: static unsigned int __cdecl Concurrency::details::_CurrentScheduler::_Id(void)` | 194 | Exported Function
`public: static void __cdecl Concurrency::agent::wait_for_all(unsigned int,class Concurrency::agent * *,enum Concurrency::agent_status *,unsigned int)` | 289 | Exported Function
`public: static void __cdecl Concurrency::Context::Block(void)` | 112 | Exported Function
`public: static void __cdecl Concurrency::Context::Oversubscribe(bool)` | 146 | Exported Function
`public: static void __cdecl Concurrency::agent::wait_for_one(unsigned int,class Concurrency::agent * *,enum Concurrency::agent_status &,unsigned int &,unsigned int)` | 291 | Exported Function
`public: static void __cdecl Concurrency::Context::_SpinYield(void)` | 247 | Exported Function
`public: static class Concurrency::SchedulerPolicy __cdecl Concurrency::CurrentScheduler::GetPolicy(void)` | 131 | Exported Function
`public: static enum Concurrency::agent_status __cdecl Concurrency::agent::wait(class Concurrency::agent *,unsigned int)` | 286 | Exported Function
`public: static class Concurrency::Scheduler * __cdecl Concurrency::CurrentScheduler::Get(void)` | 127 | Exported Function
`public: static class Concurrency::Scheduler * __cdecl Concurrency::Scheduler::Create(class Concurrency::SchedulerPolicy const &)` | 118 | Exported Function
`public: static unsigned int __cdecl Concurrency::Context::Id(void)` | 137 | Exported Function
`public: static unsigned int __cdecl Concurrency::CurrentScheduler::GetNumberOfVirtualProcessors(void)` | 129 | Exported Function
`public: static unsigned int __cdecl Concurrency::CurrentScheduler::Id(void)` | 138 | Exported Function
`public: static unsigned int __cdecl Concurrency::Context::ScheduleGroupId(void)` | 154 | Exported Function
`public: static unsigned int __cdecl Concurrency::Context::VirtualProcessorId(void)` | 162 | Exported Function
`public: unsigned int __thiscall Concurrency::details::_Scheduler::_Reference(void)` | 222 | Exported Function
`public: unsigned int __thiscall Concurrency::details::_Scheduler::_Release(void)` | 228 | Exported Function
`public: static void __cdecl Concurrency::Scheduler::ResetDefaultSchedulerPolicy(void)` | 151 | Exported Function
`public: static void __cdecl Concurrency::Scheduler::SetDefaultSchedulerPolicy(class Concurrency::SchedulerPolicy const &)` | 159 | Exported Function
`public: unsigned int __thiscall Concurrency::event::wait(unsigned int)` | 287 | Exported Function
`public: virtual __thiscall Concurrency::agent::~agent(void)` | 94 | Exported Function
`public: void __thiscall Concurrency::critical_section::lock(void)` | 265 | Exported Function
`public: unsigned int __thiscall Concurrency::SchedulerPolicy::GetPolicyValue(enum Concurrency::PolicyElementKey)const ` | 132 | Exported Function
`public: unsigned int __thiscall Concurrency::SchedulerPolicy::SetPolicyValue(enum Concurrency::PolicyElementKey,unsigned int)` | 160 | Exported Function
`public: static void __cdecl Concurrency::CurrentScheduler::Detach(void)` | 123 | Exported Function
`public: static void __cdecl Concurrency::CurrentScheduler::RegisterShutdownEvent(void *)` | 150 | Exported Function
`public: static void __cdecl Concurrency::Context::Yield(void)` | 163 | Exported Function
`public: static void __cdecl Concurrency::CurrentScheduler::Create(class Concurrency::SchedulerPolicy const &)` | 117 | Exported Function
`public: static void __cdecl Concurrency::CurrentScheduler::ScheduleTask(void (__cdecl*)(void *),void *)` | 155 | Exported Function
`public: static void __cdecl Concurrency::details::_Context::_Yield(void)` | 258 | Exported Function
`public: static void __cdecl Concurrency::details::_CurrentScheduler::_ScheduleTask(void (__cdecl*)(void *),void *)` | 239 | Exported Function
`public: static void __cdecl Concurrency::CurrentScheduler::ScheduleTask(void (__cdecl*)(void *),void *,class Concurrency::location &)` | 156 | Exported Function
`public: static void __cdecl Concurrency::details::_Context::_Oversubscribe(bool)` | 221 | Exported Function
`public: bool __thiscall Concurrency::reader_writer_lock::try_lock(void)` | 279 | Exported Function
`public: bool __thiscall Concurrency::reader_writer_lock::try_lock_read(void)` | 281 | Exported Function
`public: bool __thiscall Concurrency::details::_StructuredTaskCollection::_IsCanceling(void)` | 215 | Exported Function
`public: bool __thiscall Concurrency::details::_TaskCollection::_IsCanceling(void)` | 216 | Exported Function
`public: class Concurrency::critical_section & __thiscall Concurrency::critical_section::native_handle(void)` | 268 | Exported Function
`public: class Concurrency::details::_SpinWait<1> & __thiscall Concurrency::details::_SpinWait<1>::operator=(class Concurrency::details::_SpinWait<1> &&)` | 101 | Exported Function
`public: class Concurrency::details::_SpinWait<1> & __thiscall Concurrency::details::_SpinWait<1>::operator=(class Concurrency::details::_SpinWait<1> const &)` | 102 | Exported Function
`public: class Concurrency::details::_SpinWait<0> & __thiscall Concurrency::details::_SpinWait<0>::operator=(class Concurrency::details::_SpinWait<0> &&)` | 103 | Exported Function
`public: class Concurrency::details::_SpinWait<0> & __thiscall Concurrency::details::_SpinWait<0>::operator=(class Concurrency::details::_SpinWait<0> const &)` | 104 | Exported Function
`public: bool __thiscall Concurrency::details::_Context::_IsSynchronouslyBlocked(void)const ` | 217 | Exported Function
`public: bool __thiscall Concurrency::details::_NonReentrantBlockingLock::_TryAcquire(void)` | 252 | Exported Function
`public: bool __thiscall Concurrency::details::_Cancellation_beacon::_Confirm_cancel(void)` | 181 | Exported Function
`public: bool __thiscall Concurrency::details::_Condition_variable::wait_for(class Concurrency::critical_section &,unsigned int)` | 288 | Exported Function
`public: bool __thiscall Concurrency::details::_ReaderWriterLock::_TryAcquireWrite(void)` | 255 | Exported Function
`public: bool __thiscall Concurrency::details::_SpinWait<0>::_SpinOnce(void)` | 246 | Exported Function
`public: bool __thiscall Concurrency::details::_SpinWait<1>::_SpinOnce(void)` | 245 | Exported Function
`public: bool __thiscall Concurrency::details::_ReentrantBlockingLock::_TryAcquire(void)` | 253 | Exported Function
`public: bool __thiscall Concurrency::details::_ReentrantLock::_TryAcquire(void)` | 254 | Exported Function
`public: static class Concurrency::details::_Context __cdecl Concurrency::details::_Context::_CurrentContext(void)` | 182 | Exported Function
`public: static class Concurrency::details::_Scheduler __cdecl Concurrency::details::_CurrentScheduler::_Get(void)` | 187 | Exported Function
`public: static class Concurrency::Context * __cdecl Concurrency::Context::CurrentContext(void)` | 122 | Exported Function
`public: static class Concurrency::details::_AsyncTaskCollection * __cdecl Concurrency::details::_AsyncTaskCollection::_NewCollection(class Concurrency::details::_CancellationTokenState *)` | 218 | Exported Function
`public: static class Concurrency::location __cdecl Concurrency::location::_Current_node(void)` | 183 | Exported Function
`public: static class Concurrency::ScheduleGroup * __cdecl Concurrency::CurrentScheduler::CreateScheduleGroup(class Concurrency::location &)` | 120 | Exported Function
`public: static class Concurrency::ScheduleGroup * __cdecl Concurrency::CurrentScheduler::CreateScheduleGroup(void)` | 121 | Exported Function
`public: static class Concurrency::location __cdecl Concurrency::location::current(void)` | 260 | Exported Function
`public: static class Concurrency::location __cdecl Concurrency::location::from_numa_node(unsigned short)` | 262 | Exported Function
`public: class Concurrency::SchedulerPolicy & __thiscall Concurrency::SchedulerPolicy::operator=(class Concurrency::SchedulerPolicy const &)` | 105 | Exported Function
`public: enum Concurrency::agent_status __thiscall Concurrency::agent::status(void)` | 276 | Exported Function
`public: class Concurrency::ISource<enum Concurrency::agent_status> * __thiscall Concurrency::agent::status_port(void)` | 277 | Exported Function
`public: class Concurrency::Scheduler * __thiscall Concurrency::details::_Scheduler::_GetScheduler(void)` | 193 | Exported Function
`public: enum Concurrency::details::_TaskCollectionStatus __stdcall Concurrency::details::_StructuredTaskCollection::_RunAndWait(class Concurrency::details::_UnrealizedChore *)` | 233 | Exported Function
`public: static bool __cdecl Concurrency::Context::IsCurrentTaskCollectionCanceling(void)` | 140 | Exported Function
`public: static bool __cdecl Concurrency::CurrentScheduler::IsAvailableLocation(class Concurrency::location const &)` | 139 | Exported Function
`public: enum Concurrency::details::_TaskCollectionStatus __stdcall Concurrency::details::_TaskCollection::_RunAndWait(class Concurrency::details::_UnrealizedChore *)` | 234 | Exported Function
`public: long __thiscall Concurrency::scheduler_resource_allocation_error::get_error_code(void)const ` | 263 | Exported Function
`public: void __thiscall Concurrency::critical_section::unlock(void)` | 282 | Exported Function
`struct _GUID const Concurrency::VirtualProcessorEventGuid` | 161 | Exported Function
`struct Concurrency::details::_CONCRT_TRACE_INFO const * __cdecl Concurrency::_GetConcRTTraceInfo(void)` | 189 | Exported Function
`struct _GUID const Concurrency::ScheduleGroupEventGuid` | 153 | Exported Function
`struct _GUID const Concurrency::SchedulerEventGuid` | 157 | Exported Function
`struct Concurrency::IResourceManager * __cdecl Concurrency::CreateResourceManager(void)` | 119 | Exported Function
`unsigned int __cdecl Concurrency::details::_GetConcurrency(void)` | 190 | Exported Function
`unsigned int __cdecl Concurrency::details::NFS_GetLineSize(void)` | 145 | Exported Function
`unsigned char const * const Concurrency::details::_Byte_reverse_table` | 174 | Exported Function
`unsigned int __cdecl Concurrency::details::_GetCombinableSize(void)` | 188 | Exported Function
`struct _GUID const Concurrency::ConcRTEventGuid` | 114 | Exported Function
`struct _GUID const Concurrency::ContextEventGuid` | 116 | Exported Function
`struct _GUID const Concurrency::ChoreEventGuid` | 113 | Exported Function
`struct _GUID const Concurrency::ConcRT_ProviderGuid` | 115 | Exported Function
`struct _GUID const Concurrency::LockEventGuid` | 141 | Exported Function
`struct _GUID const Concurrency::PPLParallelInvokeEventGuid` | 149 | Exported Function
`struct _GUID const Concurrency::ResourceManagerEventGuid` | 152 | Exported Function
`struct _GUID const Concurrency::PPLParallelForeachEventGuid` | 148 | Exported Function
`struct _GUID const Concurrency::PPLParallelForEventGuid` | 147 | Exported Function
`void __cdecl Concurrency::details::_ConcRT_Trace(int,wchar_t const *,...)` | 180 | Exported Function
`void __cdecl Concurrency::details::_UnderlyingYield(void)` | 256 | Exported Function
`void __cdecl Concurrency::_Trace_ppl_function(struct _GUID const &,unsigned char,enum Concurrency::ConcRT_EventType)` | 251 | Exported Function
`void __cdecl Concurrency::details::_ConcRT_CoreAssert(char const *,char const *,int)` | 179 | Exported Function
`void __cdecl Concurrency::details::NFS_Free(void *)` | 144 | Exported Function
`void __cdecl Concurrency::set_task_execution_resources(unsigned short,struct _GROUP_AFFINITY *)` | 273 | Exported Function
`void __cdecl Concurrency::wait(unsigned int)` | 284 | Exported Function
`void __cdecl Concurrency::Free(void *)` | 126 | Exported Function
`void __cdecl Concurrency::set_task_execution_resources(unsigned long)` | 274 | Exported Function
`unsigned int __cdecl Concurrency::GetProcessorNodeCount(void)` | 134 | Exported Function
`unsigned int __cdecl Concurrency::GetSchedulerId(void)` | 135 | Exported Function
`unsigned int __cdecl Concurrency::GetExecutionContextId(void)` | 128 | Exported Function
`unsigned int __cdecl Concurrency::GetProcessorCount(void)` | 133 | Exported Function
`unsigned long __cdecl Concurrency::details::Log2(unsigned int)` | 142 | Exported Function
`void * __cdecl Concurrency::details::NFS_Allocate(unsigned int,unsigned int,void *)` | 143 | Exported Function
`void __cdecl Concurrency::_Trace_agents(enum Concurrency::Agents_EventType,__int64,...)` | 250 | Exported Function
`void * __cdecl Concurrency::Alloc(unsigned int)` | 111 | Exported Function
`void * __cdecl Concurrency::details::GetSharedTimerQueue(void)` | 136 | Exported Function
`public: void __thiscall Concurrency::details::_ReaderWriterLock::_ReleaseWrite(void)` | 230 | Exported Function
`public: void __thiscall Concurrency::details::_ReentrantBlockingLock::_Acquire(void)` | 167 | Exported Function
`public: void __thiscall Concurrency::details::_ReaderWriterLock::_AcquireWrite(void)` | 171 | Exported Function
`public: void __thiscall Concurrency::details::_ReaderWriterLock::_ReleaseRead(void)` | 229 | Exported Function
`public: void __thiscall Concurrency::details::_ReentrantBlockingLock::_Release(void)` | 225 | Exported Function
`public: void __thiscall Concurrency::details::_ReentrantPPLLock::_Acquire(void *)` | 169 | Exported Function
`public: void __thiscall Concurrency::details::_ReentrantPPLLock::_Release(void)` | 227 | Exported Function
`public: void __thiscall Concurrency::details::_ReentrantLock::_Acquire(void)` | 168 | Exported Function
`public: void __thiscall Concurrency::details::_ReentrantLock::_Release(void)` | 226 | Exported Function
`public: void __thiscall Concurrency::details::_Condition_variable::wait(class Concurrency::critical_section &)` | 285 | Exported Function
`public: void __thiscall Concurrency::details::_Context::``default constructor closure'(void)` | 108 | Exported Function
`public: void __thiscall Concurrency::details::_Condition_variable::notify_all(void)` | 269 | Exported Function
`public: void __thiscall Concurrency::details::_Condition_variable::notify_one(void)` | 270 | Exported Function
`public: void __thiscall Concurrency::details::_NonReentrantBlockingLock::_Acquire(void)` | 165 | Exported Function
`public: void __thiscall Concurrency::details::_NonReentrantPPLLock::_Release(void)` | 224 | Exported Function
`public: void __thiscall Concurrency::details::_ReaderWriterLock::_AcquireRead(void)` | 170 | Exported Function
`public: void __thiscall Concurrency::details::_NonReentrantBlockingLock::_Release(void)` | 223 | Exported Function
`public: void __thiscall Concurrency::details::_NonReentrantPPLLock::_Acquire(void *)` | 166 | Exported Function
`public: void __thiscall Concurrency::event::reset(void)` | 271 | Exported Function
`public: void __thiscall Concurrency::event::set(void)` | 272 | Exported Function
`public: void __thiscall Concurrency::details::_TaskCollection::_Schedule(class Concurrency::details::_UnrealizedChore *)` | 237 | Exported Function
`public: void __thiscall Concurrency::details::_TaskCollection::_Schedule(class Concurrency::details::_UnrealizedChore *,class Concurrency::location *)` | 238 | Exported Function
`public: void __thiscall Concurrency::reader_writer_lock::lock(void)` | 266 | Exported Function
`public: void __thiscall Concurrency::SchedulerPolicy::SetConcurrencyLimits(unsigned int,unsigned int)` | 158 | Exported Function
`struct _GUID const Concurrency::AgentEventGuid` | 110 | Exported Function
`public: void __thiscall Concurrency::reader_writer_lock::lock_read(void)` | 267 | Exported Function
`public: void __thiscall Concurrency::reader_writer_lock::unlock(void)` | 283 | Exported Function
`public: void __thiscall Concurrency::details::_SpinWait<0>::``default constructor closure'(void)` | 107 | Exported Function
`public: void __thiscall Concurrency::details::_SpinWait<1>::_SetSpinCount(unsigned int)` | 241 | Exported Function
`public: void __thiscall Concurrency::details::_Scheduler::``default constructor closure'(void)` | 109 | Exported Function
`public: void __thiscall Concurrency::details::_SpinWait<0>::_SetSpinCount(unsigned int)` | 242 | Exported Function
`public: void __thiscall Concurrency::details::_SpinWait<1>::``default constructor closure'(void)` | 106 | Exported Function
`public: void __thiscall Concurrency::details::_StructuredTaskCollection::_Schedule(class Concurrency::details::_UnrealizedChore *,class Concurrency::location *)` | 236 | Exported Function
`public: void __thiscall Concurrency::details::_TaskCollection::_Cancel(void)` | 176 | Exported Function
`public: void __thiscall Concurrency::details::_StructuredTaskCollection::_Cancel(void)` | 175 | Exported Function
`public: void __thiscall Concurrency::details::_StructuredTaskCollection::_Schedule(class Concurrency::details::_UnrealizedChore *)` | 235 | Exported Function
`public: bool __thiscall Concurrency::critical_section::try_lock_for(unsigned int)` | 280 | Exported Function
`protected: void __thiscall Concurrency::details::_Timer::_Start(void)` | 248 | Exported Function
`protected: void __thiscall Concurrency::details::_Timer::_Stop(void)` | 249 | Exported Function
`protected: void __thiscall Concurrency::details::_SpinWait<1>::_DoYield(void)` | 185 | Exported Function
`protected: void __thiscall Concurrency::details::_SpinWait<1>::_Reset(void)` | 231 | Exported Function
`protected: void __thiscall Concurrency::details::_UnrealizedChore::_CheckTaskCollection(void)` | 177 | Exported Function
`public: __thiscall Concurrency::agent::agent(class Concurrency::Scheduler &)` | 28 | Exported Function
`public: __thiscall Concurrency::agent::agent(void)` | 29 | Exported Function
`public: __cdecl Concurrency::SchedulerPolicy::SchedulerPolicy(unsigned int,...)` | 3 | Exported Function
`public: __thiscall Concurrency::agent::agent(class Concurrency::ScheduleGroup &)` | 27 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_vector_base_v4::_Internal_copy(class Concurrency::details::_Concurrent_vector_base_v4 const &,unsigned int,void (__cdecl*)(void *,void const *,unsigned int))` | 199 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_vector_base_v4::_Internal_reserve(unsigned int,unsigned int,unsigned int)` | 208 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_queue_iterator_base_v4::_Assign(class Concurrency::details::_Concurrent_queue_iterator_base_v4 const &)` | 173 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_vector_base_v4::_Internal_assign(class Concurrency::details::_Concurrent_vector_base_v4 const &,unsigned int,void (__cdecl*)(void *,unsigned int),void (__cdecl*)(void *,void const *,unsigned int),void (__cdecl*)(void *,void const *,unsigned int))` | 195 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_vector_base_v4::_Internal_resize(unsigned int,unsigned int,unsigned int,void (__cdecl*)(void *,unsigned int),void (__cdecl*)(void *,void const *,unsigned int),void const *)` | 209 | Exported Function
`protected: void __thiscall Concurrency::details::_SpinWait<0>::_DoYield(void)` | 186 | Exported Function
`protected: void __thiscall Concurrency::details::_SpinWait<0>::_Reset(void)` | 232 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_vector_base_v4::_Internal_swap(class Concurrency::details::_Concurrent_vector_base_v4 &)` | 212 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_vector_base_v4::_Internal_throw_exception(unsigned int)const ` | 214 | Exported Function
`public: __thiscall Concurrency::default_scheduler_exists::default_scheduler_exists(void)` | 38 | Exported Function
`public: __thiscall Concurrency::details::_Cancellation_beacon::_Cancellation_beacon(void)` | 6 | Exported Function
`public: __thiscall Concurrency::critical_section::~critical_section(void)` | 95 | Exported Function
`public: __thiscall Concurrency::default_scheduler_exists::default_scheduler_exists(char const *)` | 37 | Exported Function
`public: __thiscall Concurrency::details::_Cancellation_beacon::~_Cancellation_beacon(void)` | 81 | Exported Function
`public: __thiscall Concurrency::details::_Context::_Context(class Concurrency::Context *)` | 10 | Exported Function
`public: __thiscall Concurrency::details::_NonReentrantBlockingLock::_NonReentrantBlockingLock(void)` | 11 | Exported Function
`public: __thiscall Concurrency::details::_Condition_variable::_Condition_variable(void)` | 9 | Exported Function
`public: __thiscall Concurrency::details::_Condition_variable::~_Condition_variable(void)` | 85 | Exported Function
`public: __thiscall Concurrency::context_self_unblock::context_self_unblock(char const *)` | 32 | Exported Function
`public: __thiscall Concurrency::context_self_unblock::context_self_unblock(void)` | 33 | Exported Function
`public: __thiscall Concurrency::bad_target::bad_target(char const *)` | 30 | Exported Function
`public: __thiscall Concurrency::bad_target::bad_target(void)` | 31 | Exported Function
`public: __thiscall Concurrency::context_unblock_unbalanced::context_unblock_unbalanced(char const *)` | 34 | Exported Function
`public: __thiscall Concurrency::critical_section::scoped_lock::scoped_lock(class Concurrency::critical_section &)` | 75 | Exported Function
`public: __thiscall Concurrency::critical_section::scoped_lock::~scoped_lock(void)` | 98 | Exported Function
`public: __thiscall Concurrency::context_unblock_unbalanced::context_unblock_unbalanced(void)` | 35 | Exported Function
`public: __thiscall Concurrency::critical_section::critical_section(void)` | 36 | Exported Function
`protected: __thiscall Concurrency::details::_Concurrent_vector_base_v4::~_Concurrent_vector_base_v4(void)` | 84 | Exported Function
`protected: __thiscall Concurrency::details::_Timer::_Timer(unsigned int,bool)` | 26 | Exported Function
`protected: __thiscall Concurrency::details::_Concurrent_queue_iterator_base_v4::_Concurrent_queue_iterator_base_v4(class Concurrency::details::_Concurrent_queue_base_v4 const &)` | 8 | Exported Function
`protected: __thiscall Concurrency::details::_Concurrent_queue_iterator_base_v4::~_Concurrent_queue_iterator_base_v4(void)` | 83 | Exported Function
`protected: bool __thiscall Concurrency::agent::done(void)` | 261 | Exported Function
`protected: bool __thiscall Concurrency::details::_SpinWait<0>::_ShouldSpinAgain(void)` | 244 | Exported Function
`protected: bool __thiscall Concurrency::details::_SpinWait<1>::_ShouldSpinAgain(void)` | 243 | Exported Function
`protected: bool __thiscall Concurrency::details::_Concurrent_queue_base_v4::_Internal_empty(void)const ` | 200 | Exported Function
`protected: bool __thiscall Concurrency::details::_Concurrent_queue_base_v4::_Internal_pop_if_present(void *)` | 205 | Exported Function
`long __cdecl Concurrency::DisableTracing(void)` | 124 | Exported Function
`long __cdecl Concurrency::EnableTracing(void)` | 125 | Exported Function
`bool __cdecl Concurrency::is_current_task_group_canceling(void)` | 264 | Exported Function
`enum Concurrency::IResourceManager::OSVersion __cdecl Concurrency::GetOSVersion(void)` | 130 | Exported Function
`private: static unsigned int & __cdecl Concurrency::details::_StackGuard::_GetCurrentInlineDepth(void)` | 191 | Exported Function
`private: void __thiscall Concurrency::details::_StructuredTaskCollection::_CleanupToken(void)` | 178 | Exported Function
`protected: __thiscall Concurrency::details::_Concurrent_queue_base_v4::_Concurrent_queue_base_v4(unsigned int)` | 7 | Exported Function
`private: virtual void __thiscall Concurrency::details::_AsyncTaskCollection::_Destroy(void)` | 184 | Exported Function
`private: void __thiscall Concurrency::details::_StructuredTaskCollection::_Abort(void)` | 164 | Exported Function
`protected: void * __thiscall Concurrency::details::_Concurrent_vector_base_v4::_Internal_push_back(unsigned int,unsigned int &)` | 207 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_queue_base_v4::_Internal_finish_clear(void)` | 201 | Exported Function
`protected: virtual __thiscall Concurrency::details::_Timer::~_Timer(void)` | 93 | Exported Function
`protected: void * __thiscall Concurrency::details::_Concurrent_vector_base_v4::_Internal_compact(unsigned int,void *,void (__cdecl*)(void *,unsigned int),void (__cdecl*)(void *,void const *,unsigned int))` | 198 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_queue_base_v4::_Internal_move_push(void *)` | 204 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_queue_base_v4::_Internal_throw_exception(void)const ` | 213 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_queue_iterator_base_v4::_Advance(void)` | 172 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_queue_base_v4::_Internal_push(void const *)` | 206 | Exported Function
`protected: void __thiscall Concurrency::details::_Concurrent_queue_base_v4::_Internal_swap(class Concurrency::details::_Concurrent_queue_base_v4 &)` | 211 | Exported Function
`protected: unsigned int __thiscall Concurrency::details::_Concurrent_vector_base_v4::_Internal_capacity(void)const ` | 196 | Exported Function
`protected: unsigned int __thiscall Concurrency::details::_Concurrent_vector_base_v4::_Internal_clear(void (__cdecl*)(void *,unsigned int))` | 197 | Exported Function
`protected: static unsigned int __cdecl Concurrency::details::_Concurrent_vector_base_v4::_Segment_index_of(unsigned int)` | 240 | Exported Function
`protected: unsigned int __thiscall Concurrency::details::_Concurrent_queue_base_v4::_Internal_size(void)const ` | 210 | Exported Function
`protected: unsigned int __thiscall Concurrency::details::_Concurrent_vector_base_v4::_Internal_grow_by(unsigned int,unsigned int,void (__cdecl*)(void *,void const *,unsigned int),void const *)` | 202 | Exported Function
`protected: unsigned long __thiscall Concurrency::details::_SpinWait<1>::_NumberOfSpins(void)` | 219 | Exported Function
`protected: virtual __thiscall Concurrency::details::_Concurrent_queue_base_v4::~_Concurrent_queue_base_v4(void)` | 82 | Exported Function
`protected: unsigned int __thiscall Concurrency::details::_Concurrent_vector_base_v4::_Internal_grow_to_at_least_with_result(unsigned int,unsigned int,void (__cdecl*)(void *,void const *,unsigned int),void const *)` | 203 | Exported Function
`protected: unsigned long __thiscall Concurrency::details::_SpinWait<0>::_NumberOfSpins(void)` | 220 | Exported Function
`public: __thiscall Concurrency::details::_NonReentrantBlockingLock::~_NonReentrantBlockingLock(void)` | 86 | Exported Function
`public: __thiscall Concurrency::missing_wait::missing_wait(void)` | 63 | Exported Function
`public: __thiscall Concurrency::nested_scheduler_missing_detach::nested_scheduler_missing_detach(char const *)` | 64 | Exported Function
`public: __thiscall Concurrency::message_not_found::message_not_found(void)` | 61 | Exported Function
`public: __thiscall Concurrency::missing_wait::missing_wait(char const *)` | 62 | Exported Function
`public: __thiscall Concurrency::nested_scheduler_missing_detach::nested_scheduler_missing_detach(void)` | 65 | Exported Function
`public: __thiscall Concurrency::reader_writer_lock::reader_writer_lock(void)` | 68 | Exported Function
`public: __thiscall Concurrency::reader_writer_lock::scoped_lock::scoped_lock(class Concurrency::reader_writer_lock &)` | 76 | Exported Function
`public: __thiscall Concurrency::operation_timed_out::operation_timed_out(char const *)` | 66 | Exported Function
`public: __thiscall Concurrency::operation_timed_out::operation_timed_out(void)` | 67 | Exported Function
`public: __thiscall Concurrency::invalid_scheduler_policy_key::invalid_scheduler_policy_key(char const *)` | 54 | Exported Function
`public: __thiscall Concurrency::invalid_scheduler_policy_key::invalid_scheduler_policy_key(void)` | 55 | Exported Function
`public: __thiscall Concurrency::invalid_oversubscribe_operation::invalid_oversubscribe_operation(char const *)` | 52 | Exported Function
`public: __thiscall Concurrency::invalid_oversubscribe_operation::invalid_oversubscribe_operation(void)` | 53 | Exported Function
`public: __thiscall Concurrency::invalid_scheduler_policy_thread_specification::invalid_scheduler_policy_thread_specification(char const *)` | 56 | Exported Function
`public: __thiscall Concurrency::invalid_scheduler_policy_value::invalid_scheduler_policy_value(void)` | 59 | Exported Function
`public: __thiscall Concurrency::message_not_found::message_not_found(char const *)` | 60 | Exported Function
`public: __thiscall Concurrency::invalid_scheduler_policy_thread_specification::invalid_scheduler_policy_thread_specification(void)` | 57 | Exported Function
`public: __thiscall Concurrency::invalid_scheduler_policy_value::invalid_scheduler_policy_value(char const *)` | 58 | Exported Function
`public: __thiscall Concurrency::SchedulerPolicy::SchedulerPolicy(void)` | 5 | Exported Function
`public: __thiscall Concurrency::SchedulerPolicy::~SchedulerPolicy(void)` | 80 | Exported Function
`public: __thiscall Concurrency::scheduler_worker_creation_error::scheduler_worker_creation_error(long)` | 73 | Exported Function
`public: __thiscall Concurrency::SchedulerPolicy::SchedulerPolicy(class Concurrency::SchedulerPolicy const &)` | 4 | Exported Function
`public: __thiscall Concurrency::unsupported_os::unsupported_os(char const *)` | 78 | Exported Function
`public: bool __thiscall Concurrency::agent::start(void)` | 275 | Exported Function
`public: bool __thiscall Concurrency::critical_section::try_lock(void)` | 278 | Exported Function
`public: __thiscall Concurrency::unsupported_os::unsupported_os(void)` | 79 | Exported Function
`public: bool __thiscall Concurrency::agent::cancel(void)` | 259 | Exported Function
`public: __thiscall Concurrency::reader_writer_lock::scoped_lock_read::~scoped_lock_read(void)` | 100 | Exported Function
`public: __thiscall Concurrency::reader_writer_lock::~reader_writer_lock(void)` | 97 | Exported Function
`public: __thiscall Concurrency::reader_writer_lock::scoped_lock::~scoped_lock(void)` | 99 | Exported Function
`public: __thiscall Concurrency::reader_writer_lock::scoped_lock_read::scoped_lock_read(class Concurrency::reader_writer_lock &)` | 77 | Exported Function
`public: __thiscall Concurrency::scheduler_not_attached::scheduler_not_attached(char const *)` | 69 | Exported Function
`public: __thiscall Concurrency::scheduler_resource_allocation_error::scheduler_resource_allocation_error(long)` | 71 | Exported Function
`public: __thiscall Concurrency::scheduler_worker_creation_error::scheduler_worker_creation_error(char const *,long)` | 74 | Exported Function
`public: __thiscall Concurrency::scheduler_not_attached::scheduler_not_attached(void)` | 70 | Exported Function
`public: __thiscall Concurrency::scheduler_resource_allocation_error::scheduler_resource_allocation_error(char const *,long)` | 72 | Exported Function
`public: __thiscall Concurrency::details::_Runtime_object::_Runtime_object(void)` | 18 | Exported Function
`public: __thiscall Concurrency::details::_Scheduler::_Scheduler(class Concurrency::Scheduler *)` | 19 | Exported Function
`public: __thiscall Concurrency::details::_ReentrantPPLLock::_Scoped_lock::~_Scoped_lock(void)` | 89 | Exported Function
`public: __thiscall Concurrency::details::_Runtime_object::_Runtime_object(int)` | 17 | Exported Function
`public: __thiscall Concurrency::details::_SpinLock::_SpinLock(long volatile &)` | 22 | Exported Function
`public: __thiscall Concurrency::details::_SpinWait<1>::_SpinWait<1>(void (__cdecl*)(void))` | 1 | Exported Function
`public: __thiscall Concurrency::details::_StructuredTaskCollection::_StructuredTaskCollection(class Concurrency::details::_CancellationTokenState *)` | 23 | Exported Function
`public: __thiscall Concurrency::details::_SpinLock::~_SpinLock(void)` | 90 | Exported Function
`public: __thiscall Concurrency::details::_SpinWait<0>::_SpinWait<0>(void (__cdecl*)(void))` | 2 | Exported Function
`public: __thiscall Concurrency::details::_NonReentrantPPLLock::_Scoped_lock::~_Scoped_lock(void)` | 88 | Exported Function
`public: __thiscall Concurrency::details::_ReaderWriterLock::_ReaderWriterLock(void)` | 13 | Exported Function
`public: __thiscall Concurrency::details::_NonReentrantPPLLock::_NonReentrantPPLLock(void)` | 12 | Exported Function
`public: __thiscall Concurrency::details::_NonReentrantPPLLock::_Scoped_lock::_Scoped_lock(class Concurrency::details::_NonReentrantPPLLock &)` | 20 | Exported Function
`public: __thiscall Concurrency::details::_ReentrantBlockingLock::_ReentrantBlockingLock(void)` | 14 | Exported Function
`public: __thiscall Concurrency::details::_ReentrantPPLLock::_ReentrantPPLLock(void)` | 16 | Exported Function
`public: __thiscall Concurrency::details::_ReentrantPPLLock::_Scoped_lock::_Scoped_lock(class Concurrency::details::_ReentrantPPLLock &)` | 21 | Exported Function
`public: __thiscall Concurrency::details::_ReentrantBlockingLock::~_ReentrantBlockingLock(void)` | 87 | Exported Function
`public: __thiscall Concurrency::details::_ReentrantLock::_ReentrantLock(void)` | 15 | Exported Function
`public: __thiscall Concurrency::improper_scheduler_detach::improper_scheduler_detach(void)` | 45 | Exported Function
`public: __thiscall Concurrency::improper_scheduler_reference::improper_scheduler_reference(char const *)` | 46 | Exported Function
`public: __thiscall Concurrency::improper_scheduler_attach::improper_scheduler_attach(void)` | 43 | Exported Function
`public: __thiscall Concurrency::improper_scheduler_detach::improper_scheduler_detach(char const *)` | 44 | Exported Function
`public: __thiscall Concurrency::improper_scheduler_reference::improper_scheduler_reference(void)` | 47 | Exported Function
`public: __thiscall Concurrency::invalid_multiple_scheduling::invalid_multiple_scheduling(char const *)` | 50 | Exported Function
`public: __thiscall Concurrency::invalid_multiple_scheduling::invalid_multiple_scheduling(void)` | 51 | Exported Function
`public: __thiscall Concurrency::invalid_link_target::invalid_link_target(char const *)` | 48 | Exported Function
`public: __thiscall Concurrency::invalid_link_target::invalid_link_target(void)` | 49 | Exported Function
`public: __thiscall Concurrency::details::_TaskCollection::_TaskCollection(void)` | 25 | Exported Function
`public: __thiscall Concurrency::details::_TaskCollection::~_TaskCollection(void)` | 92 | Exported Function
`public: __thiscall Concurrency::details::_StructuredTaskCollection::~_StructuredTaskCollection(void)` | 91 | Exported Function
`public: __thiscall Concurrency::details::_TaskCollection::_TaskCollection(class Concurrency::details::_CancellationTokenState *)` | 24 | Exported Function
`public: __thiscall Concurrency::event::event(void)` | 39 | Exported Function
`public: __thiscall Concurrency::improper_lock::improper_lock(void)` | 41 | Exported Function
`public: __thiscall Concurrency::improper_scheduler_attach::improper_scheduler_attach(char const *)` | 42 | Exported Function
`public: __thiscall Concurrency::event::~event(void)` | 96 | Exported Function
`public: __thiscall Concurrency::improper_lock::improper_lock(char const *)` | 40 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000010A2C79AED7797BA6AC00010000010A`
* Thumbprint: `3BDA323E552DB1FDE5F4FBEE75D6D5B2B187EEDC`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: concrt140.dll
* Product Name: Microsoft Visual Studio 2015
* Company Name: Microsoft Corporation
* File Version: 14.00.24210.0 built by: VCTOOLSREL
* Product Version: 14.00.24210.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/f3093cb216bf8ecc8d869e46d8cda3aaca28a326cb865ccbef329e1b13abc834/detection/




MIT License. Copyright (c) 2020 Strontic.


