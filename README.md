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

# Server Metrics 2026-03-21 10:37:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 50502.1 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1467020
telemt_connections_bad_total 75486
telemt_connections_current 1661
telemt_connections_me_current 1661
telemt_handshake_timeouts_total 59084
telemt_upstream_connect_attempt_total 19874
telemt_upstream_connect_success_total 19784
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 19850
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12659
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 931
telemt_me_reconnect_success_total 405
telemt_me_reader_eof_total 408
telemt_me_idle_close_by_peer_total 408
telemt_me_route_drop_no_conn_total 790867
telemt_me_route_drop_channel_closed_total 305
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1117377
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 349
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 401
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
telemt_me_writers_active_current 50
telemt_me_writers_warm_current 32
telemt_desync_total 4703
telemt_desync_full_logged_total 1636
telemt_desync_suppressed_total 3067
telemt_desync_frames_bucket_total{bucket="1_2"} 976
telemt_desync_frames_bucket_total{bucket="3_10"} 1821
telemt_desync_frames_bucket_total{bucket="gt_10"} 1906
telemt_pool_swap_total 54
telemt_pool_force_close_total 1541
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 247
telemt_me_draining_writers_reap_progress_total 17748
telemt_me_writer_removed_unexpected_total 386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1422
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16608
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1485
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16207
telemt_me_writer_teardown_success_total{mode="normal"} 18030
telemt_me_writer_teardown_noop_total 17750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35780
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 95.611036
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35780
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 247
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1116528
telemt_user_connections_current{user="hello"} 1661
telemt_user_octets_from_client{user="hello"} 15665909951 (14.59 GB)
telemt_user_octets_to_client{user="hello"} 317498734227 (295.69 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 591
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 50503.5 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3782748
telemt_connections_bad_total 381014
telemt_connections_current 4469
telemt_connections_me_current 4469
telemt_handshake_timeouts_total 110072
telemt_upstream_connect_attempt_total 17994
telemt_upstream_connect_success_total 17909
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 17967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1101
telemt_me_reconnect_success_total 413
telemt_me_reader_eof_total 406
telemt_me_idle_close_by_peer_total 405
telemt_me_route_drop_no_conn_total 1760737
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2605025
telemt_me_endpoint_quarantine_total 316
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 385
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
telemt_me_writers_warm_current 38
telemt_desync_total 11140
telemt_desync_full_logged_total 3743
telemt_desync_suppressed_total 7397
telemt_desync_frames_bucket_total{bucket="1_2"} 2272
telemt_desync_frames_bucket_total{bucket="3_10"} 4399
telemt_desync_frames_bucket_total{bucket="gt_10"} 4469
telemt_pool_swap_total 54
telemt_pool_force_close_total 1657
telemt_me_writer_close_signal_drop_total 206
telemt_me_draining_writers_reap_progress_total 16051
telemt_me_writer_removed_unexpected_total 380
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1489
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14928
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1559
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 98
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14394
telemt_me_writer_teardown_success_total{mode="normal"} 16417
telemt_me_writer_teardown_noop_total 16051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32468
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.242082
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32468
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 206
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 330
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 2600352
telemt_user_connections_current{user="hello"} 4469
telemt_user_octets_from_client{user="hello"} 35958632184 (33.49 GB)
telemt_user_octets_to_client{user="hello"} 863645012452 (804.33 GB)
telemt_user_unique_ips_current{user="hello"} 1711
telemt_user_unique_ips_recent_window{user="hello"} 772
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 50499.9 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2790520
telemt_connections_bad_total 317997
telemt_connections_current 4370
telemt_connections_me_current 4370
telemt_handshake_timeouts_total 103445
telemt_upstream_connect_attempt_total 19419
telemt_upstream_connect_success_total 19406
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 19407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 631
telemt_me_reconnect_success_total 360
telemt_me_reader_eof_total 374
telemt_me_idle_close_by_peer_total 374
telemt_me_route_drop_no_conn_total 1153190
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2198488
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 390
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
telemt_me_writers_warm_current 10
telemt_desync_total 9574
telemt_desync_full_logged_total 3295
telemt_desync_suppressed_total 6279
telemt_desync_frames_bucket_total{bucket="1_2"} 1989
telemt_desync_frames_bucket_total{bucket="3_10"} 3800
telemt_desync_frames_bucket_total{bucket="gt_10"} 3785
telemt_pool_swap_total 54
telemt_pool_force_close_total 1652
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 222
telemt_me_draining_writers_reap_progress_total 17679
telemt_me_writer_removed_unexpected_total 353
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1436
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16454
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1565
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16027
telemt_me_writer_teardown_success_total{mode="normal"} 17890
telemt_me_writer_teardown_noop_total 17691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35581
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.864502
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35581
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 222
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 323
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 2195233
telemt_user_connections_current{user="hello"} 4370
telemt_user_octets_from_client{user="hello"} 35800889780 (33.34 GB)
telemt_user_octets_to_client{user="hello"} 822777913232 (766.27 GB)
telemt_user_unique_ips_current{user="hello"} 1682
telemt_user_unique_ips_recent_window{user="hello"} 611
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 50501.1 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2306047
telemt_connections_bad_total 258984
telemt_connections_current 3481
telemt_connections_me_current 3481
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 97545
telemt_upstream_connect_attempt_total 24468
telemt_upstream_connect_success_total 24216
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 24345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1037
telemt_me_reconnect_success_total 464
telemt_me_reader_eof_total 430
telemt_me_idle_close_by_peer_total 430
telemt_me_route_drop_no_conn_total 675685
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1617072
telemt_me_endpoint_quarantine_total 344
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 391
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 35
telemt_desync_total 7481
telemt_desync_full_logged_total 2563
telemt_desync_suppressed_total 4918
telemt_desync_frames_bucket_total{bucket="1_2"} 1867
telemt_desync_frames_bucket_total{bucket="3_10"} 2936
telemt_desync_frames_bucket_total{bucket="gt_10"} 2678
telemt_pool_swap_total 54
telemt_pool_force_close_total 1480
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 17536
telemt_me_writer_removed_unexpected_total 424
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1432
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16542
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1393
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16056
telemt_me_writer_teardown_success_total{mode="normal"} 17974
telemt_me_writer_teardown_noop_total 17537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35511
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.026347
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35511
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 389
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1618872
telemt_user_connections_current{user="hello"} 3481
telemt_user_octets_from_client{user="hello"} 31854209909 (29.67 GB)
telemt_user_octets_to_client{user="hello"} 777095301951 (723.73 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1423
telemt_user_unique_ips_recent_window{user="hello"} 475
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 50465.0 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2250316
telemt_connections_bad_total 250901
telemt_connections_current 3138
telemt_connections_me_current 3138
telemt_handshake_timeouts_total 68337
telemt_upstream_connect_attempt_total 20780
telemt_upstream_connect_success_total 20729
telemt_upstream_connect_attempts_per_request{bucket="1"} 20729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 719
telemt_me_reconnect_success_total 470
telemt_me_reader_eof_total 435
telemt_me_idle_close_by_peer_total 435
telemt_me_route_drop_no_conn_total 647430
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1616085
telemt_me_endpoint_quarantine_total 378
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 385
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
telemt_me_writers_warm_current 20
telemt_desync_total 7598
telemt_desync_full_logged_total 2596
telemt_desync_suppressed_total 5002
telemt_desync_frames_bucket_total{bucket="1_2"} 2015
telemt_desync_frames_bucket_total{bucket="3_10"} 2898
telemt_desync_frames_bucket_total{bucket="gt_10"} 2685
telemt_pool_swap_total 53
telemt_pool_force_close_total 1457
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 136
telemt_me_draining_writers_reap_progress_total 18622
telemt_me_writer_removed_unexpected_total 410
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1430
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17633
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17165
telemt_me_writer_teardown_success_total{mode="normal"} 19063
telemt_me_writer_teardown_noop_total 18625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37688
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.303515
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37688
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 136
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 420
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1613559
telemt_user_connections_current{user="hello"} 3138
telemt_user_octets_from_client{user="hello"} 37912691320 (35.31 GB)
telemt_user_octets_to_client{user="hello"} 789559169788 (735.33 GB)
telemt_user_unique_ips_current{user="hello"} 1294
telemt_user_unique_ips_recent_window{user="hello"} 496
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 50505.4 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6904838
telemt_connections_bad_total 415436
telemt_connections_current 5552
telemt_connections_me_current 5552
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 253226
telemt_upstream_connect_attempt_total 59893
telemt_upstream_connect_success_total 57251
telemt_upstream_connect_fail_total 1931
telemt_upstream_connect_attempts_per_request{bucket="1"} 59182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1931
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 2936
telemt_me_reconnect_success_total 1012
telemt_me_reader_eof_total 710
telemt_me_idle_close_by_peer_total 709
telemt_me_route_drop_no_conn_total 11652665
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5792867
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 117
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 117
telemt_me_single_endpoint_shadow_rotate_total 398
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 25
telemt_desync_total 11317
telemt_desync_full_logged_total 3626
telemt_desync_suppressed_total 7691
telemt_desync_frames_bucket_total{bucket="1_2"} 2493
telemt_desync_frames_bucket_total{bucket="3_10"} 4935
telemt_desync_frames_bucket_total{bucket="gt_10"} 3889
telemt_pool_swap_total 51
telemt_pool_force_close_total 1607
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 320
telemt_me_draining_writers_reap_progress_total 16897
telemt_me_writer_removed_unexpected_total 974
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2141
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15641
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 220
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15290
telemt_me_writer_teardown_success_total{mode="normal"} 17782
telemt_me_writer_teardown_noop_total 16906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34688
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.183903
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34688
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 320
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 702
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 5827230
telemt_user_connections_current{user="hello"} 5553
telemt_user_octets_from_client{user="hello"} 51354303784 (47.83 GB)
telemt_user_octets_to_client{user="hello"} 608250008547 (566.48 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1877
telemt_user_unique_ips_recent_window{user="hello"} 1179
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 50471.8 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2251576
telemt_connections_bad_total 271729
telemt_connections_current 3481
telemt_connections_me_current 3481
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 45170
telemt_upstream_connect_attempt_total 22223
telemt_upstream_connect_success_total 21993
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 22201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_reconnect_attempts_total 2107
telemt_me_reconnect_success_total 696
telemt_me_reader_eof_total 706
telemt_me_idle_close_by_peer_total 706
telemt_me_route_drop_no_conn_total 771743
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1704668
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 387
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
telemt_me_writers_warm_current 20
telemt_desync_total 7832
telemt_desync_full_logged_total 2844
telemt_desync_suppressed_total 4988
telemt_desync_frames_bucket_total{bucket="1_2"} 1477
telemt_desync_frames_bucket_total{bucket="3_10"} 3184
telemt_desync_frames_bucket_total{bucket="gt_10"} 3171
telemt_pool_swap_total 51
telemt_pool_force_close_total 1391
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 18440
telemt_me_writer_removed_unexpected_total 683
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1704
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17442
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1250
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17049
telemt_me_writer_teardown_success_total{mode="normal"} 19146
telemt_me_writer_teardown_noop_total 18440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37586
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.705868
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37586
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 594
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 1691127
telemt_user_connections_current{user="hello"} 3481
telemt_user_octets_from_client{user="hello"} 30700910536 (28.59 GB)
telemt_user_octets_to_client{user="hello"} 773351952006 (720.24 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1447
telemt_user_unique_ips_recent_window{user="hello"} 532
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 50466.3 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3269468
telemt_connections_bad_total 177293
telemt_connections_current 3231
telemt_connections_me_current 3231
telemt_handshake_timeouts_total 1375345
telemt_upstream_connect_attempt_total 20680
telemt_upstream_connect_success_total 20646
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11097
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 546
telemt_me_reconnect_success_total 309
telemt_me_reader_eof_total 313
telemt_me_idle_close_by_peer_total 313
telemt_me_route_drop_no_conn_total 607515
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1516701
telemt_me_endpoint_quarantine_total 378
telemt_me_single_endpoint_shadow_rotate_total 395
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 23
telemt_desync_total 7445
telemt_desync_full_logged_total 2635
telemt_desync_suppressed_total 4810
telemt_desync_frames_bucket_total{bucket="1_2"} 1326
telemt_desync_frames_bucket_total{bucket="3_10"} 2980
telemt_desync_frames_bucket_total{bucket="gt_10"} 3139
telemt_pool_swap_total 55
telemt_pool_force_close_total 1349
telemt_me_writer_close_signal_drop_total 105
telemt_me_draining_writers_reap_progress_total 18523
telemt_me_writer_removed_unexpected_total 301
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1172
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17673
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1331
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17174
telemt_me_writer_teardown_success_total{mode="normal"} 18845
telemt_me_writer_teardown_noop_total 18523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37368
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.958479
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37368
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 105
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 276
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1512134
telemt_user_connections_current{user="hello"} 3231
telemt_user_octets_from_client{user="hello"} 27158272080 (25.29 GB)
telemt_user_octets_to_client{user="hello"} 739748968644 (688.94 GB)
telemt_user_unique_ips_current{user="hello"} 1328
telemt_user_unique_ips_recent_window{user="hello"} 463
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 48457.8 (13h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672192
telemt_connections_bad_total 22426
telemt_connections_current 625
telemt_connections_me_current 625
telemt_handshake_timeouts_total 251499
telemt_upstream_connect_attempt_total 23501
telemt_upstream_connect_success_total 23499
telemt_upstream_connect_attempts_per_request{bucket="1"} 23499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1037
telemt_me_reconnect_success_total 383
telemt_me_reader_eof_total 384
telemt_me_idle_close_by_peer_total 384
telemt_me_route_drop_no_conn_total 143757
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345232
telemt_me_endpoint_quarantine_total 459
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 414
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
telemt_me_writers_active_current 44
telemt_desync_total 2244
telemt_desync_full_logged_total 890
telemt_desync_suppressed_total 1354
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 830
telemt_desync_frames_bucket_total{bucket="gt_10"} 1030
telemt_pool_swap_total 53
telemt_pool_force_close_total 1162
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 21009
telemt_me_writer_removed_unexpected_total 365
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1528
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19850
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19847
telemt_me_writer_teardown_success_total{mode="normal"} 21378
telemt_me_writer_teardown_noop_total 21009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42387
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.266792
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42387
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 313
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 345358
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 5094674855 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 132877669365 (123.75 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 50476.3 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2381743
telemt_connections_bad_total 220351
telemt_connections_current 4075
telemt_connections_me_current 4075
telemt_handshake_timeouts_total 57696
telemt_upstream_connect_attempt_total 21493
telemt_upstream_connect_success_total 21399
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 21462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10673
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_reconnect_attempts_total 855
telemt_me_reconnect_success_total 481
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_route_drop_no_conn_total 618584
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1880660
telemt_me_endpoint_quarantine_total 397
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 394
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
telemt_me_writers_warm_current 28
telemt_desync_total 7404
telemt_desync_full_logged_total 2476
telemt_desync_suppressed_total 4928
telemt_desync_frames_bucket_total{bucket="1_2"} 1796
telemt_desync_frames_bucket_total{bucket="3_10"} 2786
telemt_desync_frames_bucket_total{bucket="gt_10"} 2822
telemt_pool_swap_total 55
telemt_pool_force_close_total 1374
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 19305
telemt_me_writer_removed_unexpected_total 440
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1450
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18309
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1350
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17931
telemt_me_writer_teardown_success_total{mode="normal"} 19759
telemt_me_writer_teardown_noop_total 19305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39064
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.097463
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39064
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1874610
telemt_user_connections_current{user="hello"} 4075
telemt_user_octets_from_client{user="hello"} 40776334396 (37.98 GB)
telemt_user_octets_to_client{user="hello"} 881271844436 (820.75 GB)
telemt_user_unique_ips_current{user="hello"} 1568
telemt_user_unique_ips_recent_window{user="hello"} 550
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 50473.0 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2196214
telemt_connections_bad_total 175914
telemt_connections_current 3520
telemt_connections_me_current 3520
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 54104
telemt_upstream_connect_attempt_total 37680
telemt_upstream_connect_success_total 37459
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 37637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12343
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 579
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_reconnect_attempts_total 3073
telemt_me_reconnect_success_total 623
telemt_me_reader_eof_total 550
telemt_me_idle_close_by_peer_total 550
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 619864
telemt_me_route_drop_channel_closed_total 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1769955
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 392
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_warm_current 17
telemt_desync_total 6696
telemt_desync_full_logged_total 2279
telemt_desync_suppressed_total 4417
telemt_desync_frames_bucket_total{bucket="1_2"} 1789
telemt_desync_frames_bucket_total{bucket="3_10"} 2488
telemt_desync_frames_bucket_total{bucket="gt_10"} 2419
telemt_pool_swap_total 54
telemt_pool_force_close_total 1319
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 18517
telemt_me_writer_removed_unexpected_total 559
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1702
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17401
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17198
telemt_me_writer_teardown_success_total{mode="normal"} 19103
telemt_me_writer_teardown_noop_total 18518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37621
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.527893
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37621
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 139
telemt_me_writer_restored_same_endpoint_total 482
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1781173
telemt_user_connections_current{user="hello"} 3520
telemt_user_octets_from_client{user="hello"} 32358959293 (30.14 GB)
telemt_user_octets_to_client{user="hello"} 789682221040 (735.45 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1329
telemt_user_unique_ips_recent_window{user="hello"} 499
```