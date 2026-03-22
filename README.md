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

# Server Metrics 2026-03-22 13:25:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 58757.4 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1823941
telemt_connections_bad_total 81431
telemt_connections_current 1656
telemt_connections_me_current 1656
telemt_handshake_timeouts_total 78297
telemt_upstream_connect_attempt_total 22111
telemt_upstream_connect_success_total 22110
telemt_upstream_connect_attempts_per_request{bucket="1"} 22110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 904
telemt_me_reconnect_success_total 359
telemt_me_reader_eof_total 363
telemt_me_idle_close_by_peer_total 363
telemt_me_route_drop_no_conn_total 1277345
telemt_me_route_drop_channel_closed_total 573
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1549975
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 467
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 8682
telemt_desync_full_logged_total 2651
telemt_desync_suppressed_total 6031
telemt_desync_frames_bucket_total{bucket="1_2"} 2430
telemt_desync_frames_bucket_total{bucket="3_10"} 3267
telemt_desync_frames_bucket_total{bucket="gt_10"} 2985
telemt_pool_swap_total 65
telemt_pool_force_close_total 1947
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 313
telemt_me_draining_writers_reap_progress_total 20169
telemt_me_writer_removed_unexpected_total 354
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1441
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18944
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1911
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18222
telemt_me_writer_teardown_success_total{mode="normal"} 20385
telemt_me_writer_teardown_noop_total 20173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40558
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 151.214917
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40558
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 313
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1547061
telemt_user_connections_current{user="hello"} 1656
telemt_user_octets_from_client{user="hello"} 24300035612 (22.63 GB)
telemt_user_octets_to_client{user="hello"} 451770312108 (420.74 GB)
telemt_user_unique_ips_current{user="hello"} 630
telemt_user_unique_ips_recent_window{user="hello"} 289
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 72123.8 (20h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2987131
telemt_connections_bad_total 281222
telemt_connections_current 2288
telemt_connections_me_current 2288
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 69869
telemt_upstream_connect_attempt_total 46587
telemt_upstream_connect_success_total 46036
telemt_upstream_connect_fail_total 486
telemt_upstream_connect_attempts_per_request{bucket="1"} 46522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 486
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3628
telemt_me_reconnect_success_total 1616
telemt_me_reader_eof_total 1492
telemt_me_idle_close_by_peer_total 1492
telemt_me_route_drop_no_conn_total 2783155
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2346931
telemt_me_endpoint_quarantine_total 602
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 561
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 37
telemt_desync_total 9165
telemt_desync_full_logged_total 5121
telemt_desync_suppressed_total 4044
telemt_desync_frames_bucket_total{bucket="1_2"} 2149
telemt_desync_frames_bucket_total{bucket="3_10"} 3589
telemt_desync_frames_bucket_total{bucket="gt_10"} 3427
telemt_pool_swap_total 71
telemt_pool_force_close_total 2036
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 170
telemt_me_draining_writers_reap_progress_total 28488
telemt_me_writer_removed_unexpected_total 1451
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3116
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26824
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1792
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 244
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26452
telemt_me_writer_teardown_success_total{mode="normal"} 29940
telemt_me_writer_teardown_noop_total 28488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58428
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.429753
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58428
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 170
telemt_me_refill_failed_total 91
telemt_me_writer_restored_same_endpoint_total 1343
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 2358536
telemt_user_connections_current{user="hello"} 2288
telemt_user_octets_from_client{user="hello"} 28524592015 (26.57 GB)
telemt_user_octets_to_client{user="hello"} 542944309382 (505.66 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1418
telemt_user_unique_ips_recent_window{user="hello"} 525
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 146983.8 (40h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13696848
telemt_connections_bad_total 1199346
telemt_connections_current 4507
telemt_connections_me_current 4507
telemt_handshake_timeouts_total 345585
telemt_upstream_connect_attempt_total 53435
telemt_upstream_connect_success_total 53353
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 53361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28961
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2431
telemt_me_reconnect_success_total 1274
telemt_me_reader_eof_total 1216
telemt_me_idle_close_by_peer_total 1215
telemt_me_route_drop_no_conn_total 11874414
telemt_me_route_drop_channel_closed_total 118
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10983252
telemt_me_endpoint_quarantine_total 937
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1095
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
telemt_me_writers_active_current 43
telemt_desync_total 44722
telemt_desync_full_logged_total 14209
telemt_desync_suppressed_total 30513
telemt_desync_frames_bucket_total{bucket="1_2"} 10110
telemt_desync_frames_bucket_total{bucket="3_10"} 17494
telemt_desync_frames_bucket_total{bucket="gt_10"} 17118
telemt_pool_swap_total 158
telemt_pool_force_close_total 5408
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 856
telemt_me_draining_writers_reap_progress_total 48746
telemt_me_writer_removed_unexpected_total 1173
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4240
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45013
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4977
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 431
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43338
telemt_me_writer_teardown_success_total{mode="normal"} 49253
telemt_me_writer_teardown_noop_total 48795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98048
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 249.980564
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98048
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 856
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1097
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 10971253
telemt_user_connections_current{user="hello"} 4507
telemt_user_octets_from_client{user="hello"} 158396158356 (147.52 GB)
telemt_user_octets_to_client{user="hello"} 2935812755564 (2.67 TB)
telemt_user_unique_ips_current{user="hello"} 1678
telemt_user_unique_ips_recent_window{user="hello"} 796
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 146985.1 (40h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10170584
telemt_connections_bad_total 950798
telemt_connections_current 4771
telemt_connections_me_current 4771
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 304741
telemt_upstream_connect_attempt_total 79823
telemt_upstream_connect_success_total 78685
telemt_upstream_connect_fail_total 817
telemt_upstream_connect_attempts_per_request{bucket="1"} 79502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3677
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 817
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3669
telemt_me_reconnect_success_total 1460
telemt_me_reader_eof_total 1333
telemt_me_idle_close_by_peer_total 1333
telemt_me_route_drop_no_conn_total 4065080
telemt_me_route_drop_channel_closed_total 428
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7591906
telemt_me_endpoint_quarantine_total 926
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1117
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_active_current 46
telemt_desync_total 33997
telemt_desync_full_logged_total 11455
telemt_desync_suppressed_total 22542
telemt_desync_frames_bucket_total{bucket="1_2"} 8375
telemt_desync_frames_bucket_total{bucket="3_10"} 13082
telemt_desync_frames_bucket_total{bucket="gt_10"} 12540
telemt_pool_swap_total 157
telemt_pool_force_close_total 4830
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 602
telemt_me_draining_writers_reap_progress_total 46959
telemt_me_writer_removed_unexpected_total 1366
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4260
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43933
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4412
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 418
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42129
telemt_me_writer_teardown_success_total{mode="normal"} 48193
telemt_me_writer_teardown_noop_total 46974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95167
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 88.141588
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95167
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 602
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 1237
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 7531678
telemt_user_connections_current{user="hello"} 4771
telemt_user_octets_from_client{user="hello"} 192635015437 (179.41 GB)
telemt_user_octets_to_client{user="hello"} 3402457808578 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1927
telemt_user_unique_ips_recent_window{user="hello"} 657
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 146949.0 (40h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9644314
telemt_connections_bad_total 804444
telemt_connections_current 3196
telemt_connections_me_current 3196
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 312716
telemt_upstream_connect_attempt_total 65259
telemt_upstream_connect_success_total 64356
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 64537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30208
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4163
telemt_me_reconnect_success_total 1788
telemt_me_reader_eof_total 1557
telemt_me_idle_close_by_peer_total 1556
telemt_me_route_drop_no_conn_total 4789744
telemt_me_route_drop_channel_closed_total 325
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7276849
telemt_me_endpoint_quarantine_total 1014
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1077
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 33709
telemt_desync_full_logged_total 11199
telemt_desync_suppressed_total 22510
telemt_desync_frames_bucket_total{bucket="1_2"} 8573
telemt_desync_frames_bucket_total{bucket="3_10"} 12923
telemt_desync_frames_bucket_total{bucket="gt_10"} 12213
telemt_pool_swap_total 153
telemt_pool_force_close_total 4775
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 47606
telemt_me_writer_removed_unexpected_total 1704
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4757
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44475
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 511
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42831
telemt_me_writer_teardown_success_total{mode="normal"} 49232
telemt_me_writer_teardown_noop_total 47673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96905
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3153.659928
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96905
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 122
telemt_me_writer_restored_same_endpoint_total 1562
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 7271003
telemt_user_connections_current{user="hello"} 3196
telemt_user_octets_from_client{user="hello"} 170889421057 (159.15 GB)
telemt_user_octets_to_client{user="hello"} 3035515439317 (2.76 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1322
telemt_user_unique_ips_recent_window{user="hello"} 578
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 17229.2 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7252203
telemt_connections_bad_total 470031
telemt_connections_current 6570
telemt_connections_me_current 6570
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 114282
telemt_upstream_connect_attempt_total 27751
telemt_upstream_connect_success_total 26406
telemt_upstream_connect_fail_total 1010
telemt_upstream_connect_attempts_per_request{bucket="1"} 27416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6369
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4703
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1010
telemt_me_keepalive_timeout_total 639
telemt_me_reconnect_attempts_total 2604
telemt_me_reconnect_success_total 475
telemt_me_reader_eof_total 298
telemt_me_idle_close_by_peer_total 298
telemt_me_route_drop_no_conn_total 17427156
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6026818
telemt_me_endpoint_quarantine_total 112
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 136
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 8820
telemt_desync_full_logged_total 2268
telemt_desync_suppressed_total 6552
telemt_desync_frames_bucket_total{bucket="1_2"} 1584
telemt_desync_frames_bucket_total{bucket="3_10"} 3578
telemt_desync_frames_bucket_total{bucket="gt_10"} 3658
telemt_pool_swap_total 16
telemt_pool_force_close_total 626
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 247
telemt_me_draining_writers_reap_progress_total 4527
telemt_me_writer_removed_unexpected_total 429
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 801
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4113
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 182
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3901
telemt_me_writer_teardown_success_total{mode="normal"} 4914
telemt_me_writer_teardown_noop_total 4530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9444
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.911748
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9444
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 247
telemt_me_refill_failed_total 112
telemt_me_writer_restored_same_endpoint_total 318
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 6042077
telemt_user_connections_current{user="hello"} 6569
telemt_user_octets_from_client{user="hello"} 32922747971 (30.66 GB)
telemt_user_octets_to_client{user="hello"} 179861034320 (167.51 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2331
telemt_user_unique_ips_recent_window{user="hello"} 1750
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 146955.9 (40h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9346203
telemt_connections_bad_total 777499
telemt_connections_current 3734
telemt_connections_me_current 3734
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 201864
telemt_upstream_connect_attempt_total 89578
telemt_upstream_connect_success_total 88678
telemt_upstream_connect_fail_total 778
telemt_upstream_connect_attempts_per_request{bucket="1"} 89456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 778
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71302
telemt_me_reconnect_success_total 2401
telemt_me_reader_eof_total 2135
telemt_me_idle_close_by_peer_total 2134
telemt_me_route_drop_no_conn_total 4543373
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7380316
telemt_me_endpoint_quarantine_total 983
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1099
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 37792
telemt_desync_full_logged_total 12918
telemt_desync_suppressed_total 24874
telemt_desync_frames_bucket_total{bucket="1_2"} 7665
telemt_desync_frames_bucket_total{bucket="3_10"} 14617
telemt_desync_frames_bucket_total{bucket="gt_10"} 15510
telemt_pool_swap_total 151
telemt_pool_force_close_total 4466
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 544
telemt_me_draining_writers_reap_progress_total 50264
telemt_me_writer_removed_unexpected_total 2163
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5306
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47137
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3854
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 612
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45798
telemt_me_writer_teardown_success_total{mode="normal"} 52443
telemt_me_writer_teardown_noop_total 50265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102708
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.563002
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102708
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 544
telemt_me_refill_failed_total 4252
telemt_me_writer_restored_same_endpoint_total 2015
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 7381752
telemt_user_connections_current{user="hello"} 3734
telemt_user_octets_from_client{user="hello"} 170998097647 (159.25 GB)
telemt_user_octets_to_client{user="hello"} 2816239212589 (2.56 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1501
telemt_user_unique_ips_recent_window{user="hello"} 687
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 83792.0 (23h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9211500
telemt_connections_bad_total 325507
telemt_connections_current 5524
telemt_connections_me_current 5524
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3880163
telemt_upstream_connect_attempt_total 41773
telemt_upstream_connect_success_total 41471
telemt_upstream_connect_fail_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 41766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 295
telemt_me_reconnect_attempts_total 47902
telemt_me_reconnect_success_total 1433
telemt_me_reader_eof_total 1100
telemt_me_idle_close_by_peer_total 1100
telemt_me_route_drop_no_conn_total 3344518
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4442074
telemt_me_endpoint_quarantine_total 550
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 628
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_writers_warm_current 35
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 24258
telemt_desync_full_logged_total 8131
telemt_desync_suppressed_total 16127
telemt_desync_frames_bucket_total{bucket="1_2"} 4914
telemt_desync_frames_bucket_total{bucket="3_10"} 9549
telemt_desync_frames_bucket_total{bucket="gt_10"} 9795
telemt_pool_swap_total 87
telemt_pool_force_close_total 2703
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 279
telemt_me_draining_writers_reap_progress_total 29156
telemt_me_writer_removed_unexpected_total 1165
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2643
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27706
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2301
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 402
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26453
telemt_me_writer_teardown_success_total{mode="normal"} 30349
telemt_me_writer_teardown_noop_total 29163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59512
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.850910
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59512
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 279
telemt_me_refill_failed_total 2701
telemt_me_writer_restored_same_endpoint_total 1280
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4437070
telemt_user_connections_current{user="hello"} 5524
telemt_user_octets_from_client{user="hello"} 98028779992 (91.30 GB)
telemt_user_octets_to_client{user="hello"} 1706787241814 (1.55 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2177
telemt_user_unique_ips_recent_window{user="hello"} 701
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 64762.7 (17h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 753680
telemt_connections_bad_total 8697
telemt_connections_current 987
telemt_connections_me_current 987
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14296
telemt_upstream_connect_attempt_total 32923
telemt_upstream_connect_success_total 32840
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 32909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 401
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1459
telemt_me_reconnect_success_total 627
telemt_me_reader_eof_total 609
telemt_me_idle_close_by_peer_total 609
telemt_me_route_drop_no_conn_total 253828
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678079
telemt_me_endpoint_quarantine_total 579
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 539
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
telemt_desync_total 3760
telemt_desync_full_logged_total 1116
telemt_desync_suppressed_total 2644
telemt_desync_frames_bucket_total{bucket="1_2"} 915
telemt_desync_frames_bucket_total{bucket="3_10"} 1490
telemt_desync_frames_bucket_total{bucket="gt_10"} 1355
telemt_pool_swap_total 68
telemt_pool_force_close_total 1680
telemt_me_writer_close_signal_drop_total 97
telemt_me_draining_writers_reap_progress_total 27014
telemt_me_writer_removed_unexpected_total 589
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2065
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25560
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1603
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25334
telemt_me_writer_teardown_success_total{mode="normal"} 27625
telemt_me_writer_teardown_noop_total 27016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54641
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.002513
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54641
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 97
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 544
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 679631
telemt_user_connections_current{user="hello"} 987
telemt_user_octets_from_client{user="hello"} 12806471029 (11.93 GB)
telemt_user_octets_to_client{user="hello"} 323033479779 (300.85 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 146960.2 (40h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11414032
telemt_connections_bad_total 1339154
telemt_connections_current 5884
telemt_connections_me_current 5884
telemt_handshake_timeouts_total 307552
telemt_upstream_connect_attempt_total 55565
telemt_upstream_connect_success_total 55350
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 55517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28020
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_reconnect_attempts_total 2183
telemt_me_reconnect_success_total 1159
telemt_me_reader_eof_total 1124
telemt_me_idle_close_by_peer_total 1124
telemt_me_route_drop_no_conn_total 3606258
telemt_me_route_drop_channel_closed_total 96
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8570461
telemt_me_endpoint_quarantine_total 1011
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1102
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 35083
telemt_desync_full_logged_total 11518
telemt_desync_suppressed_total 23565
telemt_desync_frames_bucket_total{bucket="1_2"} 8361
telemt_desync_frames_bucket_total{bucket="3_10"} 13006
telemt_desync_frames_bucket_total{bucket="gt_10"} 13716
telemt_pool_swap_total 163
telemt_pool_force_close_total 4477
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 563
telemt_me_draining_writers_reap_progress_total 50054
telemt_me_writer_removed_unexpected_total 1079
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4102
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47067
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4324
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 153
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45577
telemt_me_writer_teardown_success_total{mode="normal"} 51169
telemt_me_writer_teardown_noop_total 50056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101225
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.131917
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101225
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 563
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1015
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8541104
telemt_user_connections_current{user="hello"} 5884
telemt_user_octets_from_client{user="hello"} 164975115584 (153.65 GB)
telemt_user_octets_to_client{user="hello"} 3847248814080 (3.50 TB)
telemt_user_unique_ips_current{user="hello"} 2176
telemt_user_unique_ips_recent_window{user="hello"} 717
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 146956.9 (40h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9843487
telemt_connections_bad_total 1102565
telemt_connections_current 3858
telemt_connections_me_current 3858
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 257415
telemt_upstream_connect_attempt_total 81108
telemt_upstream_connect_success_total 80515
telemt_upstream_connect_fail_total 513
telemt_upstream_connect_attempts_per_request{bucket="1"} 81028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 513
telemt_me_reconnect_attempts_total 8559
telemt_me_reconnect_success_total 1925
telemt_me_reader_eof_total 1795
telemt_me_idle_close_by_peer_total 1795
telemt_me_seq_mismatch_total 71
telemt_me_route_drop_no_conn_total 4393039
telemt_me_route_drop_channel_closed_total 314
telemt_me_route_drop_queue_full_total 16
telemt_me_route_drop_queue_full_profile_total{profile="high"} 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7574655
telemt_me_endpoint_quarantine_total 1125
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1106
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 34238
telemt_desync_full_logged_total 11168
telemt_desync_suppressed_total 23070
telemt_desync_frames_bucket_total{bucket="1_2"} 8466
telemt_desync_frames_bucket_total{bucket="3_10"} 12759
telemt_desync_frames_bucket_total{bucket="gt_10"} 13013
telemt_pool_swap_total 156
telemt_pool_force_close_total 4339
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 553
telemt_me_draining_writers_reap_progress_total 49374
telemt_me_writer_removed_unexpected_total 1819
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5119
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46141
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3945
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 394
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45035
telemt_me_writer_teardown_success_total{mode="normal"} 51260
telemt_me_writer_teardown_noop_total 49378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100638
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.226966
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100638
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 553
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1565
telemt_me_writer_restored_fallback_total 95
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 7581820
telemt_user_connections_current{user="hello"} 3858
telemt_user_octets_from_client{user="hello"} 133997153573 (124.79 GB)
telemt_user_octets_to_client{user="hello"} 2998261854467 (2.73 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1563
telemt_user_unique_ips_recent_window{user="hello"} 667
```