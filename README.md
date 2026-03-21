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

# Server Metrics 2026-03-21 08:25:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 42549.0 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1094137
telemt_connections_bad_total 54856
telemt_connections_current 1603
telemt_connections_me_current 1603
telemt_handshake_timeouts_total 47993
telemt_upstream_connect_attempt_total 16949
telemt_upstream_connect_success_total 16873
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 16925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 665
telemt_me_reconnect_success_total 301
telemt_me_reader_eof_total 304
telemt_me_idle_close_by_peer_total 304
telemt_me_route_drop_no_conn_total 466861
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 804550
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_endpoint_quarantine_total 302
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 348
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
telemt_desync_total 3426
telemt_desync_full_logged_total 1209
telemt_desync_suppressed_total 2217
telemt_desync_frames_bucket_total{bucket="1_2"} 711
telemt_desync_frames_bucket_total{bucket="3_10"} 1314
telemt_desync_frames_bucket_total{bucket="gt_10"} 1401
telemt_pool_swap_total 47
telemt_pool_force_close_total 1283
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 169
telemt_me_draining_writers_reap_progress_total 15152
telemt_me_writer_removed_unexpected_total 286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1182
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14186
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1263
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13869
telemt_me_writer_teardown_success_total{mode="normal"} 15368
telemt_me_writer_teardown_noop_total 15153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30521
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 63.652699
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30521
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 169
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 264
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 803868
telemt_user_connections_current{user="hello"} 1603
telemt_user_octets_from_client{user="hello"} 11367253387 (10.59 GB)
telemt_user_octets_to_client{user="hello"} 233262098111 (217.24 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 42550.6 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2654001
telemt_connections_bad_total 298795
telemt_connections_current 4265
telemt_connections_me_current 4265
telemt_handshake_timeouts_total 74925
telemt_upstream_connect_attempt_total 15647
telemt_upstream_connect_success_total 15573
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 15623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 943
telemt_me_reconnect_success_total 353
telemt_me_reader_eof_total 347
telemt_me_idle_close_by_peer_total 346
telemt_me_route_drop_no_conn_total 708260
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1693754
telemt_me_endpoint_quarantine_total 278
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 334
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
telemt_desync_total 7465
telemt_desync_full_logged_total 2549
telemt_desync_suppressed_total 4916
telemt_desync_frames_bucket_total{bucket="1_2"} 1498
telemt_desync_frames_bucket_total{bucket="3_10"} 2932
telemt_desync_frames_bucket_total{bucket="gt_10"} 3035
telemt_pool_swap_total 46
telemt_pool_force_close_total 1384
telemt_me_writer_close_signal_drop_total 154
telemt_me_draining_writers_reap_progress_total 13999
telemt_me_writer_removed_unexpected_total 325
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1280
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13039
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1306
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12615
telemt_me_writer_teardown_success_total{mode="normal"} 14319
telemt_me_writer_teardown_noop_total 13999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28318
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.740650
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28318
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 154
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 282
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1690276
telemt_user_connections_current{user="hello"} 4265
telemt_user_octets_from_client{user="hello"} 24000857032 (22.35 GB)
telemt_user_octets_to_client{user="hello"} 655558950104 (610.54 GB)
telemt_user_unique_ips_current{user="hello"} 1544
telemt_user_unique_ips_recent_window{user="hello"} 595
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 42546.9 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1911622
telemt_connections_bad_total 234639
telemt_connections_current 3974
telemt_connections_me_current 3974
telemt_handshake_timeouts_total 74012
telemt_upstream_connect_attempt_total 16998
telemt_upstream_connect_success_total 16988
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 567
telemt_me_reconnect_success_total 316
telemt_me_reader_eof_total 328
telemt_me_idle_close_by_peer_total 328
telemt_me_route_drop_no_conn_total 606704
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1472716
telemt_me_endpoint_quarantine_total 295
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 339
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
telemt_me_writers_active_current 44
telemt_desync_total 6092
telemt_desync_full_logged_total 2159
telemt_desync_suppressed_total 3933
telemt_desync_frames_bucket_total{bucket="1_2"} 1372
telemt_desync_frames_bucket_total{bucket="3_10"} 2343
telemt_desync_frames_bucket_total{bucket="gt_10"} 2377
telemt_pool_swap_total 46
telemt_pool_force_close_total 1350
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 168
telemt_me_draining_writers_reap_progress_total 15470
telemt_me_writer_removed_unexpected_total 308
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1259
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14422
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1280
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14120
telemt_me_writer_teardown_success_total{mode="normal"} 15681
telemt_me_writer_teardown_noop_total 15479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31160
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.463548
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31160
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 168
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 279
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1470098
telemt_user_connections_current{user="hello"} 3974
telemt_user_octets_from_client{user="hello"} 20643957192 (19.23 GB)
telemt_user_octets_to_client{user="hello"} 608999915820 (567.18 GB)
telemt_user_unique_ips_current{user="hello"} 1426
telemt_user_unique_ips_recent_window{user="hello"} 541
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 42548.2 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1620394
telemt_connections_bad_total 200475
telemt_connections_current 3336
telemt_connections_me_current 3336
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 67255
telemt_upstream_connect_attempt_total 21666
telemt_upstream_connect_success_total 21436
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 21558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 380
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 820
telemt_me_reconnect_success_total 347
telemt_me_reader_eof_total 323
telemt_me_idle_close_by_peer_total 323
telemt_me_route_drop_no_conn_total 454597
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1107408
telemt_me_endpoint_quarantine_total 307
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 342
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
telemt_me_writers_active_current 45
telemt_desync_total 5175
telemt_desync_full_logged_total 1804
telemt_desync_suppressed_total 3371
telemt_desync_frames_bucket_total{bucket="1_2"} 1243
telemt_desync_frames_bucket_total{bucket="3_10"} 2109
telemt_desync_frames_bucket_total{bucket="gt_10"} 1823
telemt_pool_swap_total 47
telemt_pool_force_close_total 1237
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 15172
telemt_me_writer_removed_unexpected_total 315
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1172
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14329
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1195
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13935
telemt_me_writer_teardown_success_total{mode="normal"} 15501
telemt_me_writer_teardown_noop_total 15173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30674
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.362675
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30674
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 289
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1109808
telemt_user_connections_current{user="hello"} 3336
telemt_user_octets_from_client{user="hello"} 20224776357 (18.84 GB)
telemt_user_octets_to_client{user="hello"} 534763957471 (498.04 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1199
telemt_user_unique_ips_recent_window{user="hello"} 470
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 42512.0 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1539375
telemt_connections_bad_total 195625
telemt_connections_current 3153
telemt_connections_me_current 3153
telemt_handshake_timeouts_total 50442
telemt_upstream_connect_attempt_total 17842
telemt_upstream_connect_success_total 17830
telemt_upstream_connect_attempts_per_request{bucket="1"} 17830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 411
telemt_me_reconnect_success_total 312
telemt_me_reader_eof_total 313
telemt_me_idle_close_by_peer_total 313
telemt_me_route_drop_no_conn_total 344841
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1100352
telemt_me_endpoint_quarantine_total 341
telemt_me_single_endpoint_shadow_rotate_total 331
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 5330
telemt_desync_full_logged_total 1877
telemt_desync_suppressed_total 3453
telemt_desync_frames_bucket_total{bucket="1_2"} 1387
telemt_desync_frames_bucket_total{bucket="3_10"} 2060
telemt_desync_frames_bucket_total{bucket="gt_10"} 1883
telemt_pool_swap_total 46
telemt_pool_force_close_total 1189
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 93
telemt_me_draining_writers_reap_progress_total 16118
telemt_me_writer_removed_unexpected_total 290
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1140
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15293
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14929
telemt_me_writer_teardown_success_total{mode="normal"} 16433
telemt_me_writer_teardown_noop_total 16121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32554
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.856762
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32554
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 93
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 282
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1098444
telemt_user_connections_current{user="hello"} 3153
telemt_user_octets_from_client{user="hello"} 28110726708 (26.18 GB)
telemt_user_octets_to_client{user="hello"} 568421986872 (529.38 GB)
telemt_user_unique_ips_current{user="hello"} 1096
telemt_user_unique_ips_recent_window{user="hello"} 539
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 42551.4 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4153640
telemt_connections_bad_total 236391
telemt_connections_current 5139
telemt_connections_me_current 5139
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 195230
telemt_upstream_connect_attempt_total 43376
telemt_upstream_connect_success_total 41410
telemt_upstream_connect_fail_total 1367
telemt_upstream_connect_attempts_per_request{bucket="1"} 42777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1266
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1367
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2192
telemt_me_reconnect_success_total 768
telemt_me_reader_eof_total 504
telemt_me_idle_close_by_peer_total 503
telemt_me_route_drop_no_conn_total 6041184
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3448477
telemt_me_endpoint_quarantine_total 346
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 339
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
telemt_me_writers_active_current 47
telemt_desync_total 7437
telemt_desync_full_logged_total 2529
telemt_desync_suppressed_total 4908
telemt_desync_frames_bucket_total{bucket="1_2"} 1653
telemt_desync_frames_bucket_total{bucket="3_10"} 3215
telemt_desync_frames_bucket_total{bucket="gt_10"} 2569
telemt_pool_swap_total 45
telemt_pool_force_close_total 1312
telemt_me_writer_close_signal_drop_total 228
telemt_me_draining_writers_reap_progress_total 14403
telemt_me_writer_removed_unexpected_total 729
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1731
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13359
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1194
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 118
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13091
telemt_me_writer_teardown_success_total{mode="normal"} 15090
telemt_me_writer_teardown_noop_total 14409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29499
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.600464
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29499
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 228
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 503
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 3470679
telemt_user_connections_current{user="hello"} 5139
telemt_user_octets_from_client{user="hello"} 40471894246 (37.69 GB)
telemt_user_octets_to_client{user="hello"} 520349186150 (484.61 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1639
telemt_user_unique_ips_recent_window{user="hello"} 1417
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 42518.9 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1608904
telemt_connections_bad_total 221145
telemt_connections_current 2983
telemt_connections_me_current 2983
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31324
telemt_upstream_connect_attempt_total 19360
telemt_upstream_connect_success_total 19184
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 19343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_reconnect_attempts_total 1703
telemt_me_reconnect_success_total 538
telemt_me_reader_eof_total 551
telemt_me_idle_close_by_peer_total 551
telemt_me_route_drop_no_conn_total 421301
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1187674
telemt_me_endpoint_quarantine_total 267
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 340
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
telemt_me_writers_active_current 46
telemt_desync_total 5232
telemt_desync_full_logged_total 1939
telemt_desync_suppressed_total 3293
telemt_desync_frames_bucket_total{bucket="1_2"} 1007
telemt_desync_frames_bucket_total{bucket="3_10"} 2136
telemt_desync_frames_bucket_total{bucket="gt_10"} 2089
telemt_pool_swap_total 45
telemt_pool_force_close_total 1153
telemt_me_writer_close_signal_drop_total 73
telemt_me_draining_writers_reap_progress_total 16005
telemt_me_writer_removed_unexpected_total 530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1391
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15165
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1086
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 67
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14852
telemt_me_writer_teardown_success_total{mode="normal"} 16556
telemt_me_writer_teardown_noop_total 16005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32561
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.211015
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32561
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 73
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 454
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1184735
telemt_user_connections_current{user="hello"} 2983
telemt_user_octets_from_client{user="hello"} 20493536292 (19.09 GB)
telemt_user_octets_to_client{user="hello"} 558632461854 (520.27 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1113
telemt_user_unique_ips_recent_window{user="hello"} 720
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 42513.4 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2108862
telemt_connections_bad_total 132103
telemt_connections_current 2966
telemt_connections_me_current 2966
telemt_handshake_timeouts_total 794887
telemt_upstream_connect_attempt_total 18203
telemt_upstream_connect_success_total 18169
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 18172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 458
telemt_me_reconnect_success_total 277
telemt_me_reader_eof_total 279
telemt_me_idle_close_by_peer_total 279
telemt_me_route_drop_no_conn_total 380350
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1046416
telemt_me_endpoint_quarantine_total 350
telemt_me_single_endpoint_shadow_rotate_total 340
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
telemt_me_writers_active_current 44
telemt_desync_total 5199
telemt_desync_full_logged_total 1840
telemt_desync_suppressed_total 3359
telemt_desync_frames_bucket_total{bucket="1_2"} 895
telemt_desync_frames_bucket_total{bucket="3_10"} 2106
telemt_desync_frames_bucket_total{bucket="gt_10"} 2198
telemt_pool_swap_total 47
telemt_pool_force_close_total 1124
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 16292
telemt_me_writer_removed_unexpected_total 269
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1014
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15566
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1107
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15168
telemt_me_writer_teardown_success_total{mode="normal"} 16580
telemt_me_writer_teardown_noop_total 16292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32872
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.662955
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32872
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 247
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1042864
telemt_user_connections_current{user="hello"} 2966
telemt_user_octets_from_client{user="hello"} 17965553704 (16.73 GB)
telemt_user_octets_to_client{user="hello"} 529992830468 (493.59 GB)
telemt_user_unique_ips_current{user="hello"} 1107
telemt_user_unique_ips_recent_window{user="hello"} 757
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 40505.3 (11h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441878
telemt_connections_bad_total 14209
telemt_connections_current 545
telemt_connections_me_current 545
telemt_handshake_timeouts_total 147338
telemt_upstream_connect_attempt_total 20091
telemt_upstream_connect_success_total 20089
telemt_upstream_connect_attempts_per_request{bucket="1"} 20089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 741
telemt_me_reconnect_success_total 309
telemt_me_reader_eof_total 312
telemt_me_idle_close_by_peer_total 312
telemt_me_route_drop_no_conn_total 98542
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250125
telemt_me_endpoint_quarantine_total 390
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 346
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 1601
telemt_desync_full_logged_total 672
telemt_desync_suppressed_total 929
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 661
telemt_desync_frames_bucket_total{bucket="gt_10"} 618
telemt_pool_swap_total 44
telemt_pool_force_close_total 936
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 17949
telemt_me_writer_removed_unexpected_total 294
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1261
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16985
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 934
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17013
telemt_me_writer_teardown_success_total{mode="normal"} 18246
telemt_me_writer_teardown_noop_total 17949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36195
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.397640
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36195
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 260
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 250317
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 3525593923 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 102850092349 (95.79 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 42523.3 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1646767
telemt_connections_bad_total 140012
telemt_connections_current 3906
telemt_connections_me_current 3906
telemt_handshake_timeouts_total 42064
telemt_upstream_connect_attempt_total 18796
telemt_upstream_connect_success_total 18711
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 18767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9298
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 662
telemt_me_reconnect_success_total 401
telemt_me_reader_eof_total 368
telemt_me_idle_close_by_peer_total 368
telemt_me_route_drop_no_conn_total 389202
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1293429
telemt_me_endpoint_quarantine_total 345
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 343
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
telemt_me_writers_active_current 48
telemt_desync_total 5173
telemt_desync_full_logged_total 1739
telemt_desync_suppressed_total 3434
telemt_desync_frames_bucket_total{bucket="1_2"} 1265
telemt_desync_frames_bucket_total{bucket="3_10"} 1940
telemt_desync_frames_bucket_total{bucket="gt_10"} 1968
telemt_pool_swap_total 47
telemt_pool_force_close_total 1140
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 96
telemt_me_draining_writers_reap_progress_total 16950
telemt_me_writer_removed_unexpected_total 367
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1241
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16085
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1120
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15810
telemt_me_writer_teardown_success_total{mode="normal"} 17326
telemt_me_writer_teardown_noop_total 16950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34276
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.119183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34276
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 96
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 359
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 1288352
telemt_user_connections_current{user="hello"} 3906
telemt_user_octets_from_client{user="hello"} 28722639928 (26.75 GB)
telemt_user_octets_to_client{user="hello"} 594631085376 (553.79 GB)
telemt_user_unique_ips_current{user="hello"} 1347
telemt_user_unique_ips_recent_window{user="hello"} 890
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 42520.2 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1578617
telemt_connections_bad_total 130864
telemt_connections_current 3259
telemt_connections_me_current 3259
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 39615
telemt_upstream_connect_attempt_total 27242
telemt_upstream_connect_success_total 27047
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 27201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9699
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_reconnect_attempts_total 2781
telemt_me_reconnect_success_total 537
telemt_me_reader_eof_total 456
telemt_me_idle_close_by_peer_total 456
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 395927
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1252289
telemt_me_endpoint_quarantine_total 405
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 336
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
telemt_me_writers_active_current 45
telemt_desync_total 4931
telemt_desync_full_logged_total 1599
telemt_desync_suppressed_total 3332
telemt_desync_frames_bucket_total{bucket="1_2"} 1374
telemt_desync_frames_bucket_total{bucket="3_10"} 1787
telemt_desync_frames_bucket_total{bucket="gt_10"} 1770
telemt_pool_swap_total 47
telemt_pool_force_close_total 1117
telemt_me_writer_close_signal_drop_total 92
telemt_me_draining_writers_reap_progress_total 16056
telemt_me_writer_removed_unexpected_total 465
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1443
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15103
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1069
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14939
telemt_me_writer_teardown_success_total{mode="normal"} 16546
telemt_me_writer_teardown_noop_total 16056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32602
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.448197
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32602
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 92
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 405
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1256426
telemt_user_connections_current{user="hello"} 3259
telemt_user_octets_from_client{user="hello"} 19255681191 (17.93 GB)
telemt_user_octets_to_client{user="hello"} 557067169459 (518.81 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1156
telemt_user_unique_ips_recent_window{user="hello"} 786
```