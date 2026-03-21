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

# Server Metrics 2026-03-21 13:26:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 60614.2 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2000253
telemt_connections_bad_total 100047
telemt_connections_current 1518
telemt_connections_me_current 1518
telemt_handshake_timeouts_total 72556
telemt_upstream_connect_attempt_total 23325
telemt_upstream_connect_success_total 23210
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 23287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1317
telemt_me_reconnect_success_total 532
telemt_me_reader_eof_total 515
telemt_me_idle_close_by_peer_total 515
telemt_me_route_drop_no_conn_total 1494028
telemt_me_route_drop_channel_closed_total 498
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1577201
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 428
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 480
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 6255
telemt_desync_full_logged_total 2149
telemt_desync_suppressed_total 4106
telemt_desync_frames_bucket_total{bucket="1_2"} 1398
telemt_desync_frames_bucket_total{bucket="3_10"} 2366
telemt_desync_frames_bucket_total{bucket="gt_10"} 2491
telemt_pool_swap_total 66
telemt_pool_force_close_total 1963
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 20862
telemt_me_writer_removed_unexpected_total 495
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1719
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19463
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18899
telemt_me_writer_teardown_success_total{mode="normal"} 21182
telemt_me_writer_teardown_noop_total 20867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42049
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 166.260573
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42049
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 459
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1575976
telemt_user_connections_current{user="hello"} 1518
telemt_user_octets_from_client{user="hello"} 23587906471 (21.97 GB)
telemt_user_octets_to_client{user="hello"} 410685377991 (382.48 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 575
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 167.4 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25703
telemt_connections_bad_total 1919
telemt_connections_current 3805
telemt_connections_me_current 3805
telemt_handshake_timeouts_total 369
telemt_upstream_connect_attempt_total 125
telemt_upstream_connect_success_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_success_total 5
telemt_me_route_drop_no_conn_total 8406
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21437
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_me_writers_active_current 47
telemt_desync_total 89
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_draining_writers_reap_progress_total 44
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44
telemt_me_writer_teardown_success_total{mode="normal"} 44
telemt_me_writer_teardown_noop_total 44
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.000920
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88
telemt_user_connections_total{user="hello"} 21424
telemt_user_connections_current{user="hello"} 3805
telemt_user_octets_from_client{user="hello"} 120567156 (114.98 MB)
telemt_user_octets_to_client{user="hello"} 3017984148 (2.81 GB)
telemt_user_unique_ips_current{user="hello"} 1265
telemt_user_unique_ips_recent_window{user="hello"} 706
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 60611.9 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3961313
telemt_connections_bad_total 391486
telemt_connections_current 5136
telemt_connections_me_current 5136
telemt_handshake_timeouts_total 152852
telemt_upstream_connect_attempt_total 22906
telemt_upstream_connect_success_total 22871
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 891
telemt_me_reconnect_success_total 521
telemt_me_reader_eof_total 518
telemt_me_idle_close_by_peer_total 518
telemt_me_route_drop_no_conn_total 1999529
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3188799
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 462
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
telemt_me_writers_active_current 94
telemt_desync_total 13427
telemt_desync_full_logged_total 4548
telemt_desync_suppressed_total 8879
telemt_desync_frames_bucket_total{bucket="1_2"} 2847
telemt_desync_frames_bucket_total{bucket="3_10"} 5273
telemt_desync_frames_bucket_total{bucket="gt_10"} 5307
telemt_pool_swap_total 64
telemt_pool_force_close_total 2022
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 309
telemt_me_draining_writers_reap_progress_total 20742
telemt_me_writer_removed_unexpected_total 501
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1806
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19246
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1871
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18720
telemt_me_writer_teardown_success_total{mode="normal"} 21052
telemt_me_writer_teardown_noop_total 20760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41812
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 62.532323
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41812
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 309
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 473
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 3184785
telemt_user_connections_current{user="hello"} 5136
telemt_user_octets_from_client{user="hello"} 52180213796 (48.60 GB)
telemt_user_octets_to_client{user="hello"} 1095615368456 (1020.37 GB)
telemt_user_unique_ips_current{user="hello"} 2030
telemt_user_unique_ips_recent_window{user="hello"} 582
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 60613.1 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3227687
telemt_connections_bad_total 355150
telemt_connections_current 3863
telemt_connections_me_current 3863
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 123332
telemt_upstream_connect_attempt_total 27468
telemt_upstream_connect_success_total 27194
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 27328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12531
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 477
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1161
telemt_me_reconnect_success_total 546
telemt_me_reader_eof_total 509
telemt_me_idle_close_by_peer_total 509
telemt_me_route_drop_no_conn_total 1006605
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2326386
telemt_me_endpoint_quarantine_total 396
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 465
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
telemt_desync_total 10670
telemt_desync_full_logged_total 3615
telemt_desync_suppressed_total 7055
telemt_desync_frames_bucket_total{bucket="1_2"} 2661
telemt_desync_frames_bucket_total{bucket="3_10"} 4108
telemt_desync_frames_bucket_total{bucket="gt_10"} 3901
telemt_pool_swap_total 66
telemt_pool_force_close_total 1856
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 165
telemt_me_draining_writers_reap_progress_total 20152
telemt_me_writer_removed_unexpected_total 496
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1714
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18955
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1733
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 123
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18296
telemt_me_writer_teardown_success_total{mode="normal"} 20669
telemt_me_writer_teardown_noop_total 20153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40822
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.357352
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40822
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 165
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 460
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 2327170
telemt_user_connections_current{user="hello"} 3863
telemt_user_octets_from_client{user="hello"} 43712481925 (40.71 GB)
telemt_user_octets_to_client{user="hello"} 1098067570039 (1022.66 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1396
telemt_user_unique_ips_recent_window{user="hello"} 504
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 60577.3 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3140051
telemt_connections_bad_total 335776
telemt_connections_current 3420
telemt_connections_me_current 3420
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 91020
telemt_upstream_connect_attempt_total 32671
telemt_upstream_connect_success_total 32444
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 32577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13895
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 843
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1276
telemt_me_reconnect_success_total 616
telemt_me_reader_eof_total 559
telemt_me_idle_close_by_peer_total 559
telemt_me_route_drop_no_conn_total 963529
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2296674
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 455
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 10654
telemt_desync_full_logged_total 3550
telemt_desync_suppressed_total 7104
telemt_desync_frames_bucket_total{bucket="1_2"} 2706
telemt_desync_frames_bucket_total{bucket="3_10"} 4036
telemt_desync_frames_bucket_total{bucket="gt_10"} 3912
telemt_pool_swap_total 64
telemt_pool_force_close_total 1809
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 211
telemt_me_draining_writers_reap_progress_total 21523
telemt_me_writer_removed_unexpected_total 533
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1820
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20270
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1646
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 163
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19714
telemt_me_writer_teardown_success_total{mode="normal"} 22090
telemt_me_writer_teardown_noop_total 21527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43617
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.708309
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43617
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 211
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 537
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2301470
telemt_user_connections_current{user="hello"} 3420
telemt_user_octets_from_client{user="hello"} 51046062345 (47.54 GB)
telemt_user_octets_to_client{user="hello"} 1094609656628 (1019.43 GB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1317
telemt_user_unique_ips_recent_window{user="hello"} 474
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 60616.4 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10607728
telemt_connections_bad_total 720949
telemt_connections_current 5483
telemt_connections_me_current 5483
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 339543
telemt_upstream_connect_attempt_total 90014
telemt_upstream_connect_success_total 84781
telemt_upstream_connect_fail_total 4333
telemt_upstream_connect_attempts_per_request{bucket="1"} 89114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4333
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3543
telemt_me_reconnect_success_total 1235
telemt_me_reader_eof_total 890
telemt_me_idle_close_by_peer_total 889
telemt_me_route_drop_no_conn_total 19642220
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8719898
telemt_me_endpoint_quarantine_total 458
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 475
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
telemt_desync_total 16343
telemt_desync_full_logged_total 5218
telemt_desync_suppressed_total 11125
telemt_desync_frames_bucket_total{bucket="1_2"} 3463
telemt_desync_frames_bucket_total{bucket="3_10"} 7171
telemt_desync_frames_bucket_total{bucket="gt_10"} 5709
telemt_pool_swap_total 61
telemt_pool_force_close_total 2016
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 406
telemt_me_draining_writers_reap_progress_total 19852
telemt_me_writer_removed_unexpected_total 1199
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2582
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18300
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1685
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 331
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17836
telemt_me_writer_teardown_success_total{mode="normal"} 20882
telemt_me_writer_teardown_noop_total 19862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40744
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.273783
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40744
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 406
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 874
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 8777367
telemt_user_connections_current{user="hello"} 5483
telemt_user_octets_from_client{user="hello"} 67191793605 (62.58 GB)
telemt_user_octets_to_client{user="hello"} 718614097380 (669.26 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 1956
telemt_user_unique_ips_recent_window{user="hello"} 1029
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 60583.8 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3166977
telemt_connections_bad_total 367965
telemt_connections_current 3568
telemt_connections_me_current 3568
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 69955
telemt_upstream_connect_attempt_total 26074
telemt_upstream_connect_success_total 25789
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 26044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 2530
telemt_me_reconnect_success_total 901
telemt_me_reader_eof_total 894
telemt_me_idle_close_by_peer_total 894
telemt_me_route_drop_no_conn_total 1210339
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2411101
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 461
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
telemt_me_writers_active_current 46
telemt_desync_total 11267
telemt_desync_full_logged_total 3913
telemt_desync_suppressed_total 7354
telemt_desync_frames_bucket_total{bucket="1_2"} 2193
telemt_desync_frames_bucket_total{bucket="3_10"} 4487
telemt_desync_frames_bucket_total{bucket="gt_10"} 4587
telemt_pool_swap_total 61
telemt_pool_force_close_total 1741
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 21795
telemt_me_writer_removed_unexpected_total 864
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2120
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20569
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1527
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 214
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20054
telemt_me_writer_teardown_success_total{mode="normal"} 22689
telemt_me_writer_teardown_noop_total 21796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44293
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44485
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.825943
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44485
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 766
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 2395722
telemt_user_connections_current{user="hello"} 3568
telemt_user_octets_from_client{user="hello"} 48472850204 (45.14 GB)
telemt_user_octets_to_client{user="hello"} 1043029730950 (971.40 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1392
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 60578.5 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4843944
telemt_connections_bad_total 238011
telemt_connections_current 3278
telemt_connections_me_current 3278
telemt_handshake_timeouts_total 2140724
telemt_upstream_connect_attempt_total 24034
telemt_upstream_connect_success_total 24000
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 290
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1014
telemt_me_reconnect_success_total 432
telemt_me_reader_eof_total 440
telemt_me_idle_close_by_peer_total 440
telemt_me_route_drop_no_conn_total 1103308
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2171806
telemt_me_endpoint_quarantine_total 451
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 471
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
telemt_desync_total 10335
telemt_desync_full_logged_total 3669
telemt_desync_suppressed_total 6666
telemt_desync_frames_bucket_total{bucket="1_2"} 1906
telemt_desync_frames_bucket_total{bucket="3_10"} 4109
telemt_desync_frames_bucket_total{bucket="gt_10"} 4320
telemt_pool_swap_total 66
telemt_pool_force_close_total 1684
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 21508
telemt_me_writer_removed_unexpected_total 422
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1476
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20481
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1627
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 57
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19824
telemt_me_writer_teardown_success_total{mode="normal"} 21957
telemt_me_writer_teardown_noop_total 21508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43465
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.579942
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43465
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 2164975
telemt_user_connections_current{user="hello"} 3278
telemt_user_octets_from_client{user="hello"} 43878490384 (40.87 GB)
telemt_user_octets_to_client{user="hello"} 1010652069776 (941.24 GB)
telemt_user_unique_ips_current{user="hello"} 1266
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 58570.0 (16h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1041445
telemt_connections_bad_total 133301
telemt_connections_current 706
telemt_connections_me_current 706
telemt_handshake_timeouts_total 362253
telemt_upstream_connect_attempt_total 27588
telemt_upstream_connect_success_total 27586
telemt_upstream_connect_attempts_per_request{bucket="1"} 27586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1187
telemt_me_reconnect_success_total 459
telemt_me_reader_eof_total 456
telemt_me_idle_close_by_peer_total 456
telemt_me_route_drop_no_conn_total 217161
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476684
telemt_me_endpoint_quarantine_total 535
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 493
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
telemt_me_writers_active_current 48
telemt_me_writers_warm_current 26
telemt_desync_total 3163
telemt_desync_full_logged_total 1180
telemt_desync_suppressed_total 1983
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 1126
telemt_desync_frames_bucket_total{bucket="gt_10"} 1487
telemt_pool_swap_total 64
telemt_pool_force_close_total 1441
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 24699
telemt_me_writer_removed_unexpected_total 431
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1815
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23325
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1438
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23258
telemt_me_writer_teardown_success_total{mode="normal"} 25140
telemt_me_writer_teardown_noop_total 24699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49839
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.267129
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49839
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 372
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 476489
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 8606749739 (8.02 GB)
telemt_user_octets_to_client{user="hello"} 182085815849 (169.58 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 60588.2 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3426903
telemt_connections_bad_total 322144
telemt_connections_current 4086
telemt_connections_me_current 4086
telemt_handshake_timeouts_total 101984
telemt_upstream_connect_attempt_total 24844
telemt_upstream_connect_success_total 24741
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 24813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12395
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1016
telemt_me_reconnect_success_total 568
telemt_me_reader_eof_total 528
telemt_me_idle_close_by_peer_total 528
telemt_me_route_drop_no_conn_total 985091
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2706281
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 468
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
telemt_me_writers_active_current 46
telemt_desync_total 10900
telemt_desync_full_logged_total 3577
telemt_desync_suppressed_total 7323
telemt_desync_frames_bucket_total{bucket="1_2"} 2594
telemt_desync_frames_bucket_total{bucket="3_10"} 4057
telemt_desync_frames_bucket_total{bucket="gt_10"} 4249
telemt_pool_swap_total 67
telemt_pool_force_close_total 1731
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 22310
telemt_me_writer_removed_unexpected_total 519
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1735
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21092
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1700
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20579
telemt_me_writer_teardown_success_total{mode="normal"} 22827
telemt_me_writer_teardown_noop_total 22310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45137
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.633186
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45137
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 501
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 2698911
telemt_user_connections_current{user="hello"} 4086
telemt_user_octets_from_client{user="hello"} 57356797728 (53.42 GB)
telemt_user_octets_to_client{user="hello"} 1272015666856 (1.16 TB)
telemt_user_unique_ips_current{user="hello"} 1478
telemt_user_unique_ips_recent_window{user="hello"} 574
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 60584.9 (16h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3076233
telemt_connections_bad_total 257099
telemt_connections_current 3946
telemt_connections_me_current 3946
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 90793
telemt_upstream_connect_attempt_total 41057
telemt_upstream_connect_success_total 40791
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 41012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 587
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_reconnect_attempts_total 3492
telemt_me_reconnect_success_total 739
telemt_me_reader_eof_total 645
telemt_me_idle_close_by_peer_total 645
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 1025308
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2474099
telemt_me_endpoint_quarantine_total 520
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 470
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_me_writers_active_current 41
telemt_desync_total 9561
telemt_desync_full_logged_total 3265
telemt_desync_suppressed_total 6296
telemt_desync_frames_bucket_total{bucket="1_2"} 2439
telemt_desync_frames_bucket_total{bucket="3_10"} 3529
telemt_desync_frames_bucket_total{bucket="gt_10"} 3593
telemt_pool_swap_total 66
telemt_pool_force_close_total 1678
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 21507
telemt_me_writer_removed_unexpected_total 657
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2041
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20153
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1567
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 111
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19829
telemt_me_writer_teardown_success_total{mode="normal"} 22194
telemt_me_writer_teardown_noop_total 21508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43702
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.919007
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43702
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 563
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2483488
telemt_user_connections_current{user="hello"} 3946
telemt_user_octets_from_client{user="hello"} 45648044733 (42.51 GB)
telemt_user_octets_to_client{user="hello"} 1085480279748 (1010.93 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1412
telemt_user_unique_ips_recent_window{user="hello"} 498
```