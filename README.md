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

# Server Metrics 2026-03-22 12:33:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 55634.4 (15h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1668579
telemt_connections_bad_total 78021
telemt_connections_current 1696
telemt_connections_me_current 1696
telemt_handshake_timeouts_total 73986
telemt_upstream_connect_attempt_total 21109
telemt_upstream_connect_success_total 21108
telemt_upstream_connect_attempts_per_request{bucket="1"} 21108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 795
telemt_me_reconnect_success_total 343
telemt_me_reader_eof_total 343
telemt_me_idle_close_by_peer_total 343
telemt_me_route_drop_no_conn_total 1110490
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1411482
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 443
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 8350
telemt_desync_full_logged_total 2521
telemt_desync_suppressed_total 5829
telemt_desync_frames_bucket_total{bucket="1_2"} 2352
telemt_desync_frames_bucket_total{bucket="3_10"} 3150
telemt_desync_frames_bucket_total{bucket="gt_10"} 2848
telemt_pool_swap_total 61
telemt_pool_force_close_total 1825
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 279
telemt_me_draining_writers_reap_progress_total 19257
telemt_me_writer_removed_unexpected_total 335
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18106
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1790
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17432
telemt_me_writer_teardown_success_total{mode="normal"} 19467
telemt_me_writer_teardown_noop_total 19259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38726
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 136.703783
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38726
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 279
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 304
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 1408734
telemt_user_connections_current{user="hello"} 1696
telemt_user_octets_from_client{user="hello"} 22515428196 (20.97 GB)
telemt_user_octets_to_client{user="hello"} 417795405048 (389.10 GB)
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 69000.8 (19h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2694450
telemt_connections_bad_total 248085
telemt_connections_current 1884
telemt_connections_me_current 1884
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 62534
telemt_upstream_connect_attempt_total 45454
telemt_upstream_connect_success_total 44926
telemt_upstream_connect_fail_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 45393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 118
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 467
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3460
telemt_me_reconnect_success_total 1564
telemt_me_reader_eof_total 1450
telemt_me_idle_close_by_peer_total 1450
telemt_me_route_drop_no_conn_total 2361004
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2112556
telemt_me_endpoint_quarantine_total 582
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 541
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
telemt_me_writers_active_current 45
telemt_desync_total 8375
telemt_desync_full_logged_total 4716
telemt_desync_suppressed_total 3659
telemt_desync_frames_bucket_total{bucket="1_2"} 1959
telemt_desync_frames_bucket_total{bucket="3_10"} 3262
telemt_desync_frames_bucket_total{bucket="gt_10"} 3154
telemt_pool_swap_total 68
telemt_pool_force_close_total 1946
telemt_me_writer_close_signal_drop_total 161
telemt_me_draining_writers_reap_progress_total 27554
telemt_me_writer_removed_unexpected_total 1410
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3018
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25946
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 238
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25608
telemt_me_writer_teardown_success_total{mode="normal"} 28964
telemt_me_writer_teardown_noop_total 27554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56518
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.427279
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56518
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 161
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1307
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 2124294
telemt_user_connections_current{user="hello"} 1884
telemt_user_octets_from_client{user="hello"} 26290728047 (24.49 GB)
telemt_user_octets_to_client{user="hello"} 518200242994 (482.61 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1125
telemt_user_unique_ips_recent_window{user="hello"} 733
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 143860.8 (39h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12933735
telemt_connections_bad_total 1140740
telemt_connections_current 5575
telemt_connections_me_current 5575
telemt_handshake_timeouts_total 334830
telemt_upstream_connect_attempt_total 52385
telemt_upstream_connect_success_total 52305
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 52313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2374
telemt_me_reconnect_success_total 1223
telemt_me_reader_eof_total 1186
telemt_me_idle_close_by_peer_total 1185
telemt_me_route_drop_no_conn_total 10625295
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10333451
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1070
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
telemt_desync_total 42559
telemt_desync_full_logged_total 13584
telemt_desync_suppressed_total 28975
telemt_desync_frames_bucket_total{bucket="1_2"} 9621
telemt_desync_frames_bucket_total{bucket="3_10"} 16612
telemt_desync_frames_bucket_total{bucket="gt_10"} 16326
telemt_pool_swap_total 154
telemt_pool_force_close_total 5263
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 834
telemt_me_draining_writers_reap_progress_total 47777
telemt_me_writer_removed_unexpected_total 1145
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4148
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44130
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4848
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 415
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42514
telemt_me_writer_teardown_success_total{mode="normal"} 48278
telemt_me_writer_teardown_noop_total 47825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96103
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 228.817350
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96103
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 834
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 1060
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 10321877
telemt_user_connections_current{user="hello"} 5575
telemt_user_octets_from_client{user="hello"} 152712455616 (142.22 GB)
telemt_user_octets_to_client{user="hello"} 2867691339316 (2.61 TB)
telemt_user_unique_ips_current{user="hello"} 2179
telemt_user_unique_ips_recent_window{user="hello"} 1003
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 143862.0 (39h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9767489
telemt_connections_bad_total 894733
telemt_connections_current 4835
telemt_connections_me_current 4835
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 294688
telemt_upstream_connect_attempt_total 78687
telemt_upstream_connect_success_total 77559
telemt_upstream_connect_fail_total 814
telemt_upstream_connect_attempts_per_request{bucket="1"} 78373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30941
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3671
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 814
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3336
telemt_me_reconnect_success_total 1360
telemt_me_reader_eof_total 1246
telemt_me_idle_close_by_peer_total 1246
telemt_me_route_drop_no_conn_total 3916003
telemt_me_route_drop_channel_closed_total 403
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7284226
telemt_me_endpoint_quarantine_total 904
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1096
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
telemt_me_writers_active_current 45
telemt_desync_total 32860
telemt_desync_full_logged_total 11112
telemt_desync_suppressed_total 21748
telemt_desync_frames_bucket_total{bucket="1_2"} 8099
telemt_desync_frames_bucket_total{bucket="3_10"} 12658
telemt_desync_frames_bucket_total{bucket="gt_10"} 12103
telemt_pool_swap_total 154
telemt_pool_force_close_total 4706
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 570
telemt_me_draining_writers_reap_progress_total 46010
telemt_me_writer_removed_unexpected_total 1277
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4102
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43053
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4327
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 379
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41304
telemt_me_writer_teardown_success_total{mode="normal"} 47155
telemt_me_writer_teardown_noop_total 46021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93176
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 83.065764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93176
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 570
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 1161
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 7224633
telemt_user_connections_current{user="hello"} 4835
telemt_user_octets_from_client{user="hello"} 186662338301 (173.84 GB)
telemt_user_octets_to_client{user="hello"} 3280663304014 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1898
telemt_user_unique_ips_recent_window{user="hello"} 600
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 143827.0 (39h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9202967
telemt_connections_bad_total 775870
telemt_connections_current 3594
telemt_connections_me_current 3594
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 292833
telemt_upstream_connect_attempt_total 64035
telemt_upstream_connect_success_total 63280
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 63442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29687
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1964
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 306
telemt_me_reconnect_attempts_total 3885
telemt_me_reconnect_success_total 1685
telemt_me_reader_eof_total 1507
telemt_me_idle_close_by_peer_total 1506
telemt_me_route_drop_no_conn_total 3996739
telemt_me_route_drop_channel_closed_total 283
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6929282
telemt_me_endpoint_quarantine_total 987
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1053
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_active_current 48
telemt_desync_total 32635
telemt_desync_full_logged_total 10869
telemt_desync_suppressed_total 21766
telemt_desync_frames_bucket_total{bucket="1_2"} 8268
telemt_desync_frames_bucket_total{bucket="3_10"} 12510
telemt_desync_frames_bucket_total{bucket="gt_10"} 11857
telemt_pool_swap_total 150
telemt_pool_force_close_total 4668
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 46772
telemt_me_writer_removed_unexpected_total 1587
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4543
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43738
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 484
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42104
telemt_me_writer_teardown_success_total{mode="normal"} 48281
telemt_me_writer_teardown_noop_total 46838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95119
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3092.038599
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95119
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1466
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 6921097
telemt_user_connections_current{user="hello"} 3594
telemt_user_octets_from_client{user="hello"} 167436549249 (155.94 GB)
telemt_user_octets_to_client{user="hello"} 2958156059013 (2.69 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1508
telemt_user_unique_ips_recent_window{user="hello"} 591
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 14109.4 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5984717
telemt_connections_bad_total 364782
telemt_connections_current 6812
telemt_connections_me_current 6812
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 94878
telemt_upstream_connect_attempt_total 24195
telemt_upstream_connect_success_total 23113
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 23951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4958
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4628
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 521
telemt_me_reconnect_attempts_total 2299
telemt_me_reconnect_success_total 361
telemt_me_reader_eof_total 232
telemt_me_idle_close_by_peer_total 232
telemt_me_route_drop_no_conn_total 14086420
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 24
telemt_me_route_drop_queue_full_profile_total{profile="high"} 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5002939
telemt_me_endpoint_quarantine_total 92
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 117
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 7597
telemt_desync_full_logged_total 1937
telemt_desync_suppressed_total 5660
telemt_desync_frames_bucket_total{bucket="1_2"} 1391
telemt_desync_frames_bucket_total{bucket="3_10"} 3032
telemt_desync_frames_bucket_total{bucket="gt_10"} 3174
telemt_pool_swap_total 13
telemt_pool_force_close_total 540
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 212
telemt_me_draining_writers_reap_progress_total 3667
telemt_me_writer_removed_unexpected_total 320
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 621
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3323
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 395
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 145
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3127
telemt_me_writer_teardown_success_total{mode="normal"} 3944
telemt_me_writer_teardown_noop_total 3670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7614
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.190056
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7614
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 212
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 246
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 5016335
telemt_user_connections_current{user="hello"} 6812
telemt_user_octets_from_client{user="hello"} 27455718242 (25.57 GB)
telemt_user_octets_to_client{user="hello"} 146287502027 (136.24 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2498
telemt_user_unique_ips_recent_window{user="hello"} 1390
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 143832.8 (39h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8970108
telemt_connections_bad_total 757759
telemt_connections_current 4828
telemt_connections_me_current 4828
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 191092
telemt_upstream_connect_attempt_total 88558
telemt_upstream_connect_success_total 87684
telemt_upstream_connect_fail_total 752
telemt_upstream_connect_attempts_per_request{bucket="1"} 88436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31634
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1248
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 752
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71133
telemt_me_reconnect_success_total 2368
telemt_me_reader_eof_total 2109
telemt_me_idle_close_by_peer_total 2108
telemt_me_route_drop_no_conn_total 4248403
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7085719
telemt_me_endpoint_quarantine_total 959
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1075
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 36175
telemt_desync_full_logged_total 12439
telemt_desync_suppressed_total 23736
telemt_desync_frames_bucket_total{bucket="1_2"} 7383
telemt_desync_frames_bucket_total{bucket="3_10"} 13902
telemt_desync_frames_bucket_total{bucket="gt_10"} 14890
telemt_pool_swap_total 147
telemt_pool_force_close_total 4326
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 523
telemt_me_draining_writers_reap_progress_total 49365
telemt_me_writer_removed_unexpected_total 2137
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5203
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46325
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3733
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 593
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45039
telemt_me_writer_teardown_success_total{mode="normal"} 51528
telemt_me_writer_teardown_noop_total 49366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100894
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.043962
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100894
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 523
telemt_me_refill_failed_total 4245
telemt_me_writer_restored_same_endpoint_total 1987
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 7088173
telemt_user_connections_current{user="hello"} 4828
telemt_user_octets_from_client{user="hello"} 166779934251 (155.33 GB)
telemt_user_octets_to_client{user="hello"} 2733042063605 (2.49 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1952
telemt_user_unique_ips_recent_window{user="hello"} 692
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 80668.9 (22h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8539125
telemt_connections_bad_total 300615
telemt_connections_current 4376
telemt_connections_me_current 4376
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3582851
telemt_upstream_connect_attempt_total 40816
telemt_upstream_connect_success_total 40526
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 40809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_reconnect_attempts_total 47847
telemt_me_reconnect_success_total 1401
telemt_me_reader_eof_total 1071
telemt_me_idle_close_by_peer_total 1071
telemt_me_route_drop_no_conn_total 2955805
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4151105
telemt_me_endpoint_quarantine_total 539
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 609
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 22806
telemt_desync_full_logged_total 7624
telemt_desync_suppressed_total 15182
telemt_desync_frames_bucket_total{bucket="1_2"} 4680
telemt_desync_frames_bucket_total{bucket="3_10"} 8891
telemt_desync_frames_bucket_total{bucket="gt_10"} 9235
telemt_pool_swap_total 84
telemt_pool_force_close_total 2608
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 266
telemt_me_draining_writers_reap_progress_total 28348
telemt_me_writer_removed_unexpected_total 1136
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2555
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26957
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2213
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 395
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25740
telemt_me_writer_teardown_success_total{mode="normal"} 29512
telemt_me_writer_teardown_noop_total 28355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57867
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.830081
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57867
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 266
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1253
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4147190
telemt_user_connections_current{user="hello"} 4376
telemt_user_octets_from_client{user="hello"} 93201893576 (86.80 GB)
telemt_user_octets_to_client{user="hello"} 1624939031154 (1.48 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1803
telemt_user_unique_ips_recent_window{user="hello"} 661
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 61639.9 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691109
telemt_connections_bad_total 7893
telemt_connections_current 1084
telemt_connections_me_current 1084
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 13484
telemt_upstream_connect_attempt_total 31653
telemt_upstream_connect_success_total 31575
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 31642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 1394
telemt_me_reconnect_success_total 603
telemt_me_reader_eof_total 583
telemt_me_idle_close_by_peer_total 583
telemt_me_route_drop_no_conn_total 231071
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 624070
telemt_me_endpoint_quarantine_total 564
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 518
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
telemt_desync_total 3409
telemt_desync_full_logged_total 1004
telemt_desync_suppressed_total 2405
telemt_desync_frames_bucket_total{bucket="1_2"} 847
telemt_desync_frames_bucket_total{bucket="3_10"} 1354
telemt_desync_frames_bucket_total{bucket="gt_10"} 1208
telemt_pool_swap_total 65
telemt_pool_force_close_total 1598
telemt_me_writer_close_signal_drop_total 92
telemt_me_draining_writers_reap_progress_total 25914
telemt_me_writer_removed_unexpected_total 565
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1971
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24527
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1521
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24316
telemt_me_writer_teardown_success_total{mode="normal"} 26498
telemt_me_writer_teardown_noop_total 25916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52414
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.849546
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52414
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 92
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 524
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 625816
telemt_user_connections_current{user="hello"} 1084
telemt_user_octets_from_client{user="hello"} 12045273793 (11.22 GB)
telemt_user_octets_to_client{user="hello"} 302731223019 (281.94 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 143837.3 (39h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10930768
telemt_connections_bad_total 1260471
telemt_connections_current 5372
telemt_connections_me_current 5372
telemt_handshake_timeouts_total 293358
telemt_upstream_connect_attempt_total 54641
telemt_upstream_connect_success_total 54428
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 54593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27537
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_reconnect_attempts_total 2143
telemt_me_reconnect_success_total 1136
telemt_me_reader_eof_total 1099
telemt_me_idle_close_by_peer_total 1099
telemt_me_route_drop_no_conn_total 3414494
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8209119
telemt_me_endpoint_quarantine_total 996
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1082
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
telemt_desync_total 33378
telemt_desync_full_logged_total 10960
telemt_desync_suppressed_total 22418
telemt_desync_frames_bucket_total{bucket="1_2"} 8024
telemt_desync_frames_bucket_total{bucket="3_10"} 12341
telemt_desync_frames_bucket_total{bucket="gt_10"} 13013
telemt_pool_swap_total 159
telemt_pool_force_close_total 4349
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 542
telemt_me_draining_writers_reap_progress_total 49240
telemt_me_writer_removed_unexpected_total 1055
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4011
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46319
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4205
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 144
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44891
telemt_me_writer_teardown_success_total{mode="normal"} 50330
telemt_me_writer_teardown_noop_total 49242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99572
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.478949
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99572
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 542
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 992
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 8180249
telemt_user_connections_current{user="hello"} 5372
telemt_user_octets_from_client{user="hello"} 156766172024 (146.00 GB)
telemt_user_octets_to_client{user="hello"} 3711195498204 (3.38 TB)
telemt_user_unique_ips_current{user="hello"} 1870
telemt_user_unique_ips_recent_window{user="hello"} 817
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 143834.4 (39h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9508576
telemt_connections_bad_total 1070993
telemt_connections_current 5464
telemt_connections_me_current 5464
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 246616
telemt_upstream_connect_attempt_total 79817
telemt_upstream_connect_success_total 79234
telemt_upstream_connect_fail_total 505
telemt_upstream_connect_attempts_per_request{bucket="1"} 79739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32374
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1993
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 505
telemt_me_reconnect_attempts_total 8374
telemt_me_reconnect_success_total 1831
telemt_me_reader_eof_total 1701
telemt_me_idle_close_by_peer_total 1701
telemt_me_seq_mismatch_total 70
telemt_me_route_drop_no_conn_total 4075411
telemt_me_route_drop_channel_closed_total 300
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7305414
telemt_me_endpoint_quarantine_total 1097
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1084
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_me_writers_active_current 127
telemt_desync_total 32749
telemt_desync_full_logged_total 10719
telemt_desync_suppressed_total 22030
telemt_desync_frames_bucket_total{bucket="1_2"} 8119
telemt_desync_frames_bucket_total{bucket="3_10"} 12188
telemt_desync_frames_bucket_total{bucket="gt_10"} 12442
telemt_pool_swap_total 153
telemt_pool_force_close_total 4179
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 531
telemt_me_draining_writers_reap_progress_total 48194
telemt_me_writer_removed_unexpected_total 1726
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4933
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45052
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44015
telemt_me_writer_teardown_success_total{mode="normal"} 49985
telemt_me_writer_teardown_noop_total 48198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98183
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.267357
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98183
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 531
telemt_me_refill_failed_total 337
telemt_me_writer_restored_same_endpoint_total 1478
telemt_me_writer_restored_fallback_total 94
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 7313228
telemt_user_connections_current{user="hello"} 5464
telemt_user_octets_from_client{user="hello"} 129048866457 (120.19 GB)
telemt_user_octets_to_client{user="hello"} 2923888274723 (2.66 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2284
telemt_user_unique_ips_recent_window{user="hello"} 731
```