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

# Server Metrics 2026-03-22 08:43:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 41848.3 (11h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1000590
telemt_connections_bad_total 57562
telemt_connections_current 1699
telemt_connections_me_current 1699
telemt_handshake_timeouts_total 46264
telemt_upstream_connect_attempt_total 16622
telemt_upstream_connect_success_total 16621
telemt_upstream_connect_attempts_per_request{bucket="1"} 16621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 481
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 253
telemt_me_idle_close_by_peer_total 253
telemt_me_route_drop_no_conn_total 556036
telemt_me_route_drop_channel_closed_total 179
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 832549
telemt_me_endpoint_quarantine_total 299
telemt_me_single_endpoint_shadow_rotate_total 337
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 6201
telemt_desync_full_logged_total 1743
telemt_desync_suppressed_total 4458
telemt_desync_frames_bucket_total{bucket="1_2"} 1887
telemt_desync_frames_bucket_total{bucket="3_10"} 2327
telemt_desync_frames_bucket_total{bucket="gt_10"} 1987
telemt_pool_swap_total 46
telemt_pool_force_close_total 1297
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 15103
telemt_me_writer_removed_unexpected_total 250
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1047
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14257
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1271
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13806
telemt_me_writer_teardown_success_total{mode="normal"} 15304
telemt_me_writer_teardown_noop_total 15105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30409
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.204204
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30409
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 233
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 831004
telemt_user_connections_current{user="hello"} 1699
telemt_user_octets_from_client{user="hello"} 12012233824 (11.19 GB)
telemt_user_octets_to_client{user="hello"} 267757929048 (249.37 GB)
telemt_user_unique_ips_current{user="hello"} 622
telemt_user_unique_ips_recent_window{user="hello"} 250
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 55214.4 (15h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1517047
telemt_connections_bad_total 149725
telemt_connections_current 1153
telemt_connections_me_current 1153
telemt_handshake_timeouts_total 42786
telemt_upstream_connect_attempt_total 28866
telemt_upstream_connect_success_total 28440
telemt_upstream_connect_fail_total 374
telemt_upstream_connect_attempts_per_request{bucket="1"} 28814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 374
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2481
telemt_me_reconnect_success_total 1062
telemt_me_reader_eof_total 965
telemt_me_idle_close_by_peer_total 965
telemt_me_route_drop_no_conn_total 691971
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1144449
telemt_me_endpoint_quarantine_total 485
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 438
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 5064
telemt_desync_full_logged_total 2931
telemt_desync_suppressed_total 2133
telemt_desync_frames_bucket_total{bucket="1_2"} 1101
telemt_desync_frames_bucket_total{bucket="3_10"} 1971
telemt_desync_frames_bucket_total{bucket="gt_10"} 1992
telemt_pool_swap_total 57
telemt_pool_force_close_total 1581
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 22596
telemt_me_writer_removed_unexpected_total 935
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2218
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21302
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1457
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21015
telemt_me_writer_teardown_success_total{mode="normal"} 23520
telemt_me_writer_teardown_noop_total 22596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46116
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.107619
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46116
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 860
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 1145999
telemt_user_connections_current{user="hello"} 1153
telemt_user_octets_from_client{user="hello"} 17643455446 (16.43 GB)
telemt_user_octets_to_client{user="hello"} 393831416779 (366.78 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 734
telemt_user_unique_ips_recent_window{user="hello"} 500
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 130074.7 (36h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9784437
telemt_connections_bad_total 877785
telemt_connections_current 4546
telemt_connections_me_current 4546
telemt_handshake_timeouts_total 292481
telemt_upstream_connect_attempt_total 47984
telemt_upstream_connect_success_total 47904
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 47912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1915
telemt_me_reconnect_success_total 988
telemt_me_reader_eof_total 998
telemt_me_idle_close_by_peer_total 998
telemt_me_route_drop_no_conn_total 5517691
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7683997
telemt_me_endpoint_quarantine_total 816
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 975
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
telemt_desync_total 33358
telemt_desync_full_logged_total 10960
telemt_desync_suppressed_total 22398
telemt_desync_frames_bucket_total{bucket="1_2"} 7328
telemt_desync_frames_bucket_total{bucket="3_10"} 12961
telemt_desync_frames_bucket_total{bucket="gt_10"} 13069
telemt_pool_swap_total 140
telemt_pool_force_close_total 4681
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 711
telemt_me_draining_writers_reap_progress_total 43799
telemt_me_writer_removed_unexpected_total 959
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3685
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40529
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4367
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 314
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39118
telemt_me_writer_teardown_success_total{mode="normal"} 44214
telemt_me_writer_teardown_noop_total 43843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88057
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 188.107724
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88057
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 711
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 7674163
telemt_user_connections_current{user="hello"} 4546
telemt_user_octets_from_client{user="hello"} 126483690684 (117.80 GB)
telemt_user_octets_to_client{user="hello"} 2555497537960 (2.32 TB)
telemt_user_unique_ips_current{user="hello"} 1781
telemt_user_unique_ips_recent_window{user="hello"} 693
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 130075.9 (36h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7981371
telemt_connections_bad_total 714408
telemt_connections_current 4257
telemt_connections_me_current 4257
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 256290
telemt_upstream_connect_attempt_total 53985
telemt_upstream_connect_success_total 53507
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 53753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26176
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2898
telemt_me_reconnect_success_total 1091
telemt_me_reader_eof_total 1009
telemt_me_idle_close_by_peer_total 1009
telemt_me_route_drop_no_conn_total 2671957
telemt_me_route_drop_channel_closed_total 320
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5901200
telemt_me_endpoint_quarantine_total 828
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1004
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 26990
telemt_desync_full_logged_total 9215
telemt_desync_suppressed_total 17775
telemt_desync_frames_bucket_total{bucket="1_2"} 6512
telemt_desync_frames_bucket_total{bucket="3_10"} 10447
telemt_desync_frames_bucket_total{bucket="gt_10"} 10031
telemt_pool_swap_total 142
telemt_pool_force_close_total 4267
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 458
telemt_me_draining_writers_reap_progress_total 42005
telemt_me_writer_removed_unexpected_total 1029
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3586
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39339
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4016
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 251
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37738
telemt_me_writer_teardown_success_total{mode="normal"} 42925
telemt_me_writer_teardown_noop_total 42011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84936
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 58.982021
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84936
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 458
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 920
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 5823757
telemt_user_connections_current{user="hello"} 4257
telemt_user_octets_from_client{user="hello"} 161066436555 (150.00 GB)
telemt_user_octets_to_client{user="hello"} 2797119219082 (2.54 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1636
telemt_user_unique_ips_recent_window{user="hello"} 604
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 130039.8 (36h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7673574
telemt_connections_bad_total 635765
telemt_connections_current 3984
telemt_connections_me_current 3984
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 254581
telemt_upstream_connect_attempt_total 58384
telemt_upstream_connect_success_total 57706
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 57853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2840
telemt_me_reconnect_success_total 1219
telemt_me_reader_eof_total 1119
telemt_me_idle_close_by_peer_total 1119
telemt_me_route_drop_no_conn_total 3083694
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5722423
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 960
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_desync_total 26881
telemt_desync_full_logged_total 9144
telemt_desync_suppressed_total 17737
telemt_desync_frames_bucket_total{bucket="1_2"} 6492
telemt_desync_frames_bucket_total{bucket="3_10"} 10313
telemt_desync_frames_bucket_total{bucket="gt_10"} 10076
telemt_pool_swap_total 139
telemt_pool_force_close_total 4146
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 483
telemt_me_draining_writers_reap_progress_total 42983
telemt_me_writer_removed_unexpected_total 1130
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3824
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40273
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3833
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38837
telemt_me_writer_teardown_success_total{mode="normal"} 44097
telemt_me_writer_teardown_noop_total 42995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87092
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.895379
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87092
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 483
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1056
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 5715432
telemt_user_connections_current{user="hello"} 3984
telemt_user_octets_from_client{user="hello"} 148161199995 (137.99 GB)
telemt_user_octets_to_client{user="hello"} 2536584748763 (2.31 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1570
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 319.5 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114073
telemt_connections_bad_total 11054
telemt_connections_current 5684
telemt_connections_me_current 5684
telemt_handshake_timeouts_total 1190
telemt_upstream_connect_attempt_total 167
telemt_upstream_connect_success_total 150
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 64
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 5
telemt_me_route_drop_no_conn_total 185604
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91455
telemt_me_endpoint_quarantine_total 2
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_me_writers_active_current 49
telemt_desync_total 177
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_force_close_total 2
telemt_me_draining_writers_reap_progress_total 59
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57
telemt_me_writer_teardown_success_total{mode="normal"} 59
telemt_me_writer_teardown_noop_total 59
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.008783
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118
telemt_user_connections_total{user="hello"} 91453
telemt_user_connections_current{user="hello"} 5684
telemt_user_octets_from_client{user="hello"} 541215260 (516.14 MB)
telemt_user_octets_to_client{user="hello"} 3419004432 (3.18 GB)
telemt_user_unique_ips_current{user="hello"} 2100
telemt_user_unique_ips_recent_window{user="hello"} 1226
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 130046.4 (36h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7316484
telemt_connections_bad_total 661602
telemt_connections_current 4129
telemt_connections_me_current 4129
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 150053
telemt_upstream_connect_attempt_total 74645
telemt_upstream_connect_success_total 73850
telemt_upstream_connect_fail_total 677
telemt_upstream_connect_attempts_per_request{bucket="1"} 74527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 440
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 677
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70324
telemt_me_reconnect_success_total 2003
telemt_me_reader_eof_total 1760
telemt_me_idle_close_by_peer_total 1759
telemt_me_route_drop_no_conn_total 2867139
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5742071
telemt_me_endpoint_quarantine_total 878
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 984
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 28966
telemt_desync_full_logged_total 10064
telemt_desync_suppressed_total 18902
telemt_desync_frames_bucket_total{bucket="1_2"} 5780
telemt_desync_frames_bucket_total{bucket="3_10"} 11149
telemt_desync_frames_bucket_total{bucket="gt_10"} 12037
telemt_pool_swap_total 136
telemt_pool_force_close_total 3897
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 462
telemt_me_draining_writers_reap_progress_total 45161
telemt_me_writer_removed_unexpected_total 1790
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4564
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42413
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 435
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41264
telemt_me_writer_teardown_success_total{mode="normal"} 46977
telemt_me_writer_teardown_noop_total 45162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92139
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.365559
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92139
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 462
telemt_me_refill_failed_total 4228
telemt_me_writer_restored_same_endpoint_total 1658
telemt_me_writer_restored_fallback_total 40
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7319
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 5740324
telemt_user_connections_current{user="hello"} 4129
telemt_user_octets_from_client{user="hello"} 145356636459 (135.37 GB)
telemt_user_octets_to_client{user="hello"} 2372497918039 (2.16 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1654
telemt_user_unique_ips_recent_window{user="hello"} 609
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 66882.3 (18h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5759253
telemt_connections_bad_total 227295
telemt_connections_current 3894
telemt_connections_me_current 3894
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2284712
telemt_upstream_connect_attempt_total 35954
telemt_upstream_connect_success_total 35700
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 35947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_reconnect_attempts_total 47372
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 850
telemt_me_idle_close_by_peer_total 850
telemt_me_route_drop_no_conn_total 1441061
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2889589
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 513
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 15668
telemt_desync_full_logged_total 5322
telemt_desync_suppressed_total 10346
telemt_desync_frames_bucket_total{bucket="1_2"} 3068
telemt_desync_frames_bucket_total{bucket="3_10"} 6037
telemt_desync_frames_bucket_total{bucket="gt_10"} 6563
telemt_pool_swap_total 72
telemt_pool_force_close_total 2160
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 203
telemt_me_draining_writers_reap_progress_total 24092
telemt_me_writer_removed_unexpected_total 920
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2076
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22958
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 278
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21932
telemt_me_writer_teardown_success_total{mode="normal"} 25034
telemt_me_writer_teardown_noop_total 24098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49132
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.613583
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49132
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 203
telemt_me_refill_failed_total 2687
telemt_me_writer_restored_same_endpoint_total 1052
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 2890561
telemt_user_connections_current{user="hello"} 3894
telemt_user_octets_from_client{user="hello"} 73883517544 (68.81 GB)
telemt_user_octets_to_client{user="hello"} 1263220844414 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1558
telemt_user_unique_ips_recent_window{user="hello"} 561
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 47853.3 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422273
telemt_connections_bad_total 2913
telemt_connections_current 969
telemt_connections_me_current 969
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8425
telemt_upstream_connect_attempt_total 25622
telemt_upstream_connect_success_total 25562
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 25617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 1013
telemt_me_reconnect_success_total 388
telemt_me_reader_eof_total 383
telemt_me_idle_close_by_peer_total 383
telemt_me_route_drop_no_conn_total 133805
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381399
telemt_me_endpoint_quarantine_total 458
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 409
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 1749
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1236
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 687
telemt_desync_frames_bucket_total{bucket="gt_10"} 549
telemt_pool_swap_total 52
telemt_pool_force_close_total 1167
telemt_me_writer_close_signal_drop_total 45
telemt_me_draining_writers_reap_progress_total 20579
telemt_me_writer_removed_unexpected_total 367
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1457
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19505
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19412
telemt_me_writer_teardown_success_total{mode="normal"} 20962
telemt_me_writer_teardown_noop_total 20579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41541
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.850155
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41541
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 45
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 337
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 383534
telemt_user_connections_current{user="hello"} 969
telemt_user_octets_from_client{user="hello"} 7430443173 (6.92 GB)
telemt_user_octets_to_client{user="hello"} 197251755947 (183.71 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 130050.9 (36h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9006150
telemt_connections_bad_total 1045210
telemt_connections_current 4988
telemt_connections_me_current 4988
telemt_handshake_timeouts_total 248748
telemt_upstream_connect_attempt_total 50571
telemt_upstream_connect_success_total 50378
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 50527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25403
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_reconnect_attempts_total 1897
telemt_me_reconnect_success_total 1029
telemt_me_reader_eof_total 1001
telemt_me_idle_close_by_peer_total 1001
telemt_me_route_drop_no_conn_total 2518855
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6663988
telemt_me_endpoint_quarantine_total 923
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 988
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_me_writers_active_current 45
telemt_desync_total 26750
telemt_desync_full_logged_total 8776
telemt_desync_suppressed_total 17974
telemt_desync_frames_bucket_total{bucket="1_2"} 6623
telemt_desync_frames_bucket_total{bucket="3_10"} 9746
telemt_desync_frames_bucket_total{bucket="gt_10"} 10381
telemt_pool_swap_total 144
telemt_pool_force_close_total 3871
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 472
telemt_me_draining_writers_reap_progress_total 45633
telemt_me_writer_removed_unexpected_total 961
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3641
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42983
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3770
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 101
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41762
telemt_me_writer_teardown_success_total{mode="normal"} 46624
telemt_me_writer_teardown_noop_total 45635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92259
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.603073
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92259
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 472
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 901
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 6636980
telemt_user_connections_current{user="hello"} 4988
telemt_user_octets_from_client{user="hello"} 129630048224 (120.73 GB)
telemt_user_octets_to_client{user="hello"} 3124944278584 (2.84 TB)
telemt_user_unique_ips_current{user="hello"} 1853
telemt_user_unique_ips_recent_window{user="hello"} 654
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 130047.3 (36h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7820006
telemt_connections_bad_total 870831
telemt_connections_current 4209
telemt_connections_me_current 4209
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 207951
telemt_upstream_connect_attempt_total 66625
telemt_upstream_connect_success_total 66111
telemt_upstream_connect_fail_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 66559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27085
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 630
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 448
telemt_me_reconnect_attempts_total 6391
telemt_me_reconnect_success_total 1459
telemt_me_reader_eof_total 1310
telemt_me_idle_close_by_peer_total 1310
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2659848
telemt_me_route_drop_channel_closed_total 229
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5949823
telemt_me_endpoint_quarantine_total 1017
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 987
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 25607
telemt_desync_full_logged_total 8523
telemt_desync_suppressed_total 17084
telemt_desync_frames_bucket_total{bucket="1_2"} 6313
telemt_desync_frames_bucket_total{bucket="3_10"} 9417
telemt_desync_frames_bucket_total{bucket="gt_10"} 9877
telemt_pool_swap_total 141
telemt_pool_force_close_total 3818
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 465
telemt_me_draining_writers_reap_progress_total 44278
telemt_me_writer_removed_unexpected_total 1325
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4243
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41422
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 271
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40460
telemt_me_writer_teardown_success_total{mode="normal"} 45665
telemt_me_writer_teardown_noop_total 44282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89947
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.894285
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89947
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 465
telemt_me_refill_failed_total 285
telemt_me_writer_restored_same_endpoint_total 1143
telemt_me_writer_restored_fallback_total 84
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 5950628
telemt_user_connections_current{user="hello"} 4209
telemt_user_octets_from_client{user="hello"} 109451041621 (101.93 GB)
telemt_user_octets_to_client{user="hello"} 2568443750996 (2.34 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1658
telemt_user_unique_ips_recent_window{user="hello"} 627
```