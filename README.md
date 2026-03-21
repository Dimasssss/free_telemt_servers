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

# Server Metrics 2026-03-21 10:52:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 51416.0 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1516987
telemt_connections_bad_total 77116
telemt_connections_current 1586
telemt_connections_me_current 1586
telemt_handshake_timeouts_total 60710
telemt_upstream_connect_attempt_total 20187
telemt_upstream_connect_success_total 20096
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 20163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12845
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 977
telemt_me_reconnect_success_total 421
telemt_me_reader_eof_total 420
telemt_me_idle_close_by_peer_total 420
telemt_me_route_drop_no_conn_total 877607
telemt_me_route_drop_channel_closed_total 327
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1161359
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 359
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 407
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
telemt_me_writers_active_current 42
telemt_desync_total 4803
telemt_desync_full_logged_total 1677
telemt_desync_suppressed_total 3126
telemt_desync_frames_bucket_total{bucket="1_2"} 996
telemt_desync_frames_bucket_total{bucket="3_10"} 1867
telemt_desync_frames_bucket_total{bucket="gt_10"} 1940
telemt_pool_swap_total 56
telemt_pool_force_close_total 1577
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 273
telemt_me_draining_writers_reap_progress_total 18041
telemt_me_writer_removed_unexpected_total 398
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1455
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16880
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1516
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16464
telemt_me_writer_teardown_success_total{mode="normal"} 18335
telemt_me_writer_teardown_noop_total 18043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36378
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.903495
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36378
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 273
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 371
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1160436
telemt_user_connections_current{user="hello"} 1586
telemt_user_octets_from_client{user="hello"} 16179101671 (15.07 GB)
telemt_user_octets_to_client{user="hello"} 324837852975 (302.53 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 587
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 51417.6 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3891663
telemt_connections_bad_total 387171
telemt_connections_current 4751
telemt_connections_me_current 4751
telemt_handshake_timeouts_total 113140
telemt_upstream_connect_attempt_total 18271
telemt_upstream_connect_success_total 18185
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 18244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 1131
telemt_me_reconnect_success_total 422
telemt_me_reader_eof_total 417
telemt_me_idle_close_by_peer_total 416
telemt_me_route_drop_no_conn_total 1831351
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2698359
telemt_me_endpoint_quarantine_total 326
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 393
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
telemt_me_writers_active_current 41
telemt_desync_total 11498
telemt_desync_full_logged_total 3844
telemt_desync_suppressed_total 7654
telemt_desync_frames_bucket_total{bucket="1_2"} 2353
telemt_desync_frames_bucket_total{bucket="3_10"} 4545
telemt_desync_frames_bucket_total{bucket="gt_10"} 4600
telemt_pool_swap_total 56
telemt_pool_force_close_total 1690
telemt_me_writer_close_signal_drop_total 212
telemt_me_draining_writers_reap_progress_total 16310
telemt_me_writer_removed_unexpected_total 390
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1529
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15158
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1587
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 103
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14620
telemt_me_writer_teardown_success_total{mode="normal"} 16687
telemt_me_writer_teardown_noop_total 16310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32997
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.943968
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32997
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 212
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 339
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 2693584
telemt_user_connections_current{user="hello"} 4751
telemt_user_octets_from_client{user="hello"} 37082233900 (34.54 GB)
telemt_user_octets_to_client{user="hello"} 887960205188 (826.98 GB)
telemt_user_unique_ips_current{user="hello"} 1809
telemt_user_unique_ips_recent_window{user="hello"} 707
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 51413.9 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2877102
telemt_connections_bad_total 324835
telemt_connections_current 4080
telemt_connections_me_current 4080
telemt_handshake_timeouts_total 105436
telemt_upstream_connect_attempt_total 19728
telemt_upstream_connect_success_total 19715
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 19716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 650
telemt_me_reconnect_success_total 364
telemt_me_reader_eof_total 380
telemt_me_idle_close_by_peer_total 380
telemt_me_route_drop_no_conn_total 1185637
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2272856
telemt_me_endpoint_quarantine_total 336
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 398
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
telemt_desync_total 9806
telemt_desync_full_logged_total 3373
telemt_desync_suppressed_total 6433
telemt_desync_frames_bucket_total{bucket="1_2"} 2026
telemt_desync_frames_bucket_total{bucket="3_10"} 3881
telemt_desync_frames_bucket_total{bucket="gt_10"} 3899
telemt_pool_swap_total 56
telemt_pool_force_close_total 1683
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 233
telemt_me_draining_writers_reap_progress_total 17947
telemt_me_writer_removed_unexpected_total 357
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1471
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16693
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1591
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16264
telemt_me_writer_teardown_success_total{mode="normal"} 18164
telemt_me_writer_teardown_noop_total 17960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36124
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.407235
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36124
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 233
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 326
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 2269569
telemt_user_connections_current{user="hello"} 4080
telemt_user_octets_from_client{user="hello"} 36825524600 (34.30 GB)
telemt_user_octets_to_client{user="hello"} 850731201976 (792.31 GB)
telemt_user_unique_ips_current{user="hello"} 1544
telemt_user_unique_ips_recent_window{user="hello"} 604
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 51415.2 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2387571
telemt_connections_bad_total 267364
telemt_connections_current 3357
telemt_connections_me_current 3357
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 100219
telemt_upstream_connect_attempt_total 24748
telemt_upstream_connect_success_total 24495
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 24625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1045
telemt_me_reconnect_success_total 472
telemt_me_reader_eof_total 436
telemt_me_idle_close_by_peer_total 436
telemt_me_route_drop_no_conn_total 699111
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1678049
telemt_me_endpoint_quarantine_total 353
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 398
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
telemt_desync_total 7710
telemt_desync_full_logged_total 2635
telemt_desync_suppressed_total 5075
telemt_desync_frames_bucket_total{bucket="1_2"} 1931
telemt_desync_frames_bucket_total{bucket="3_10"} 3025
telemt_desync_frames_bucket_total{bucket="gt_10"} 2754
telemt_pool_swap_total 56
telemt_pool_force_close_total 1517
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 108
telemt_me_draining_writers_reap_progress_total 17794
telemt_me_writer_removed_unexpected_total 430
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1463
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16775
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1423
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 94
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16277
telemt_me_writer_teardown_success_total{mode="normal"} 18238
telemt_me_writer_teardown_noop_total 17795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36033
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.950980
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36033
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 108
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 395
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1679758
telemt_user_connections_current{user="hello"} 3357
telemt_user_octets_from_client{user="hello"} 32560302621 (30.32 GB)
telemt_user_octets_to_client{user="hello"} 807428779543 (751.98 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1255
telemt_user_unique_ips_recent_window{user="hello"} 777
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 51379.1 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2330435
telemt_connections_bad_total 261130
telemt_connections_current 3283
telemt_connections_me_current 3283
telemt_handshake_timeouts_total 69893
telemt_upstream_connect_attempt_total 21060
telemt_upstream_connect_success_total 21007
telemt_upstream_connect_attempts_per_request{bucket="1"} 21007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 746
telemt_me_reconnect_success_total 502
telemt_me_reader_eof_total 452
telemt_me_idle_close_by_peer_total 452
telemt_me_route_drop_no_conn_total 671623
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1671919
telemt_me_endpoint_quarantine_total 393
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 392
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
telemt_me_writers_warm_current 16
telemt_desync_total 7890
telemt_desync_full_logged_total 2687
telemt_desync_suppressed_total 5203
telemt_desync_frames_bucket_total{bucket="1_2"} 2098
telemt_desync_frames_bucket_total{bucket="3_10"} 2995
telemt_desync_frames_bucket_total{bucket="gt_10"} 2797
telemt_pool_swap_total 54
telemt_pool_force_close_total 1489
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 138
telemt_me_draining_writers_reap_progress_total 18861
telemt_me_writer_removed_unexpected_total 428
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1465
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17855
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1376
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 113
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17372
telemt_me_writer_teardown_success_total{mode="normal"} 19320
telemt_me_writer_teardown_noop_total 18864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38184
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.729841
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38184
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 138
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 438
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1669350
telemt_user_connections_current{user="hello"} 3283
telemt_user_octets_from_client{user="hello"} 39001957136 (36.32 GB)
telemt_user_octets_to_client{user="hello"} 815252915248 (759.26 GB)
telemt_user_unique_ips_current{user="hello"} 1301
telemt_user_unique_ips_recent_window{user="hello"} 534
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 51418.5 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7245207
telemt_connections_bad_total 488752
telemt_connections_current 5125
telemt_connections_me_current 5125
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 261778
telemt_upstream_connect_attempt_total 60362
telemt_upstream_connect_success_total 57681
telemt_upstream_connect_fail_total 1953
telemt_upstream_connect_attempts_per_request{bucket="1"} 59634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2059
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1953
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 2989
telemt_me_reconnect_success_total 1056
telemt_me_reader_eof_total 761
telemt_me_idle_close_by_peer_total 760
telemt_me_route_drop_no_conn_total 12234084
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6032750
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 117
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 117
telemt_me_single_endpoint_shadow_rotate_total 404
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
telemt_me_writers_active_current 83
telemt_me_writers_warm_current 36
telemt_desync_total 11706
telemt_desync_full_logged_total 3741
telemt_desync_suppressed_total 7965
telemt_desync_frames_bucket_total{bucket="1_2"} 2566
telemt_desync_frames_bucket_total{bucket="3_10"} 5127
telemt_desync_frames_bucket_total{bucket="gt_10"} 4013
telemt_pool_swap_total 51
telemt_pool_force_close_total 1607
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 321
telemt_me_draining_writers_reap_progress_total 17203
telemt_me_writer_removed_unexpected_total 1026
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2200
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15940
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 220
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15596
telemt_me_writer_teardown_success_total{mode="normal"} 18140
telemt_me_writer_teardown_noop_total 17212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35352
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.260637
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35352
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 321
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 746
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 6067112
telemt_user_connections_current{user="hello"} 5125
telemt_user_octets_from_client{user="hello"} 52604144740 (48.99 GB)
telemt_user_octets_to_client{user="hello"} 618625263543 (576.14 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1844
telemt_user_unique_ips_recent_window{user="hello"} 872
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 51386.0 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2328941
telemt_connections_bad_total 278229
telemt_connections_current 3637
telemt_connections_me_current 3637
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 48029
telemt_upstream_connect_attempt_total 22528
telemt_upstream_connect_success_total 22298
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 22506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_reconnect_attempts_total 2115
telemt_me_reconnect_success_total 704
telemt_me_reader_eof_total 713
telemt_me_idle_close_by_peer_total 713
telemt_me_route_drop_no_conn_total 798058
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1764637
telemt_me_endpoint_quarantine_total 314
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 394
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 24
telemt_desync_total 8136
telemt_desync_full_logged_total 2951
telemt_desync_suppressed_total 5185
telemt_desync_frames_bucket_total{bucket="1_2"} 1552
telemt_desync_frames_bucket_total{bucket="3_10"} 3290
telemt_desync_frames_bucket_total{bucket="gt_10"} 3294
telemt_pool_swap_total 52
telemt_pool_force_close_total 1420
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 118
telemt_me_draining_writers_reap_progress_total 18706
telemt_me_writer_removed_unexpected_total 690
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1727
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17692
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1276
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 144
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17286
telemt_me_writer_teardown_success_total{mode="normal"} 19419
telemt_me_writer_teardown_noop_total 18706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38125
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.775670
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38125
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 118
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 601
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 1750642
telemt_user_connections_current{user="hello"} 3637
telemt_user_octets_from_client{user="hello"} 32311544360 (30.09 GB)
telemt_user_octets_to_client{user="hello"} 796445545666 (741.75 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1427
telemt_user_unique_ips_recent_window{user="hello"} 523
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 51380.8 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3405095
telemt_connections_bad_total 182095
telemt_connections_current 3335
telemt_connections_me_current 3335
telemt_handshake_timeouts_total 1444161
telemt_upstream_connect_attempt_total 20896
telemt_upstream_connect_success_total 20862
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 284
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 615
telemt_me_reconnect_success_total 312
telemt_me_reader_eof_total 319
telemt_me_idle_close_by_peer_total 319
telemt_me_route_drop_no_conn_total 629939
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1571879
telemt_me_endpoint_quarantine_total 384
telemt_me_single_endpoint_shadow_rotate_total 403
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
telemt_me_writers_active_current 42
telemt_me_writers_warm_current 31
telemt_desync_total 7706
telemt_desync_full_logged_total 2750
telemt_desync_suppressed_total 4956
telemt_desync_frames_bucket_total{bucket="1_2"} 1391
telemt_desync_frames_bucket_total{bucket="3_10"} 3078
telemt_desync_frames_bucket_total{bucket="gt_10"} 3237
telemt_pool_swap_total 56
telemt_pool_force_close_total 1379
telemt_me_writer_close_signal_drop_total 106
telemt_me_draining_writers_reap_progress_total 18712
telemt_me_writer_removed_unexpected_total 307
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1189
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17851
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1361
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17333
telemt_me_writer_teardown_success_total{mode="normal"} 19040
telemt_me_writer_teardown_noop_total 18712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37752
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.016666
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37752
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 106
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 278
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1567295
telemt_user_connections_current{user="hello"} 3335
telemt_user_octets_from_client{user="hello"} 28079825164 (26.15 GB)
telemt_user_octets_to_client{user="hello"} 764119130560 (711.64 GB)
telemt_user_unique_ips_current{user="hello"} 1397
telemt_user_unique_ips_recent_window{user="hello"} 476
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 49371.8 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 694648
telemt_connections_bad_total 22690
telemt_connections_current 690
telemt_connections_me_current 690
telemt_handshake_timeouts_total 259370
telemt_upstream_connect_attempt_total 23884
telemt_upstream_connect_success_total 23882
telemt_upstream_connect_attempts_per_request{bucket="1"} 23882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1039
telemt_me_reconnect_success_total 386
telemt_me_reader_eof_total 386
telemt_me_idle_close_by_peer_total 386
telemt_me_route_drop_no_conn_total 149113
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356311
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 422
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
telemt_me_writers_active_current 46
telemt_desync_total 2338
telemt_desync_full_logged_total 917
telemt_desync_suppressed_total 1421
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 856
telemt_desync_frames_bucket_total{bucket="gt_10"} 1094
telemt_pool_swap_total 54
telemt_pool_force_close_total 1188
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 21365
telemt_me_writer_removed_unexpected_total 367
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1551
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20185
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1185
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20177
telemt_me_writer_teardown_success_total{mode="normal"} 21736
telemt_me_writer_teardown_noop_total 21365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43101
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.314203
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43101
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 356431
telemt_user_connections_current{user="hello"} 690
telemt_user_octets_from_client{user="hello"} 5314091519 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 137618623201 (128.17 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 51390.3 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2471113
telemt_connections_bad_total 230048
telemt_connections_current 4009
telemt_connections_me_current 4009
telemt_handshake_timeouts_total 59895
telemt_upstream_connect_attempt_total 21837
telemt_upstream_connect_success_total 21743
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 21807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 859
telemt_me_reconnect_success_total 484
telemt_me_reader_eof_total 449
telemt_me_idle_close_by_peer_total 449
telemt_me_route_drop_no_conn_total 647144
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1950726
telemt_me_endpoint_quarantine_total 403
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 401
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
telemt_me_writers_warm_current 38
telemt_desync_total 7677
telemt_desync_full_logged_total 2580
telemt_desync_suppressed_total 5097
telemt_desync_frames_bucket_total{bucket="1_2"} 1849
telemt_desync_frames_bucket_total{bucket="3_10"} 2886
telemt_desync_frames_bucket_total{bucket="gt_10"} 2942
telemt_pool_swap_total 56
telemt_pool_force_close_total 1401
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 19611
telemt_me_writer_removed_unexpected_total 443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1466
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18602
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1377
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18210
telemt_me_writer_teardown_success_total{mode="normal"} 20068
telemt_me_writer_teardown_noop_total 19611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39679
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.111784
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39679
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 433
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1944640
telemt_user_connections_current{user="hello"} 4009
telemt_user_octets_from_client{user="hello"} 41890897504 (39.01 GB)
telemt_user_octets_to_client{user="hello"} 913285807672 (850.56 GB)
telemt_user_unique_ips_current{user="hello"} 1468
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 51387.0 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2265101
telemt_connections_bad_total 180036
telemt_connections_current 3530
telemt_connections_me_current 3530
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 55868
telemt_upstream_connect_attempt_total 38006
telemt_upstream_connect_success_total 37780
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 37962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 580
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_reconnect_attempts_total 3093
telemt_me_reconnect_success_total 628
telemt_me_reader_eof_total 554
telemt_me_idle_close_by_peer_total 554
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 644590
telemt_me_route_drop_channel_closed_total 43
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1829688
telemt_me_endpoint_quarantine_total 443
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 399
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
telemt_me_writers_warm_current 30
telemt_desync_total 6859
telemt_desync_full_logged_total 2340
telemt_desync_suppressed_total 4519
telemt_desync_frames_bucket_total{bucket="1_2"} 1825
telemt_desync_frames_bucket_total{bucket="3_10"} 2541
telemt_desync_frames_bucket_total{bucket="gt_10"} 2493
telemt_pool_swap_total 55
telemt_pool_force_close_total 1350
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 18798
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1725
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17664
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1267
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17448
telemt_me_writer_teardown_success_total{mode="normal"} 19389
telemt_me_writer_teardown_noop_total 18799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38188
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.555301
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38188
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 485
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1840785
telemt_user_connections_current{user="hello"} 3530
telemt_user_octets_from_client{user="hello"} 33538912669 (31.24 GB)
telemt_user_octets_to_client{user="hello"} 816011967872 (759.97 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1417
telemt_user_unique_ips_recent_window{user="hello"} 489
```