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

# Server Metrics 2026-03-21 11:54:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 55101.8 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1695761
telemt_connections_bad_total 86431
telemt_connections_current 1568
telemt_connections_me_current 1568
telemt_handshake_timeouts_total 67452
telemt_upstream_connect_attempt_total 21548
telemt_upstream_connect_success_total 21440
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 21510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13753
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 1095
telemt_me_reconnect_success_total 486
telemt_me_reader_eof_total 470
telemt_me_idle_close_by_peer_total 470
telemt_me_route_drop_no_conn_total 1021883
telemt_me_route_drop_channel_closed_total 405
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1309199
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 389
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 437
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
telemt_me_writers_active_current 44
telemt_desync_total 5294
telemt_desync_full_logged_total 1872
telemt_desync_suppressed_total 3422
telemt_desync_frames_bucket_total{bucket="1_2"} 1120
telemt_desync_frames_bucket_total{bucket="3_10"} 2038
telemt_desync_frames_bucket_total{bucket="gt_10"} 2136
telemt_pool_swap_total 60
telemt_pool_force_close_total 1757
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 323
telemt_me_draining_writers_reap_progress_total 19264
telemt_me_writer_removed_unexpected_total 450
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1585
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17988
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1693
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 64
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17507
telemt_me_writer_teardown_success_total{mode="normal"} 19573
telemt_me_writer_teardown_noop_total 19268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38841
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 132.028554
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38841
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 323
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 424
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1308230
telemt_user_connections_current{user="hello"} 1568
telemt_user_octets_from_client{user="hello"} 18858155271 (17.56 GB)
telemt_user_octets_to_client{user="hello"} 358400635687 (333.79 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 538
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 747.5 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41815
telemt_connections_bad_total 3236
telemt_connections_current 2504
telemt_connections_me_current 2504
telemt_handshake_timeouts_total 1350
telemt_upstream_connect_attempt_total 303
telemt_upstream_connect_success_total 296
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 3
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 17187
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34172
telemt_me_endpoint_quarantine_total 6
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
telemt_me_writers_active_current 44
telemt_desync_total 139
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_me_draining_writers_reap_progress_total 199
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 199
telemt_me_writer_teardown_success_total{mode="normal"} 201
telemt_me_writer_teardown_noop_total 199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 400
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.012479
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 400
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 34176
telemt_user_connections_current{user="hello"} 2504
telemt_user_octets_from_client{user="hello"} 443038224 (422.51 MB)
telemt_user_octets_to_client{user="hello"} 9661891112 (9.00 GB)
telemt_user_unique_ips_current{user="hello"} 1305
telemt_user_unique_ips_recent_window{user="hello"} 737
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 55100.2 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3274098
telemt_connections_bad_total 352771
telemt_connections_current 3532
telemt_connections_me_current 3532
telemt_handshake_timeouts_total 120382
telemt_upstream_connect_attempt_total 20899
telemt_upstream_connect_success_total 20886
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 728
telemt_me_reconnect_success_total 389
telemt_me_reader_eof_total 402
telemt_me_idle_close_by_peer_total 402
telemt_me_route_drop_no_conn_total 1414254
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2609842
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 424
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
telemt_me_writers_active_current 43
telemt_desync_total 11428
telemt_desync_full_logged_total 3851
telemt_desync_suppressed_total 7577
telemt_desync_frames_bucket_total{bucket="1_2"} 2402
telemt_desync_frames_bucket_total{bucket="3_10"} 4451
telemt_desync_frames_bucket_total{bucket="gt_10"} 4575
telemt_pool_swap_total 60
telemt_pool_force_close_total 1857
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 260
telemt_me_draining_writers_reap_progress_total 19044
telemt_me_writer_removed_unexpected_total 379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1567
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17696
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 14
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1757
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 100
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17187
telemt_me_writer_teardown_success_total{mode="normal"} 19263
telemt_me_writer_teardown_noop_total 19058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38321
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.075001
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38321
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 260
telemt_me_refill_failed_total 17
telemt_me_writer_restored_same_endpoint_total 345
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2606191
telemt_user_connections_current{user="hello"} 3532
telemt_user_octets_from_client{user="hello"} 43066544504 (40.11 GB)
telemt_user_octets_to_client{user="hello"} 946900429576 (881.87 GB)
telemt_user_unique_ips_current{user="hello"} 1271
telemt_user_unique_ips_recent_window{user="hello"} 1154
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 55101.5 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2719554
telemt_connections_bad_total 303879
telemt_connections_current 2899
telemt_connections_me_current 2899
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 111926
telemt_upstream_connect_attempt_total 25808
telemt_upstream_connect_success_total 25544
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 25675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 1075
telemt_me_reconnect_success_total 503
telemt_me_reader_eof_total 465
telemt_me_idle_close_by_peer_total 465
telemt_me_route_drop_no_conn_total 801739
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1919192
telemt_me_endpoint_quarantine_total 371
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 426
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
telemt_me_writers_active_current 42
telemt_desync_total 8803
telemt_desync_full_logged_total 3014
telemt_desync_suppressed_total 5789
telemt_desync_frames_bucket_total{bucket="1_2"} 2203
telemt_desync_frames_bucket_total{bucket="3_10"} 3436
telemt_desync_frames_bucket_total{bucket="gt_10"} 3164
telemt_pool_swap_total 60
telemt_pool_force_close_total 1672
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 18739
telemt_me_writer_removed_unexpected_total 455
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1575
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17637
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1561
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 111
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17067
telemt_me_writer_teardown_success_total{mode="normal"} 19212
telemt_me_writer_teardown_noop_total 18740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37952
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.859372
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37952
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 422
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1920573
telemt_user_connections_current{user="hello"} 2899
telemt_user_octets_from_client{user="hello"} 36593008757 (34.08 GB)
telemt_user_octets_to_client{user="hello"} 922044875339 (858.72 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1076
telemt_user_unique_ips_recent_window{user="hello"} 995
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 55064.7 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2650675
telemt_connections_bad_total 297599
telemt_connections_current 3952
telemt_connections_me_current 3952
telemt_handshake_timeouts_total 79058
telemt_upstream_connect_attempt_total 22250
telemt_upstream_connect_success_total 22174
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12065
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 813
telemt_me_reconnect_success_total 558
telemt_me_reader_eof_total 498
telemt_me_idle_close_by_peer_total 498
telemt_me_route_drop_no_conn_total 781908
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1915661
telemt_me_endpoint_quarantine_total 416
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 417
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
telemt_me_writers_active_current 63
telemt_me_writers_warm_current 22
telemt_desync_total 8974
telemt_desync_full_logged_total 3020
telemt_desync_suppressed_total 5954
telemt_desync_frames_bucket_total{bucket="1_2"} 2382
telemt_desync_frames_bucket_total{bucket="3_10"} 3410
telemt_desync_frames_bucket_total{bucket="gt_10"} 3182
telemt_pool_swap_total 58
telemt_pool_force_close_total 1617
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 19847
telemt_me_writer_removed_unexpected_total 477
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1610
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18747
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1496
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18230
telemt_me_writer_teardown_success_total{mode="normal"} 20357
telemt_me_writer_teardown_noop_total 19850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40207
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.988220
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40207
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 484
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1912773
telemt_user_connections_current{user="hello"} 3952
telemt_user_octets_from_client{user="hello"} 43305157876 (40.33 GB)
telemt_user_octets_to_client{user="hello"} 928252318520 (864.50 GB)
telemt_user_unique_ips_current{user="hello"} 1495
telemt_user_unique_ips_recent_window{user="hello"} 750
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 55104.3 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8567149
telemt_connections_bad_total 574177
telemt_connections_current 5147
telemt_connections_me_current 5147
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 298407
telemt_upstream_connect_attempt_total 64191
telemt_upstream_connect_success_total 60470
telemt_upstream_connect_fail_total 2946
telemt_upstream_connect_attempts_per_request{bucket="1"} 63416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2946
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3203
telemt_me_reconnect_success_total 1098
telemt_me_reader_eof_total 797
telemt_me_idle_close_by_peer_total 796
telemt_me_route_drop_no_conn_total 15280767
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7127072
telemt_me_endpoint_quarantine_total 431
telemt_me_single_endpoint_outage_enter_total 58
telemt_me_single_endpoint_outage_exit_total 58
telemt_me_single_endpoint_outage_reconnect_attempt_total 121
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 121
telemt_me_single_endpoint_shadow_rotate_total 434
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
telemt_me_writers_active_current 44
telemt_desync_total 13499
telemt_desync_full_logged_total 4349
telemt_desync_suppressed_total 9150
telemt_desync_frames_bucket_total{bucket="1_2"} 2907
telemt_desync_frames_bucket_total{bucket="3_10"} 5968
telemt_desync_frames_bucket_total{bucket="gt_10"} 4624
telemt_pool_swap_total 56
telemt_pool_force_close_total 1755
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 18296
telemt_me_writer_removed_unexpected_total 1063
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2335
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16920
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1503
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 252
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16541
telemt_me_writer_teardown_success_total{mode="normal"} 19255
telemt_me_writer_teardown_noop_total 18305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37560
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.893315
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37560
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 774
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 7162637
telemt_user_connections_current{user="hello"} 5147
telemt_user_octets_from_client{user="hello"} 57949273908 (53.97 GB)
telemt_user_octets_to_client{user="hello"} 659742678407 (614.43 GB)
telemt_user_msgs_from_client{user="hello"} 129175
telemt_user_msgs_to_client{user="hello"} 449473
telemt_user_unique_ips_current{user="hello"} 1776
telemt_user_unique_ips_recent_window{user="hello"} 1724
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 55072.0 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2685055
telemt_connections_bad_total 332153
telemt_connections_current 3475
telemt_connections_me_current 3475
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 59366
telemt_upstream_connect_attempt_total 23741
telemt_upstream_connect_success_total 23478
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 23716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_reconnect_attempts_total 2342
telemt_me_reconnect_success_total 769
telemt_me_reader_eof_total 764
telemt_me_idle_close_by_peer_total 764
telemt_me_route_drop_no_conn_total 932946
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2027350
telemt_me_endpoint_quarantine_total 348
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 424
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
telemt_desync_total 9285
telemt_desync_full_logged_total 3320
telemt_desync_suppressed_total 5965
telemt_desync_frames_bucket_total{bucket="1_2"} 1827
telemt_desync_frames_bucket_total{bucket="3_10"} 3723
telemt_desync_frames_bucket_total{bucket="gt_10"} 3735
telemt_pool_swap_total 57
telemt_pool_force_close_total 1548
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 136
telemt_me_draining_writers_reap_progress_total 19739
telemt_me_writer_removed_unexpected_total 738
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1853
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18650
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1391
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18191
telemt_me_writer_teardown_success_total{mode="normal"} 20503
telemt_me_writer_teardown_noop_total 19739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40242
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.206276
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40242
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 136
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 645
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 2012516
telemt_user_connections_current{user="hello"} 3475
telemt_user_octets_from_client{user="hello"} 37002076384 (34.46 GB)
telemt_user_octets_to_client{user="hello"} 896432506758 (834.87 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1271
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 55066.1 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3955124
telemt_connections_bad_total 204523
telemt_connections_current 3555
telemt_connections_me_current 3555
telemt_handshake_timeouts_total 1711749
telemt_upstream_connect_attempt_total 22249
telemt_upstream_connect_success_total 22215
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 22218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 802
telemt_me_reconnect_success_total 399
telemt_me_reader_eof_total 398
telemt_me_idle_close_by_peer_total 398
telemt_me_route_drop_no_conn_total 772484
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1795424
telemt_me_endpoint_quarantine_total 422
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 433
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
telemt_me_writers_active_current 44
telemt_desync_total 8799
telemt_desync_full_logged_total 3134
telemt_desync_suppressed_total 5665
telemt_desync_frames_bucket_total{bucket="1_2"} 1616
telemt_desync_frames_bucket_total{bucket="3_10"} 3517
telemt_desync_frames_bucket_total{bucket="gt_10"} 3666
telemt_pool_swap_total 60
telemt_pool_force_close_total 1494
telemt_me_writer_close_signal_drop_total 124
telemt_me_draining_writers_reap_progress_total 19888
telemt_me_writer_removed_unexpected_total 386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1340
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18955
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1442
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18394
telemt_me_writer_teardown_success_total{mode="normal"} 20295
telemt_me_writer_teardown_noop_total 19888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40183
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.097793
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40183
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 124
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 1789217
telemt_user_connections_current{user="hello"} 3555
telemt_user_octets_from_client{user="hello"} 32789940368 (30.54 GB)
telemt_user_octets_to_client{user="hello"} 864154461652 (804.81 GB)
telemt_user_unique_ips_current{user="hello"} 1539
telemt_user_unique_ips_recent_window{user="hello"} 476
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 53057.4 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 832035
telemt_connections_bad_total 59772
telemt_connections_current 713
telemt_connections_me_current 713
telemt_handshake_timeouts_total 302796
telemt_upstream_connect_attempt_total 25427
telemt_upstream_connect_success_total 25425
telemt_upstream_connect_attempts_per_request{bucket="1"} 25425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1087
telemt_me_reconnect_success_total 420
telemt_me_reader_eof_total 415
telemt_me_idle_close_by_peer_total 415
telemt_me_route_drop_no_conn_total 177728
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 406298
telemt_me_endpoint_quarantine_total 488
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 450
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
telemt_me_writers_active_current 45
telemt_desync_total 2815
telemt_desync_full_logged_total 1075
telemt_desync_suppressed_total 1740
telemt_desync_frames_bucket_total{bucket="1_2"} 452
telemt_desync_frames_bucket_total{bucket="3_10"} 1017
telemt_desync_frames_bucket_total{bucket="gt_10"} 1346
telemt_pool_swap_total 58
telemt_pool_force_close_total 1291
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 22774
telemt_me_writer_removed_unexpected_total 395
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1656
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21518
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1288
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21483
telemt_me_writer_teardown_success_total{mode="normal"} 23174
telemt_me_writer_teardown_noop_total 22774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45948
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.622908
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45948
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 340
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 406168
telemt_user_connections_current{user="hello"} 713
telemt_user_octets_from_client{user="hello"} 6507185183 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 156589756945 (145.84 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 55076.4 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2835969
telemt_connections_bad_total 264669
telemt_connections_current 4090
telemt_connections_me_current 4090
telemt_handshake_timeouts_total 77277
telemt_upstream_connect_attempt_total 23089
telemt_upstream_connect_success_total 22991
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 23058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11506
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 952
telemt_me_reconnect_success_total 530
telemt_me_reader_eof_total 493
telemt_me_idle_close_by_peer_total 493
telemt_me_route_drop_no_conn_total 755738
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2245210
telemt_me_endpoint_quarantine_total 429
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 431
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
telemt_desync_total 9020
telemt_desync_full_logged_total 2977
telemt_desync_suppressed_total 6043
telemt_desync_frames_bucket_total{bucket="1_2"} 2158
telemt_desync_frames_bucket_total{bucket="3_10"} 3361
telemt_desync_frames_bucket_total{bucket="gt_10"} 3501
telemt_pool_swap_total 61
telemt_pool_force_close_total 1506
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 20714
telemt_me_writer_removed_unexpected_total 485
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1599
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19616
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1479
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19208
telemt_me_writer_teardown_success_total{mode="normal"} 21215
telemt_me_writer_teardown_noop_total 20714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41929
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.511753
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41929
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 472
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 2238616
telemt_user_connections_current{user="hello"} 4090
telemt_user_octets_from_client{user="hello"} 46999699684 (43.77 GB)
telemt_user_octets_to_client{user="hello"} 1046315246932 (974.46 GB)
telemt_user_unique_ips_current{user="hello"} 1520
telemt_user_unique_ips_recent_window{user="hello"} 538
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 55073.1 (15h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2593183
telemt_connections_bad_total 204016
telemt_connections_current 3593
telemt_connections_me_current 3593
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 70446
telemt_upstream_connect_attempt_total 39232
telemt_upstream_connect_success_total 38986
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 39189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_reconnect_attempts_total 3253
telemt_me_reconnect_success_total 678
telemt_me_reader_eof_total 592
telemt_me_idle_close_by_peer_total 592
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 761754
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2087049
telemt_me_endpoint_quarantine_total 480
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 427
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
telemt_desync_total 7912
telemt_desync_full_logged_total 2709
telemt_desync_suppressed_total 5203
telemt_desync_frames_bucket_total{bucket="1_2"} 2068
telemt_desync_frames_bucket_total{bucket="3_10"} 2942
telemt_desync_frames_bucket_total{bucket="gt_10"} 2902
telemt_pool_swap_total 60
telemt_pool_force_close_total 1461
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 19879
telemt_me_writer_removed_unexpected_total 604
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1861
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18650
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1369
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18418
telemt_me_writer_teardown_success_total{mode="normal"} 20511
telemt_me_writer_teardown_noop_total 19880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40391
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.311320
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40391
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 514
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 2097793
telemt_user_connections_current{user="hello"} 3593
telemt_user_octets_from_client{user="hello"} 38160940489 (35.54 GB)
telemt_user_octets_to_client{user="hello"} 924593507876 (861.09 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1436
telemt_user_unique_ips_recent_window{user="hello"} 529
```