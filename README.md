# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-22 01:09:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 14567.2 (4h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214025
telemt_connections_bad_total 15035
telemt_connections_current 644
telemt_connections_me_current 644
telemt_handshake_timeouts_total 12348
telemt_upstream_connect_attempt_total 6067
telemt_upstream_connect_success_total 6066
telemt_upstream_connect_attempts_per_request{bucket="1"} 6066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 209
telemt_me_reconnect_success_total 101
telemt_me_reader_eof_total 97
telemt_me_idle_close_by_peer_total 97
telemt_me_route_drop_no_conn_total 40756
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174517
telemt_me_endpoint_quarantine_total 115
telemt_me_single_endpoint_shadow_rotate_total 128
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 1438
telemt_desync_full_logged_total 393
telemt_desync_suppressed_total 1045
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 518
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 16
telemt_pool_force_close_total 396
telemt_me_writer_close_signal_drop_total 29
telemt_me_draining_writers_reap_progress_total 5403
telemt_me_writer_removed_unexpected_total 99
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 395
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5095
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 392
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5007
telemt_me_writer_teardown_success_total{mode="normal"} 5490
telemt_me_writer_teardown_noop_total 5404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10894
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.828498
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10894
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 29
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 93
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 174249
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 1935320108 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 57914434076 (53.94 GB)
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 27933.4 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 722510
telemt_connections_bad_total 41395
telemt_connections_current 768
telemt_connections_me_current 768
telemt_handshake_timeouts_total 27085
telemt_upstream_connect_attempt_total 12238
telemt_upstream_connect_success_total 12034
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 12218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_reconnect_attempts_total 1081
telemt_me_reconnect_success_total 361
telemt_me_reader_eof_total 313
telemt_me_idle_close_by_peer_total 313
telemt_me_route_drop_no_conn_total 332903
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580797
telemt_me_endpoint_quarantine_total 256
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 224
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 4
telemt_desync_total 2537
telemt_desync_full_logged_total 1453
telemt_desync_suppressed_total 1084
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 945
telemt_desync_frames_bucket_total{bucket="gt_10"} 1045
telemt_pool_swap_total 30
telemt_pool_force_close_total 821
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 10800
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 915
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10185
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 814
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9979
telemt_me_writer_teardown_success_total{mode="normal"} 11100
telemt_me_writer_teardown_noop_total 10800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21900
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.460113
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21900
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 251
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 579943
telemt_user_connections_current{user="hello"} 768
telemt_user_octets_from_client{user="hello"} 9772805304 (9.10 GB)
telemt_user_octets_to_client{user="hello"} 205137923052 (191.05 GB)
telemt_user_unique_ips_current{user="hello"} 498
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 102793.3 (28h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7572485
telemt_connections_bad_total 613597
telemt_connections_current 1102
telemt_connections_me_current 1102
telemt_handshake_timeouts_total 247163
telemt_upstream_connect_attempt_total 37653
telemt_upstream_connect_success_total 37581
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 37588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20411
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1539
telemt_me_reconnect_success_total 775
telemt_me_reader_eof_total 786
telemt_me_idle_close_by_peer_total 786
telemt_me_route_drop_no_conn_total 4514983
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6157282
telemt_me_endpoint_quarantine_total 654
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 765
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 26123
telemt_desync_full_logged_total 8632
telemt_desync_suppressed_total 17491
telemt_desync_frames_bucket_total{bucket="1_2"} 5623
telemt_desync_frames_bucket_total{bucket="3_10"} 10191
telemt_desync_frames_bucket_total{bucket="gt_10"} 10309
telemt_pool_swap_total 111
telemt_pool_force_close_total 3731
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 589
telemt_me_draining_writers_reap_progress_total 34360
telemt_me_writer_removed_unexpected_total 756
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2891
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31768
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3492
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30629
telemt_me_writer_teardown_success_total{mode="normal"} 34659
telemt_me_writer_teardown_noop_total 34404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69063
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 156.359877
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69063
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 589
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 692
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6149555
telemt_user_connections_current{user="hello"} 1102
telemt_user_octets_from_client{user="hello"} 105338309544 (98.10 GB)
telemt_user_octets_to_client{user="hello"} 2036674775136 (1.85 TB)
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 495
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 102794.6 (28h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6235119
telemt_connections_bad_total 581880
telemt_connections_current 977
telemt_connections_me_current 977
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 207025
telemt_upstream_connect_attempt_total 41749
telemt_upstream_connect_success_total 41365
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 41552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1887
telemt_me_reconnect_success_total 835
telemt_me_reader_eof_total 804
telemt_me_idle_close_by_peer_total 804
telemt_me_route_drop_no_conn_total 2217833
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4672269
telemt_me_endpoint_quarantine_total 636
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 786
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 22306
telemt_desync_full_logged_total 7568
telemt_desync_suppressed_total 14738
telemt_desync_frames_bucket_total{bucket="1_2"} 5377
telemt_desync_frames_bucket_total{bucket="3_10"} 8649
telemt_desync_frames_bucket_total{bucket="gt_10"} 8280
telemt_pool_swap_total 112
telemt_pool_force_close_total 3367
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 32985
telemt_me_writer_removed_unexpected_total 790
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2808
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30903
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3154
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29618
telemt_me_writer_teardown_success_total{mode="normal"} 33711
telemt_me_writer_teardown_noop_total 32991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66702
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.198524
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66702
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 727
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4604430
telemt_user_connections_current{user="hello"} 977
telemt_user_octets_from_client{user="hello"} 139141681265 (129.59 GB)
telemt_user_octets_to_client{user="hello"} 2162107383891 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 391
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 102758.8 (28h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6135128
telemt_connections_bad_total 543037
telemt_connections_current 1714
telemt_connections_me_current 1714
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 196654
telemt_upstream_connect_attempt_total 48066
telemt_upstream_connect_success_total 47734
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1935
telemt_me_reconnect_success_total 863
telemt_me_reader_eof_total 805
telemt_me_idle_close_by_peer_total 805
telemt_me_route_drop_no_conn_total 2120513
telemt_me_route_drop_channel_closed_total 113
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4572281
telemt_me_endpoint_quarantine_total 714
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 768
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 22124
telemt_desync_full_logged_total 7402
telemt_desync_suppressed_total 14722
telemt_desync_frames_bucket_total{bucket="1_2"} 5404
telemt_desync_frames_bucket_total{bucket="3_10"} 8474
telemt_desync_frames_bucket_total{bucket="gt_10"} 8246
telemt_pool_swap_total 111
telemt_pool_force_close_total 3221
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 34324
telemt_me_writer_removed_unexpected_total 780
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2859
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32256
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3006
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31103
telemt_me_writer_teardown_success_total{mode="normal"} 35115
telemt_me_writer_teardown_noop_total 34335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69450
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.693772
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69450
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 747
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4573021
telemt_user_connections_current{user="hello"} 1714
telemt_user_octets_from_client{user="hello"} 132588077023 (123.48 GB)
telemt_user_octets_to_client{user="hello"} 2087792901451 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 846
telemt_user_unique_ips_recent_window{user="hello"} 305
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 102798.4 (28h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20168810
telemt_connections_bad_total 1538664
telemt_connections_current 1987
telemt_connections_me_current 1987
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 589682
telemt_upstream_connect_attempt_total 190936
telemt_upstream_connect_success_total 173238
telemt_upstream_connect_fail_total 16052
telemt_upstream_connect_attempts_per_request{bucket="1"} 189290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40999
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8890
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16052
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64561
telemt_me_reconnect_success_total 2210
telemt_me_reader_eof_total 1392
telemt_me_idle_close_by_peer_total 1391
telemt_me_route_drop_no_conn_total 39476580
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16367270
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 798
telemt_me_single_endpoint_outage_enter_total 125
telemt_me_single_endpoint_outage_exit_total 125
telemt_me_single_endpoint_outage_reconnect_attempt_total 261
telemt_me_single_endpoint_outage_reconnect_success_total 64
telemt_me_single_endpoint_quarantine_bypass_total 261
telemt_me_single_endpoint_shadow_rotate_total 802
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 31677
telemt_desync_full_logged_total 9460
telemt_desync_suppressed_total 22217
telemt_desync_frames_bucket_total{bucket="1_2"} 6877
telemt_desync_frames_bucket_total{bucket="3_10"} 14060
telemt_desync_frames_bucket_total{bucket="gt_10"} 10740
telemt_pool_swap_total 106
telemt_pool_force_close_total 3464
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 772
telemt_me_draining_writers_reap_progress_total 32037
telemt_me_writer_removed_unexpected_total 2051
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4333
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29491
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 522
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28573
telemt_me_writer_teardown_success_total{mode="normal"} 33824
telemt_me_writer_teardown_noop_total 32063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65887
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.861775
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65887
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 772
telemt_me_refill_failed_total 3797
telemt_me_writer_restored_same_endpoint_total 1530
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 500
telemt_user_connections_total{user="hello"} 16494864
telemt_user_connections_current{user="hello"} 1987
telemt_user_octets_from_client{user="hello"} 200404925984 (186.64 GB)
telemt_user_octets_to_client{user="hello"} 1157182232746 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 959
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 102765.3 (28h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5909866
telemt_connections_bad_total 555733
telemt_connections_current 1496
telemt_connections_me_current 1496
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 122956
telemt_upstream_connect_attempt_total 56313
telemt_upstream_connect_success_total 55651
telemt_upstream_connect_fail_total 567
telemt_upstream_connect_attempts_per_request{bucket="1"} 56218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22450
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 567
telemt_me_reconnect_attempts_total 69508
telemt_me_reconnect_success_total 1742
telemt_me_reader_eof_total 1514
telemt_me_idle_close_by_peer_total 1513
telemt_me_route_drop_no_conn_total 2371756
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4609862
telemt_me_endpoint_quarantine_total 696
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 772
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 23163
telemt_desync_full_logged_total 8126
telemt_desync_suppressed_total 15037
telemt_desync_frames_bucket_total{bucket="1_2"} 4396
telemt_desync_frames_bucket_total{bucket="3_10"} 8965
telemt_desync_frames_bucket_total{bucket="gt_10"} 9802
telemt_pool_swap_total 106
telemt_pool_force_close_total 3066
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 384
telemt_me_draining_writers_reap_progress_total 35758
telemt_me_writer_removed_unexpected_total 1558
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3755
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2665
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32692
telemt_me_writer_teardown_success_total{mode="normal"} 37341
telemt_me_writer_teardown_noop_total 35759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73100
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.048215
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73100
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 384
telemt_me_refill_failed_total 4200
telemt_me_writer_restored_same_endpoint_total 1460
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 4602888
telemt_user_connections_current{user="hello"} 1496
telemt_user_octets_from_client{user="hello"} 123013203180 (114.56 GB)
telemt_user_octets_to_client{user="hello"} 1882539054030 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 39601.2 (11h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3799072
telemt_connections_bad_total 138276
telemt_connections_current 1135
telemt_connections_me_current 1135
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1567541
telemt_upstream_connect_attempt_total 24574
telemt_upstream_connect_success_total 24415
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 24567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 45724
telemt_me_reconnect_success_total 920
telemt_me_reader_eof_total 595
telemt_me_idle_close_by_peer_total 595
telemt_me_route_drop_no_conn_total 1007458
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1846330
telemt_me_endpoint_quarantine_total 290
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 298
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10140
telemt_desync_full_logged_total 3492
telemt_desync_suppressed_total 6648
telemt_desync_frames_bucket_total{bucket="1_2"} 1807
telemt_desync_frames_bucket_total{bucket="3_10"} 3874
telemt_desync_frames_bucket_total{bucket="gt_10"} 4459
telemt_pool_swap_total 42
telemt_pool_force_close_total 1347
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 13877
telemt_me_writer_removed_unexpected_total 674
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1384
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13188
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1141
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12530
telemt_me_writer_teardown_success_total{mode="normal"} 14572
telemt_me_writer_teardown_noop_total 13879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28451
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.299605
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28451
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 2603
telemt_me_writer_restored_same_endpoint_total 823
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1850047
telemt_user_connections_current{user="hello"} 1135
telemt_user_octets_from_client{user="hello"} 53296239460 (49.64 GB)
telemt_user_octets_to_client{user="hello"} 792891372450 (738.44 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 20572.3 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175051
telemt_connections_bad_total 1492
telemt_connections_current 268
telemt_connections_me_current 268
telemt_handshake_timeouts_total 4817
telemt_upstream_connect_attempt_total 9718
telemt_upstream_connect_success_total 9694
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 9716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 213
telemt_me_reconnect_success_total 129
telemt_me_reader_eof_total 130
telemt_me_idle_close_by_peer_total 130
telemt_me_route_drop_no_conn_total 48558
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153746
telemt_me_endpoint_quarantine_total 202
telemt_me_single_endpoint_shadow_rotate_total 180
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 996
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 747
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 364
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 22
telemt_pool_force_close_total 495
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 8743
telemt_me_writer_removed_unexpected_total 127
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 578
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8295
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 493
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8248
telemt_me_writer_teardown_success_total{mode="normal"} 8873
telemt_me_writer_teardown_noop_total 8743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17616
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.868479
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17616
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 118
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 153457
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 2859548596 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 90880855120 (84.64 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 102769.8 (28h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7149331
telemt_connections_bad_total 727047
telemt_connections_current 1746
telemt_connections_me_current 1746
telemt_handshake_timeouts_total 203986
telemt_upstream_connect_attempt_total 39785
telemt_upstream_connect_success_total 39632
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 39748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_reconnect_attempts_total 1529
telemt_me_reconnect_success_total 814
telemt_me_reader_eof_total 796
telemt_me_idle_close_by_peer_total 796
telemt_me_route_drop_no_conn_total 2109500
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5383529
telemt_me_endpoint_quarantine_total 713
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 789
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 20869
telemt_desync_full_logged_total 6955
telemt_desync_suppressed_total 13914
telemt_desync_frames_bucket_total{bucket="1_2"} 5100
telemt_desync_frames_bucket_total{bucket="3_10"} 7555
telemt_desync_frames_bucket_total{bucket="gt_10"} 8214
telemt_pool_swap_total 114
telemt_pool_force_close_total 3064
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 35826
telemt_me_writer_removed_unexpected_total 767
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2867
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33745
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2976
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32762
telemt_me_writer_teardown_success_total{mode="normal"} 36612
telemt_me_writer_teardown_noop_total 35828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72440
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.592506
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72440
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 724
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5358638
telemt_user_connections_current{user="hello"} 1746
telemt_user_octets_from_client{user="hello"} 108324660752 (100.89 GB)
telemt_user_octets_to_client{user="hello"} 2509560300792 (2.28 TB)
telemt_user_unique_ips_current{user="hello"} 769
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 102766.2 (28h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6163735
telemt_connections_bad_total 608142
telemt_connections_current 1565
telemt_connections_me_current 1565
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 169583
telemt_upstream_connect_attempt_total 55629
telemt_upstream_connect_success_total 55211
telemt_upstream_connect_fail_total 359
telemt_upstream_connect_attempts_per_request{bucket="1"} 55570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 359
telemt_me_reconnect_attempts_total 5439
telemt_me_reconnect_success_total 1128
telemt_me_reader_eof_total 1011
telemt_me_idle_close_by_peer_total 1011
telemt_me_seq_mismatch_total 44
telemt_me_route_drop_no_conn_total 2163685
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4752570
telemt_me_endpoint_quarantine_total 824
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 784
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 19566
telemt_desync_full_logged_total 6581
telemt_desync_suppressed_total 12985
telemt_desync_frames_bucket_total{bucket="1_2"} 4897
telemt_desync_frames_bucket_total{bucket="3_10"} 7117
telemt_desync_frames_bucket_total{bucket="gt_10"} 7552
telemt_pool_swap_total 112
telemt_pool_force_close_total 3023
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 34432
telemt_me_writer_removed_unexpected_total 1022
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3368
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32134
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31409
telemt_me_writer_teardown_success_total{mode="normal"} 35502
telemt_me_writer_teardown_noop_total 34436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69938
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.974518
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69938
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 880
telemt_me_writer_restored_fallback_total 57
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 4755741
telemt_user_connections_current{user="hello"} 1565
telemt_user_octets_from_client{user="hello"} 89632291441 (83.48 GB)
telemt_user_octets_to_client{user="hello"} 2037533765840 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 732
telemt_user_unique_ips_recent_window{user="hello"} 157
```