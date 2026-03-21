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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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
- Оплачен до: 25 марта
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
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
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

# Server Metrics 2026-03-21 15:23:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 67637.4 (18h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2388486
telemt_connections_bad_total 118356
telemt_connections_current 1463
telemt_connections_me_current 1463
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 77581
telemt_upstream_connect_attempt_total 28905
telemt_upstream_connect_success_total 28778
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 28862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1650
telemt_me_reconnect_success_total 662
telemt_me_reader_eof_total 635
telemt_me_idle_close_by_peer_total 635
telemt_me_route_drop_no_conn_total 2104018
telemt_me_route_drop_channel_closed_total 635
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1916199
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 476
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 526
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 7430
telemt_desync_full_logged_total 2581
telemt_desync_suppressed_total 4849
telemt_desync_frames_bucket_total{bucket="1_2"} 1627
telemt_desync_frames_bucket_total{bucket="3_10"} 2827
telemt_desync_frames_bucket_total{bucket="gt_10"} 2976
telemt_pool_swap_total 73
telemt_pool_force_close_total 2186
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 499
telemt_me_draining_writers_reap_progress_total 23100
telemt_me_writer_removed_unexpected_total 613
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1978
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21519
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2070
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20914
telemt_me_writer_teardown_success_total{mode="normal"} 23497
telemt_me_writer_teardown_noop_total 23106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46603
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 219.668226
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46603
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 499
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 567
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1917704
telemt_user_connections_current{user="hello"} 1463
telemt_user_octets_from_client{user="hello"} 26971761041 (25.12 GB)
telemt_user_octets_to_client{user="hello"} 472239392282 (439.81 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 38.2 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2135
telemt_connections_bad_total 24
telemt_connections_current 1561
telemt_connections_me_current 1561
telemt_upstream_connect_attempt_total 91
telemt_upstream_connect_success_total 88
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 148
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2055
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 6
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_draining_writers_reap_progress_total 6
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6
telemt_me_writer_teardown_success_total{mode="normal"} 6
telemt_me_writer_teardown_noop_total 6
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.000820
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12
telemt_user_connections_total{user="hello"} 2055
telemt_user_connections_current{user="hello"} 1561
telemt_user_octets_from_client{user="hello"} 11526452 (10.99 MB)
telemt_user_octets_to_client{user="hello"} 69245856 (66.04 MB)
telemt_user_unique_ips_current{user="hello"} 644
telemt_user_unique_ips_recent_window{user="hello"} 702
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 67634.9 (18h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4753750
telemt_connections_bad_total 421422
telemt_connections_current 6026
telemt_connections_me_current 6026
telemt_handshake_timeouts_total 171201
telemt_upstream_connect_attempt_total 25108
telemt_upstream_connect_success_total 25055
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 25060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1149
telemt_me_reconnect_success_total 576
telemt_me_reader_eof_total 580
telemt_me_idle_close_by_peer_total 580
telemt_me_route_drop_no_conn_total 2652905
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3893986
telemt_me_endpoint_quarantine_total 428
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 509
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_desync_total 15920
telemt_desync_full_logged_total 5373
telemt_desync_suppressed_total 10547
telemt_desync_frames_bucket_total{bucket="1_2"} 3400
telemt_desync_frames_bucket_total{bucket="3_10"} 6264
telemt_desync_frames_bucket_total{bucket="gt_10"} 6256
telemt_pool_swap_total 72
telemt_pool_force_close_total 2300
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 363
telemt_me_draining_writers_reap_progress_total 22731
telemt_me_writer_removed_unexpected_total 561
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1995
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21079
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2102
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 198
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20431
telemt_me_writer_teardown_success_total{mode="normal"} 23074
telemt_me_writer_teardown_noop_total 22763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45837
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 77.819135
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45837
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 363
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 518
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 3889282
telemt_user_connections_current{user="hello"} 6026
telemt_user_octets_from_client{user="hello"} 62798395280 (58.49 GB)
telemt_user_octets_to_client{user="hello"} 1283704708840 (1.17 TB)
telemt_user_unique_ips_current{user="hello"} 2206
telemt_user_unique_ips_recent_window{user="hello"} 976
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 67636.8 (18h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3866880
telemt_connections_bad_total 418207
telemt_connections_current 3552
telemt_connections_me_current 3552
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 138480
telemt_upstream_connect_attempt_total 29540
telemt_upstream_connect_success_total 29259
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 29398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 485
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1379
telemt_me_reconnect_success_total 600
telemt_me_reader_eof_total 560
telemt_me_idle_close_by_peer_total 560
telemt_me_route_drop_no_conn_total 1216453
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2831964
telemt_me_endpoint_quarantine_total 440
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 513
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 13169
telemt_desync_full_logged_total 4426
telemt_desync_suppressed_total 8743
telemt_desync_frames_bucket_total{bucket="1_2"} 3308
telemt_desync_frames_bucket_total{bucket="3_10"} 5083
telemt_desync_frames_bucket_total{bucket="gt_10"} 4778
telemt_pool_swap_total 74
telemt_pool_force_close_total 2113
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 210
telemt_me_draining_writers_reap_progress_total 21972
telemt_me_writer_removed_unexpected_total 544
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1899
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20619
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1960
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 153
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19859
telemt_me_writer_teardown_success_total{mode="normal"} 22518
telemt_me_writer_teardown_noop_total 21973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44491
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.913527
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44491
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 210
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 504
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2831702
telemt_user_connections_current{user="hello"} 3552
telemt_user_octets_from_client{user="hello"} 53689584737 (50.00 GB)
telemt_user_octets_to_client{user="hello"} 1319068724895 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1373
telemt_user_unique_ips_recent_window{user="hello"} 882
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 67600.5 (18h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3794826
telemt_connections_bad_total 393419
telemt_connections_current 4109
telemt_connections_me_current 4109
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 114339
telemt_upstream_connect_attempt_total 34778
telemt_upstream_connect_success_total 34543
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15027
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 854
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1387
telemt_me_reconnect_success_total 653
telemt_me_reader_eof_total 594
telemt_me_idle_close_by_peer_total 594
telemt_me_route_drop_no_conn_total 1322288
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2816727
telemt_me_endpoint_quarantine_total 483
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 503
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
telemt_me_writers_active_current 43
telemt_desync_total 12929
telemt_desync_full_logged_total 4310
telemt_desync_suppressed_total 8619
telemt_desync_frames_bucket_total{bucket="1_2"} 3236
telemt_desync_frames_bucket_total{bucket="3_10"} 4850
telemt_desync_frames_bucket_total{bucket="gt_10"} 4843
telemt_pool_swap_total 72
telemt_pool_force_close_total 2036
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 232
telemt_me_draining_writers_reap_progress_total 23383
telemt_me_writer_removed_unexpected_total 565
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1978
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22007
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1856
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 180
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21347
telemt_me_writer_teardown_success_total{mode="normal"} 23985
telemt_me_writer_teardown_noop_total 23388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47373
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.519742
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47373
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 232
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 563
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2820623
telemt_user_connections_current{user="hello"} 4109
telemt_user_octets_from_client{user="hello"} 60086509453 (55.96 GB)
telemt_user_octets_to_client{user="hello"} 1307659196668 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1615
telemt_user_unique_ips_recent_window{user="hello"} 772
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 67639.8 (18h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13026496
telemt_connections_bad_total 847017
telemt_connections_current 5489
telemt_connections_me_current 5489
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 396500
telemt_upstream_connect_attempt_total 115946
telemt_upstream_connect_success_total 106052
telemt_upstream_connect_fail_total 8852
telemt_upstream_connect_attempts_per_request{bucket="1"} 114904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8852
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3868
telemt_me_reconnect_success_total 1411
telemt_me_reader_eof_total 980
telemt_me_idle_close_by_peer_total 979
telemt_me_route_drop_no_conn_total 25226124
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10706882
telemt_me_endpoint_quarantine_total 522
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 527
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
telemt_me_writers_active_current 48
telemt_desync_total 18922
telemt_desync_full_logged_total 5936
telemt_desync_suppressed_total 12986
telemt_desync_frames_bucket_total{bucket="1_2"} 4093
telemt_desync_frames_bucket_total{bucket="3_10"} 8333
telemt_desync_frames_bucket_total{bucket="gt_10"} 6496
telemt_pool_swap_total 69
telemt_pool_force_close_total 2220
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 487
telemt_me_draining_writers_reap_progress_total 21695
telemt_me_writer_removed_unexpected_total 1342
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2864
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19964
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1854
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 366
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19475
telemt_me_writer_teardown_success_total{mode="normal"} 22828
telemt_me_writer_teardown_noop_total 21707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44535
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 170.741525
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44535
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 487
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 985
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 10782470
telemt_user_connections_current{user="hello"} 5490
telemt_user_octets_from_client{user="hello"} 76696381221 (71.43 GB)
telemt_user_octets_to_client{user="hello"} 797845559865 (743.05 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 1930
telemt_user_unique_ips_recent_window{user="hello"} 1375
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 67607.3 (18h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3808232
telemt_connections_bad_total 422285
telemt_connections_current 4140
telemt_connections_me_current 4140
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 82153
telemt_upstream_connect_attempt_total 28444
telemt_upstream_connect_success_total 28134
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 28400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_reconnect_attempts_total 2683
telemt_me_reconnect_success_total 978
telemt_me_reader_eof_total 972
telemt_me_idle_close_by_peer_total 972
telemt_me_route_drop_no_conn_total 1606912
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2935655
telemt_me_endpoint_quarantine_total 420
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 504
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 13880
telemt_desync_full_logged_total 4842
telemt_desync_suppressed_total 9038
telemt_desync_frames_bucket_total{bucket="1_2"} 2710
telemt_desync_frames_bucket_total{bucket="3_10"} 5489
telemt_desync_frames_bucket_total{bucket="gt_10"} 5681
telemt_pool_swap_total 68
telemt_pool_force_close_total 1951
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 197
telemt_me_draining_writers_reap_progress_total 23866
telemt_me_writer_removed_unexpected_total 943
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2344
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22497
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1693
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21915
telemt_me_writer_teardown_success_total{mode="normal"} 24841
telemt_me_writer_teardown_noop_total 23867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48708
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.407047
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48708
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 197
telemt_me_refill_failed_total 93
telemt_me_writer_restored_same_endpoint_total 839
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2919205
telemt_user_connections_current{user="hello"} 4140
telemt_user_octets_from_client{user="hello"} 76218558532 (70.98 GB)
telemt_user_octets_to_client{user="hello"} 1215718710358 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1672
telemt_user_unique_ips_recent_window{user="hello"} 606
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 4443.0 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 720553
telemt_connections_bad_total 18713
telemt_connections_current 3492
telemt_connections_me_current 3492
telemt_handshake_timeouts_total 353714
telemt_upstream_connect_attempt_total 1627
telemt_upstream_connect_success_total 1594
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 851
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 205
telemt_me_reconnect_success_total 75
telemt_me_reader_eof_total 66
telemt_me_idle_close_by_peer_total 66
telemt_me_route_drop_no_conn_total 345438
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327245
telemt_me_endpoint_quarantine_total 17
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 1528
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 1031
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 581
telemt_desync_frames_bucket_total{bucket="gt_10"} 692
telemt_pool_swap_total 3
telemt_pool_force_close_total 116
telemt_me_writer_close_signal_drop_total 9
telemt_me_draining_writers_reap_progress_total 1338
telemt_me_writer_removed_unexpected_total 67
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 140
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1265
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1222
telemt_me_writer_teardown_success_total{mode="normal"} 1405
telemt_me_writer_teardown_noop_total 1338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2743
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.500727
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2743
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 9
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 66
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 326806
telemt_user_connections_current{user="hello"} 3492
telemt_user_octets_from_client{user="hello"} 9676396152 (9.01 GB)
telemt_user_octets_to_client{user="hello"} 116202194700 (108.22 GB)
telemt_user_unique_ips_current{user="hello"} 1424
telemt_user_unique_ips_recent_window{user="hello"} 515
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 65593.4 (18h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1217392
telemt_connections_bad_total 138235
telemt_connections_current 862
telemt_connections_me_current 862
telemt_handshake_timeouts_total 433972
telemt_upstream_connect_attempt_total 30735
telemt_upstream_connect_success_total 30728
telemt_upstream_connect_attempts_per_request{bucket="1"} 30728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1310
telemt_me_reconnect_success_total 541
telemt_me_reader_eof_total 541
telemt_me_idle_close_by_peer_total 541
telemt_me_route_drop_no_conn_total 265696
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 570610
telemt_me_endpoint_quarantine_total 586
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 549
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_writers_active_current 47
telemt_desync_total 3574
telemt_desync_full_logged_total 1302
telemt_desync_suppressed_total 2272
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 1282
telemt_desync_frames_bucket_total{bucket="gt_10"} 1633
telemt_pool_swap_total 71
telemt_pool_force_close_total 1651
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 111
telemt_me_draining_writers_reap_progress_total 27537
telemt_me_writer_removed_unexpected_total 514
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2062
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26002
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1628
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25886
telemt_me_writer_teardown_success_total{mode="normal"} 28064
telemt_me_writer_teardown_noop_total 27537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55601
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.073826
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55601
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 111
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 450
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 570280
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 11694827679 (10.89 GB)
telemt_user_octets_to_client{user="hello"} 217222509397 (202.30 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 67611.6 (18h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4177280
telemt_connections_bad_total 377971
telemt_connections_current 4739
telemt_connections_me_current 4739
telemt_handshake_timeouts_total 137960
telemt_upstream_connect_attempt_total 26944
telemt_upstream_connect_success_total 26831
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 26909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 1144
telemt_me_reconnect_success_total 611
telemt_me_reader_eof_total 577
telemt_me_idle_close_by_peer_total 577
telemt_me_route_drop_no_conn_total 1270222
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3327674
telemt_me_endpoint_quarantine_total 495
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 514
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 13016
telemt_desync_full_logged_total 4303
telemt_desync_suppressed_total 8713
telemt_desync_frames_bucket_total{bucket="1_2"} 3072
telemt_desync_frames_bucket_total{bucket="3_10"} 4851
telemt_desync_frames_bucket_total{bucket="gt_10"} 5093
telemt_pool_swap_total 75
telemt_pool_force_close_total 1942
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 222
telemt_me_draining_writers_reap_progress_total 24136
telemt_me_writer_removed_unexpected_total 566
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1921
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22782
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1896
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22194
telemt_me_writer_teardown_success_total{mode="normal"} 24703
telemt_me_writer_teardown_noop_total 24136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48839
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.699303
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48839
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 222
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 542
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 3319359
telemt_user_connections_current{user="hello"} 4739
telemt_user_octets_from_client{user="hello"} 67891303680 (63.23 GB)
telemt_user_octets_to_client{user="hello"} 1562990688940 (1.42 TB)
telemt_user_unique_ips_current{user="hello"} 1741
telemt_user_unique_ips_recent_window{user="hello"} 606
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 67608.3 (18h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3723839
telemt_connections_bad_total 332425
telemt_connections_current 3738
telemt_connections_me_current 3738
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 113436
telemt_upstream_connect_attempt_total 43452
telemt_upstream_connect_success_total 43157
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 43401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15381
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 600
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_reconnect_attempts_total 3832
telemt_me_reconnect_success_total 839
telemt_me_reader_eof_total 736
telemt_me_idle_close_by_peer_total 736
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1351400
telemt_me_route_drop_channel_closed_total 101
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2990610
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 511
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_me_writers_warm_current 40
telemt_desync_total 11737
telemt_desync_full_logged_total 3981
telemt_desync_suppressed_total 7756
telemt_desync_frames_bucket_total{bucket="1_2"} 2930
telemt_desync_frames_bucket_total{bucket="3_10"} 4368
telemt_desync_frames_bucket_total{bucket="gt_10"} 4439
telemt_pool_swap_total 72
telemt_pool_force_close_total 1878
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 209
telemt_me_draining_writers_reap_progress_total 23549
telemt_me_writer_removed_unexpected_total 748
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2285
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22044
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1724
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 154
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21671
telemt_me_writer_teardown_success_total{mode="normal"} 24329
telemt_me_writer_teardown_noop_total 23550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47879
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.967026
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47879
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 209
telemt_me_refill_failed_total 170
telemt_me_writer_restored_same_endpoint_total 651
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 57
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2999169
telemt_user_connections_current{user="hello"} 3738
telemt_user_octets_from_client{user="hello"} 53940445013 (50.24 GB)
telemt_user_octets_to_client{user="hello"} 1285764507580 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1583
telemt_user_unique_ips_recent_window{user="hello"} 517
```