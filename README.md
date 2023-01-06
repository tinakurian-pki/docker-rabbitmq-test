# docker-rabbitmq-test
### Run
```
docker compose -f docker-compose.hub.yaml up
```

<details><summary>The Output</summary>

```
Attaching to my-rabbitmq
my-rabbitmq  | 2023-01-06 13:22:22.840494+00:00 [error] <0.132.0> load_definitions invalid, file does not exist or cannot be read by the node
my-rabbitmq  | 2023-01-06 13:22:22.878300+00:00 [error] <0.132.0> Error preparing configuration in phase validation:
my-rabbitmq  | 2023-01-06 13:22:22.878358+00:00 [error] <0.132.0>   - load_definitions invalid, file does not exist or cannot be read by the node
my-rabbitmq  |
my-rabbitmq  | BOOT FAILED
my-rabbitmq  | ===========
my-rabbitmq  | Error during startup: {error,failed_to_prepare_configuration}
my-rabbitmq  |
my-rabbitmq  | 2023-01-06 13:22:22.883098+00:00 [error] <0.132.0>
my-rabbitmq  | 2023-01-06 13:22:22.883098+00:00 [error] <0.132.0> BOOT FAILED
my-rabbitmq  | 2023-01-06 13:22:22.883098+00:00 [error] <0.132.0> ===========
my-rabbitmq  | 2023-01-06 13:22:22.883098+00:00 [error] <0.132.0> Error during startup: {error,failed_to_prepare_configuration}
my-rabbitmq  | 2023-01-06 13:22:22.883098+00:00 [error] <0.132.0>
my-rabbitmq  | 2023-01-06 13:22:23.893869+00:00 [error] <0.132.0>     supervisor: {local,rabbit_prelaunch_sup}
my-rabbitmq  | 2023-01-06 13:22:23.893869+00:00 [error] <0.132.0>     errorContext: start_error
my-rabbitmq  | 2023-01-06 13:22:23.893869+00:00 [error] <0.132.0>     reason: failed_to_prepare_configuration
my-rabbitmq  | 2023-01-06 13:22:23.893869+00:00 [error] <0.132.0>     offender: [{pid,undefined},
my-rabbitmq  | 2023-01-06 13:22:23.893869+00:00 [error] <0.132.0>                {id,prelaunch},
my-rabbitmq  | 2023-01-06 13:22:23.893869+00:00 [error] <0.132.0>                {mfargs,{rabbit_prelaunch,run_prelaunch_first_phase,[]}},
my-rabbitmq  | 2023-01-06 13:22:23.893869+00:00 [error] <0.132.0>                {restart_type,transient},
my-rabbitmq  | 2023-01-06 13:22:23.893869+00:00 [error] <0.132.0>                {significant,false},
my-rabbitmq  | 2023-01-06 13:22:23.893869+00:00 [error] <0.132.0>                {shutdown,5000},
my-rabbitmq  | 2023-01-06 13:22:23.893869+00:00 [error] <0.132.0>                {child_type,worker}]
my-rabbitmq  | 2023-01-06 13:22:23.893869+00:00 [error] <0.132.0>
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>   crasher:
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     initial call: application_master:init/4
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     pid: <0.130.0>
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     registered_name: []
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     exception exit: {{shutdown,
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>                          {failed_to_start_child,prelaunch,
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>                              failed_to_prepare_configuration}},
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>                      {rabbit_prelaunch_app,start,[normal,[]]}}
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>       in function  application_master:init/4 (application_master.erl, line 142)
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     ancestors: [<0.129.0>]
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     message_queue_len: 1
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     messages: [{'EXIT',<0.131.0>,normal}]
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     links: [<0.129.0>,<0.44.0>]
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     dictionary: []
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     trap_exit: true
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     status: running
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     heap_size: 233
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     stack_size: 28
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>     reductions: 170
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>   neighbours:
my-rabbitmq  | 2023-01-06 13:22:23.894732+00:00 [error] <0.130.0>
my-rabbitmq  | 2023-01-06 13:22:23.906549+00:00 [notice] <0.44.0> Application rabbitmq_prelaunch exited with reason: {{shutdown,{failed_to_start_child,prelaunch,failed_to_prepare_configuration}},{rabbit_prelaunch_app,start,[normal,[]]}}
my-rabbitmq  | Kernel pid terminated (application_controller) ({application_start_failure,rabbitmq_prelaunch,{{shutdown,{failed_to_start_child,prelaunch,failed_to_prepare_configuration}},{rabbit_prelaunch_app,start,[normal,[]]}}})
my-rabbitmq  | {"Kernel pid terminated",application_controller,"{application_start_failure,rabbitmq_prelaunch,{{shutdown,{failed_to_start_child,prelaunch,failed_to_prepare_configuration}},{rabbit_prelaunch_app,start,[normal,[]]}}}"}
my-rabbitmq  |
my-rabbitmq exited with code 0

```

</details>
