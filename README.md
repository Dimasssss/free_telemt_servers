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

# Server Metrics 2026-03-21 09:21:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 45908.3 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1273451
telemt_connections_bad_total 63790
telemt_connections_current 1544
telemt_connections_me_current 1544
telemt_handshake_timeouts_total 52464
telemt_upstream_connect_attempt_total 18019
telemt_upstream_connect_success_total 17938
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 762
telemt_me_reconnect_success_total 319
telemt_me_reader_eof_total 325
telemt_me_idle_close_by_peer_total 325
telemt_me_route_drop_no_conn_total 707301
telemt_me_route_drop_channel_closed_total 204
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 960318
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 367
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 4066
telemt_desync_full_logged_total 1392
telemt_desync_suppressed_total 2674
telemt_desync_frames_bucket_total{bucket="1_2"} 852
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1627
telemt_pool_swap_total 50
telemt_pool_force_close_total 1399
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 194
telemt_me_draining_writers_reap_progress_total 16145
telemt_me_writer_removed_unexpected_total 305
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1252
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15101
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1378
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14746
telemt_me_writer_teardown_success_total{mode="normal"} 16353
telemt_me_writer_teardown_noop_total 16146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32499
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 75.968858
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32499
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 194
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 279
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 959570
telemt_user_connections_current{user="hello"} 1544
telemt_user_octets_from_client{user="hello"} 13662125491 (12.72 GB)
telemt_user_octets_to_client{user="hello"} 265858868935 (247.60 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 45909.4 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3138728
telemt_connections_bad_total 340270
telemt_connections_current 4718
telemt_connections_me_current 4718
telemt_handshake_timeouts_total 91547
telemt_upstream_connect_attempt_total 16563
telemt_upstream_connect_success_total 16487
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 16539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 980
telemt_me_reconnect_success_total 374
telemt_me_reader_eof_total 368
telemt_me_idle_close_by_peer_total 367
telemt_me_route_drop_no_conn_total 1199569
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2077315
telemt_me_endpoint_quarantine_total 294
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 354
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
telemt_me_writers_active_current 47
telemt_desync_total 9055
telemt_desync_full_logged_total 3043
telemt_desync_suppressed_total 6012
telemt_desync_frames_bucket_total{bucket="1_2"} 1853
telemt_desync_frames_bucket_total{bucket="3_10"} 3548
telemt_desync_frames_bucket_total{bucket="gt_10"} 3654
telemt_pool_swap_total 49
telemt_pool_force_close_total 1478
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 14805
telemt_me_writer_removed_unexpected_total 345
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1362
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13784
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1394
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13327
telemt_me_writer_teardown_success_total{mode="normal"} 15146
telemt_me_writer_teardown_noop_total 14805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29951
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.195519
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29951
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 300
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2073219
telemt_user_connections_current{user="hello"} 4718
telemt_user_octets_from_client{user="hello"} 29797508040 (27.75 GB)
telemt_user_octets_to_client{user="hello"} 744291859652 (693.18 GB)
telemt_user_unique_ips_current{user="hello"} 1763
telemt_user_unique_ips_recent_window{user="hello"} 649
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 45905.8 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2268981
telemt_connections_bad_total 273706
telemt_connections_current 4116
telemt_connections_me_current 4116
telemt_handshake_timeouts_total 84035
telemt_upstream_connect_attempt_total 17996
telemt_upstream_connect_success_total 17986
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9794
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 607
telemt_me_reconnect_success_total 339
telemt_me_reader_eof_total 352
telemt_me_idle_close_by_peer_total 352
telemt_me_route_drop_no_conn_total 792390
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1762494
telemt_me_endpoint_quarantine_total 305
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 358
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
telemt_me_writers_active_current 45
telemt_desync_total 7541
telemt_desync_full_logged_total 2654
telemt_desync_suppressed_total 4887
telemt_desync_frames_bucket_total{bucket="1_2"} 1626
telemt_desync_frames_bucket_total{bucket="3_10"} 2923
telemt_desync_frames_bucket_total{bucket="gt_10"} 2992
telemt_pool_swap_total 49
telemt_pool_force_close_total 1446
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 184
telemt_me_draining_writers_reap_progress_total 16367
telemt_me_writer_removed_unexpected_total 332
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1335
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15261
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1370
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14921
telemt_me_writer_teardown_success_total{mode="normal"} 16596
telemt_me_writer_teardown_noop_total 16377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32973
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.460738
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32973
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 184
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 302
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1759545
telemt_user_connections_current{user="hello"} 4116
telemt_user_octets_from_client{user="hello"} 26618631620 (24.79 GB)
telemt_user_octets_to_client{user="hello"} 701939100280 (653.73 GB)
telemt_user_unique_ips_current{user="hello"} 1550
telemt_user_unique_ips_recent_window{user="hello"} 570
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 45907.2 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1904326
telemt_connections_bad_total 226586
telemt_connections_current 3478
telemt_connections_me_current 3478
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 80813
telemt_upstream_connect_attempt_total 22904
telemt_upstream_connect_success_total 22672
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 22796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 928
telemt_me_reconnect_success_total 428
telemt_me_reader_eof_total 394
telemt_me_idle_close_by_peer_total 394
telemt_me_route_drop_no_conn_total 540841
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1318828
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 360
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
telemt_desync_total 6215
telemt_desync_full_logged_total 2123
telemt_desync_suppressed_total 4092
telemt_desync_frames_bucket_total{bucket="1_2"} 1534
telemt_desync_frames_bucket_total{bucket="3_10"} 2476
telemt_desync_frames_bucket_total{bucket="gt_10"} 2205
telemt_pool_swap_total 49
telemt_pool_force_close_total 1331
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 16239
telemt_me_writer_removed_unexpected_total 387
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1295
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15345
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1252
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 79
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14908
telemt_me_writer_teardown_success_total{mode="normal"} 16640
telemt_me_writer_teardown_noop_total 16240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32880
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.763547
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32880
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1320992
telemt_user_connections_current{user="hello"} 3478
telemt_user_octets_from_client{user="hello"} 27281506785 (25.41 GB)
telemt_user_octets_to_client{user="hello"} 637397980999 (593.62 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1342
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 45871.1 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1828775
telemt_connections_bad_total 215129
telemt_connections_current 3352
telemt_connections_me_current 3352
telemt_handshake_timeouts_total 57734
telemt_upstream_connect_attempt_total 18893
telemt_upstream_connect_success_total 18874
telemt_upstream_connect_attempts_per_request{bucket="1"} 18874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10391
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 476
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 349
telemt_me_idle_close_by_peer_total 349
telemt_me_route_drop_no_conn_total 502693
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1318812
telemt_me_endpoint_quarantine_total 355
telemt_me_single_endpoint_shadow_rotate_total 352
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
telemt_me_writers_active_current 43
telemt_desync_total 6150
telemt_desync_full_logged_total 2157
telemt_desync_suppressed_total 3993
telemt_desync_frames_bucket_total{bucket="1_2"} 1612
telemt_desync_frames_bucket_total{bucket="3_10"} 2370
telemt_desync_frames_bucket_total{bucket="gt_10"} 2168
telemt_pool_swap_total 49
telemt_pool_force_close_total 1292
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 111
telemt_me_draining_writers_reap_progress_total 17033
telemt_me_writer_removed_unexpected_total 323
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1235
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16150
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1236
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15741
telemt_me_writer_teardown_success_total{mode="normal"} 17385
telemt_me_writer_teardown_noop_total 17036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34421
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.702240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34421
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 111
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 320
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1316530
telemt_user_connections_current{user="hello"} 3352
telemt_user_octets_from_client{user="hello"} 31553198120 (29.39 GB)
telemt_user_octets_to_client{user="hello"} 658453601664 (613.23 GB)
telemt_user_unique_ips_current{user="hello"} 1284
telemt_user_unique_ips_recent_window{user="hello"} 499
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 45910.4 (12h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5265738
telemt_connections_bad_total 278392
telemt_connections_current 5751
telemt_connections_me_current 5751
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 220440
telemt_upstream_connect_attempt_total 44905
telemt_upstream_connect_success_total 42894
telemt_upstream_connect_fail_total 1378
telemt_upstream_connect_attempts_per_request{bucket="1"} 44272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1284
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1378
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 2523
telemt_me_reconnect_success_total 928
telemt_me_reader_eof_total 668
telemt_me_idle_close_by_peer_total 667
telemt_me_route_drop_no_conn_total 8399180
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4438676
telemt_me_endpoint_quarantine_total 354
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 359
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
telemt_me_writers_active_current 127
telemt_desync_total 9351
telemt_desync_full_logged_total 3094
telemt_desync_suppressed_total 6257
telemt_desync_frames_bucket_total{bucket="1_2"} 2066
telemt_desync_frames_bucket_total{bucket="3_10"} 4026
telemt_desync_frames_bucket_total{bucket="gt_10"} 3259
telemt_pool_swap_total 46
telemt_pool_force_close_total 1353
telemt_me_writer_close_signal_drop_total 244
telemt_me_draining_writers_reap_progress_total 15575
telemt_me_writer_removed_unexpected_total 892
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1933
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14491
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14222
telemt_me_writer_teardown_success_total{mode="normal"} 16424
telemt_me_writer_teardown_noop_total 15581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32005
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 31.936103
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32005
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 244
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 659
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 4460700
telemt_user_connections_current{user="hello"} 5751
telemt_user_octets_from_client{user="hello"} 45070360006 (41.98 GB)
telemt_user_octets_to_client{user="hello"} 558052609710 (519.73 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1935
telemt_user_unique_ips_recent_window{user="hello"} 1011
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 45878.0 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1880298
telemt_connections_bad_total 242543
telemt_connections_current 3322
telemt_connections_me_current 3322
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 36148
telemt_upstream_connect_attempt_total 20434
telemt_upstream_connect_success_total 20232
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 20415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_reconnect_attempts_total 1880
telemt_me_reconnect_success_total 584
telemt_me_reader_eof_total 590
telemt_me_idle_close_by_peer_total 590
telemt_me_route_drop_no_conn_total 543740
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1403463
telemt_me_endpoint_quarantine_total 284
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 361
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
telemt_me_writers_active_current 48
telemt_desync_total 6378
telemt_desync_full_logged_total 2320
telemt_desync_suppressed_total 4058
telemt_desync_frames_bucket_total{bucket="1_2"} 1258
telemt_desync_frames_bucket_total{bucket="3_10"} 2575
telemt_desync_frames_bucket_total{bucket="gt_10"} 2545
telemt_pool_swap_total 48
telemt_pool_force_close_total 1248
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 16914
telemt_me_writer_removed_unexpected_total 567
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1488
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16016
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1170
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15666
telemt_me_writer_teardown_success_total{mode="normal"} 17504
telemt_me_writer_teardown_noop_total 16914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34418
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.524349
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34418
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 487
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1400214
telemt_user_connections_current{user="hello"} 3322
telemt_user_octets_from_client{user="hello"} 25236930212 (23.50 GB)
telemt_user_octets_to_client{user="hello"} 650172518802 (605.52 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1339
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 45872.5 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2571617
telemt_connections_bad_total 150450
telemt_connections_current 3351
telemt_connections_me_current 3351
telemt_handshake_timeouts_total 1024542
telemt_upstream_connect_attempt_total 19218
telemt_upstream_connect_success_total 19184
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 511
telemt_me_reconnect_success_total 292
telemt_me_reader_eof_total 293
telemt_me_idle_close_by_peer_total 293
telemt_me_route_drop_no_conn_total 485133
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1243095
telemt_me_endpoint_quarantine_total 358
telemt_me_single_endpoint_shadow_rotate_total 363
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
telemt_desync_total 6153
telemt_desync_full_logged_total 2169
telemt_desync_suppressed_total 3984
telemt_desync_frames_bucket_total{bucket="1_2"} 1089
telemt_desync_frames_bucket_total{bucket="3_10"} 2478
telemt_desync_frames_bucket_total{bucket="gt_10"} 2586
telemt_pool_swap_total 50
telemt_pool_force_close_total 1212
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 17222
telemt_me_writer_removed_unexpected_total 283
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1076
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16448
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1195
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16010
telemt_me_writer_teardown_success_total{mode="normal"} 17524
telemt_me_writer_teardown_noop_total 17222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34746
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.825701
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34746
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 259
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1238971
telemt_user_connections_current{user="hello"} 3351
telemt_user_octets_from_client{user="hello"} 21949862436 (20.44 GB)
telemt_user_octets_to_client{user="hello"} 618743748488 (576.25 GB)
telemt_user_unique_ips_current{user="hello"} 1362
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 43864.4 (12h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 546574
telemt_connections_bad_total 19709
telemt_connections_current 659
telemt_connections_me_current 659
telemt_handshake_timeouts_total 196805
telemt_upstream_connect_attempt_total 21549
telemt_upstream_connect_success_total 21547
telemt_upstream_connect_attempts_per_request{bucket="1"} 21547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 911
telemt_me_reconnect_success_total 360
telemt_me_reader_eof_total 357
telemt_me_idle_close_by_peer_total 357
telemt_me_route_drop_no_conn_total 117028
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288399
telemt_me_endpoint_quarantine_total 426
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 376
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 1840
telemt_desync_full_logged_total 738
telemt_desync_suppressed_total 1102
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 733
telemt_desync_frames_bucket_total{bucket="gt_10"} 753
telemt_pool_swap_total 48
telemt_pool_force_close_total 1034
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 19218
telemt_me_writer_removed_unexpected_total 338
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1384
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18176
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1032
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18184
telemt_me_writer_teardown_success_total{mode="normal"} 19560
telemt_me_writer_teardown_noop_total 19218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38778
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.792378
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38778
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 294
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 288563
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 4153575375 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 113937642849 (106.11 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 45882.3 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1937450
telemt_connections_bad_total 170218
telemt_connections_current 3706
telemt_connections_me_current 3706
telemt_handshake_timeouts_total 49088
telemt_upstream_connect_attempt_total 19909
telemt_upstream_connect_success_total 19822
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 19879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 736
telemt_me_reconnect_success_total 426
telemt_me_reader_eof_total 394
telemt_me_idle_close_by_peer_total 394
telemt_me_route_drop_no_conn_total 472720
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1530004
telemt_me_endpoint_quarantine_total 359
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 361
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
telemt_me_writers_active_current 46
telemt_desync_total 6075
telemt_desync_full_logged_total 2047
telemt_desync_suppressed_total 4028
telemt_desync_frames_bucket_total{bucket="1_2"} 1488
telemt_desync_frames_bucket_total{bucket="3_10"} 2290
telemt_desync_frames_bucket_total{bucket="gt_10"} 2297
telemt_pool_swap_total 50
telemt_pool_force_close_total 1226
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 113
telemt_me_draining_writers_reap_progress_total 17930
telemt_me_writer_removed_unexpected_total 393
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1316
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17016
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1203
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16704
telemt_me_writer_teardown_success_total{mode="normal"} 18332
telemt_me_writer_teardown_noop_total 17930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36262
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.352812
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36262
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 113
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 382
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1524614
telemt_user_connections_current{user="hello"} 3706
telemt_user_octets_from_client{user="hello"} 34509563332 (32.14 GB)
telemt_user_octets_to_client{user="hello"} 712810980372 (663.86 GB)
telemt_user_unique_ips_current{user="hello"} 1324
telemt_user_unique_ips_recent_window{user="hello"} 549
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 45879.4 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1831196
telemt_connections_bad_total 148989
telemt_connections_current 4053
telemt_connections_me_current 4053
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 45398
telemt_upstream_connect_attempt_total 28539
telemt_upstream_connect_success_total 28332
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 28497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_reconnect_attempts_total 2888
telemt_me_reconnect_success_total 593
telemt_me_reader_eof_total 516
telemt_me_idle_close_by_peer_total 516
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 490214
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1468522
telemt_me_endpoint_quarantine_total 410
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 359
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
telemt_me_writers_active_current 90
telemt_desync_total 5697
telemt_desync_full_logged_total 1890
telemt_desync_suppressed_total 3807
telemt_desync_frames_bucket_total{bucket="1_2"} 1569
telemt_desync_frames_bucket_total{bucket="3_10"} 2095
telemt_desync_frames_bucket_total{bucket="gt_10"} 2033
telemt_pool_swap_total 49
telemt_pool_force_close_total 1177
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 17151
telemt_me_writer_removed_unexpected_total 524
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1569
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16132
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15974
telemt_me_writer_teardown_success_total{mode="normal"} 17701
telemt_me_writer_teardown_noop_total 17152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34853
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.005274
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34853
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 130
telemt_me_writer_restored_same_endpoint_total 458
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1472541
telemt_user_connections_current{user="hello"} 4053
telemt_user_octets_from_client{user="hello"} 23015578399 (21.43 GB)
telemt_user_octets_to_client{user="hello"} 654477342099 (609.53 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1576
telemt_user_unique_ips_recent_window{user="hello"} 511
```