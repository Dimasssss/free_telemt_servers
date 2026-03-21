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

# Server Metrics 2026-03-21 08:09:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 41634.7 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1019266
telemt_connections_bad_total 53173
telemt_connections_current 1524
telemt_connections_me_current 1524
telemt_handshake_timeouts_total 46537
telemt_upstream_connect_attempt_total 16669
telemt_upstream_connect_success_total 16595
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 16645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10657
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 660
telemt_me_reconnect_success_total 296
telemt_me_reader_eof_total 300
telemt_me_idle_close_by_peer_total 300
telemt_me_route_drop_no_conn_total 321229
telemt_me_route_drop_channel_closed_total 129
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 737427
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 297
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 343
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
telemt_desync_total 3203
telemt_desync_full_logged_total 1151
telemt_desync_suppressed_total 2052
telemt_desync_frames_bucket_total{bucket="1_2"} 669
telemt_desync_frames_bucket_total{bucket="3_10"} 1232
telemt_desync_frames_bucket_total{bucket="gt_10"} 1302
telemt_pool_swap_total 46
telemt_pool_force_close_total 1254
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 156
telemt_me_draining_writers_reap_progress_total 14900
telemt_me_writer_removed_unexpected_total 282
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1159
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13953
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13646
telemt_me_writer_teardown_success_total{mode="normal"} 15112
telemt_me_writer_teardown_noop_total 14901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30013
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.216929
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30013
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 156
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 260
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 736812
telemt_user_connections_current{user="hello"} 1524
telemt_user_octets_from_client{user="hello"} 10390346755 (9.68 GB)
telemt_user_octets_to_client{user="hello"} 228522482715 (212.83 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 538
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 41635.8 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2529064
telemt_connections_bad_total 282967
telemt_connections_current 3983
telemt_connections_me_current 3983
telemt_handshake_timeouts_total 72571
telemt_upstream_connect_attempt_total 15394
telemt_upstream_connect_success_total 15321
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 15370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 933
telemt_me_reconnect_success_total 343
telemt_me_reader_eof_total 338
telemt_me_idle_close_by_peer_total 337
telemt_me_route_drop_no_conn_total 633407
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1605286
telemt_me_endpoint_quarantine_total 277
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 329
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
telemt_me_writers_active_current 42
telemt_desync_total 6986
telemt_desync_full_logged_total 2399
telemt_desync_suppressed_total 4587
telemt_desync_frames_bucket_total{bucket="1_2"} 1423
telemt_desync_frames_bucket_total{bucket="3_10"} 2741
telemt_desync_frames_bucket_total{bucket="gt_10"} 2822
telemt_pool_swap_total 45
telemt_pool_force_close_total 1351
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 13800
telemt_me_writer_removed_unexpected_total 316
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1257
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12854
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1276
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 75
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12449
telemt_me_writer_teardown_success_total{mode="normal"} 14111
telemt_me_writer_teardown_noop_total 13800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27911
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.683118
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27911
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 273
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1601901
telemt_user_connections_current{user="hello"} 3983
telemt_user_octets_from_client{user="hello"} 22863568852 (21.29 GB)
telemt_user_octets_to_client{user="hello"} 629529773596 (586.30 GB)
telemt_user_unique_ips_current{user="hello"} 1292
telemt_user_unique_ips_recent_window{user="hello"} 668
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 41632.4 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1802375
telemt_connections_bad_total 208300
telemt_connections_current 5004
telemt_connections_me_current 5004
telemt_handshake_timeouts_total 72793
telemt_upstream_connect_attempt_total 16524
telemt_upstream_connect_success_total 16514
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 539
telemt_me_reconnect_success_total 307
telemt_me_reader_eof_total 316
telemt_me_idle_close_by_peer_total 316
telemt_me_route_drop_no_conn_total 558779
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1396562
telemt_me_endpoint_quarantine_total 287
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 333
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
telemt_me_writers_active_current 87
telemt_desync_total 5750
telemt_desync_full_logged_total 2027
telemt_desync_suppressed_total 3723
telemt_desync_frames_bucket_total{bucket="1_2"} 1284
telemt_desync_frames_bucket_total{bucket="3_10"} 2212
telemt_desync_frames_bucket_total{bucket="gt_10"} 2254
telemt_pool_swap_total 45
telemt_pool_force_close_total 1277
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 14978
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1215
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13975
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1254
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13701
telemt_me_writer_teardown_success_total{mode="normal"} 15190
telemt_me_writer_teardown_noop_total 14982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30172
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.101990
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30172
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 270
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1394065
telemt_user_connections_current{user="hello"} 5004
telemt_user_octets_from_client{user="hello"} 19280461344 (17.96 GB)
telemt_user_octets_to_client{user="hello"} 581664421876 (541.72 GB)
telemt_user_unique_ips_current{user="hello"} 1809
telemt_user_unique_ips_recent_window{user="hello"} 621
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 41633.5 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1535568
telemt_connections_bad_total 193914
telemt_connections_current 2814
telemt_connections_me_current 2814
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 65822
telemt_upstream_connect_attempt_total 21381
telemt_upstream_connect_success_total 21152
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 21273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 780
telemt_me_reconnect_success_total 341
telemt_me_reader_eof_total 317
telemt_me_idle_close_by_peer_total 317
telemt_me_route_drop_no_conn_total 433788
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1050353
telemt_me_endpoint_quarantine_total 303
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 336
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
telemt_me_writers_active_current 46
telemt_desync_total 4822
telemt_desync_full_logged_total 1692
telemt_desync_suppressed_total 3130
telemt_desync_frames_bucket_total{bucket="1_2"} 1138
telemt_desync_frames_bucket_total{bucket="3_10"} 1978
telemt_desync_frames_bucket_total{bucket="gt_10"} 1706
telemt_pool_swap_total 46
telemt_pool_force_close_total 1203
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 70
telemt_me_draining_writers_reap_progress_total 14917
telemt_me_writer_removed_unexpected_total 309
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1151
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14089
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1165
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13714
telemt_me_writer_teardown_success_total{mode="normal"} 15240
telemt_me_writer_teardown_noop_total 14918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30158
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.248811
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30158
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 70
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 285
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1052813
telemt_user_connections_current{user="hello"} 2814
telemt_user_octets_from_client{user="hello"} 18484704485 (17.22 GB)
telemt_user_octets_to_client{user="hello"} 505387502587 (470.68 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 942
telemt_user_unique_ips_recent_window{user="hello"} 752
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 41597.7 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1451554
telemt_connections_bad_total 168644
telemt_connections_current 4107
telemt_connections_me_current 4107
telemt_handshake_timeouts_total 49148
telemt_upstream_connect_attempt_total 17333
telemt_upstream_connect_success_total 17322
telemt_upstream_connect_attempts_per_request{bucket="1"} 17322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9597
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 374
telemt_me_reconnect_success_total 293
telemt_me_reader_eof_total 291
telemt_me_idle_close_by_peer_total 291
telemt_me_route_drop_no_conn_total 325745
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1044880
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_shadow_rotate_total 326
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
telemt_me_writers_active_current 76
telemt_me_writers_warm_current 11
telemt_desync_total 5064
telemt_desync_full_logged_total 1798
telemt_desync_suppressed_total 3266
telemt_desync_frames_bucket_total{bucket="1_2"} 1298
telemt_desync_frames_bucket_total{bucket="3_10"} 1966
telemt_desync_frames_bucket_total{bucket="gt_10"} 1800
telemt_pool_swap_total 45
telemt_pool_force_close_total 1136
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 15627
telemt_me_writer_removed_unexpected_total 270
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1077
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14843
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1125
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14491
telemt_me_writer_teardown_success_total{mode="normal"} 15920
telemt_me_writer_teardown_noop_total 15630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31550
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.567422
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31550
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 263
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1043052
telemt_user_connections_current{user="hello"} 4107
telemt_user_octets_from_client{user="hello"} 27166775968 (25.30 GB)
telemt_user_octets_to_client{user="hello"} 541338168960 (504.16 GB)
telemt_user_unique_ips_current{user="hello"} 1438
telemt_user_unique_ips_recent_window{user="hello"} 692
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 41637.3 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3804917
telemt_connections_bad_total 218228
telemt_connections_current 5551
telemt_connections_me_current 5551
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 188378
telemt_upstream_connect_attempt_total 43061
telemt_upstream_connect_success_total 41110
telemt_upstream_connect_fail_total 1363
telemt_upstream_connect_attempts_per_request{bucket="1"} 42473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1260
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1363
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 2105
telemt_me_reconnect_success_total 733
telemt_me_reader_eof_total 482
telemt_me_idle_close_by_peer_total 481
telemt_me_route_drop_no_conn_total 5094661
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3141087
telemt_me_endpoint_quarantine_total 331
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 84
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 84
telemt_me_single_endpoint_shadow_rotate_total 332
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
telemt_desync_total 7050
telemt_desync_full_logged_total 2414
telemt_desync_suppressed_total 4636
telemt_desync_frames_bucket_total{bucket="1_2"} 1565
telemt_desync_frames_bucket_total{bucket="3_10"} 3028
telemt_desync_frames_bucket_total{bucket="gt_10"} 2457
telemt_pool_swap_total 44
telemt_pool_force_close_total 1282
telemt_me_writer_close_signal_drop_total 219
telemt_me_draining_writers_reap_progress_total 14179
telemt_me_writer_removed_unexpected_total 705
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1697
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13145
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 118
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12897
telemt_me_writer_teardown_success_total{mode="normal"} 14842
telemt_me_writer_teardown_noop_total 14185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29027
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 28.350534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29027
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 219
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 483
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 3163359
telemt_user_connections_current{user="hello"} 5551
telemt_user_octets_from_client{user="hello"} 39192738438 (36.50 GB)
telemt_user_octets_to_client{user="hello"} 511806131754 (476.66 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1812
telemt_user_unique_ips_recent_window{user="hello"} 1142
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 41604.6 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1532235
telemt_connections_bad_total 213338
telemt_connections_current 3960
telemt_connections_me_current 3960
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30049
telemt_upstream_connect_attempt_total 19131
telemt_upstream_connect_success_total 18959
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 19114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_reconnect_attempts_total 1687
telemt_me_reconnect_success_total 528
telemt_me_reader_eof_total 543
telemt_me_idle_close_by_peer_total 543
telemt_me_route_drop_no_conn_total 399067
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1127124
telemt_me_endpoint_quarantine_total 263
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 333
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
telemt_desync_total 4896
telemt_desync_full_logged_total 1821
telemt_desync_suppressed_total 3075
telemt_desync_frames_bucket_total{bucket="1_2"} 945
telemt_desync_frames_bucket_total{bucket="3_10"} 1975
telemt_desync_frames_bucket_total{bucket="gt_10"} 1976
telemt_pool_swap_total 44
telemt_pool_force_close_total 1090
telemt_me_writer_close_signal_drop_total 68
telemt_me_draining_writers_reap_progress_total 15772
telemt_me_writer_removed_unexpected_total 522
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14954
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1028
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14682
telemt_me_writer_teardown_success_total{mode="normal"} 16315
telemt_me_writer_teardown_noop_total 15772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32087
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.136952
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32087
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 68
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 446
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1124372
telemt_user_connections_current{user="hello"} 3960
telemt_user_octets_from_client{user="hello"} 19110551844 (17.80 GB)
telemt_user_octets_to_client{user="hello"} 535155291558 (498.40 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1482
telemt_user_unique_ips_recent_window{user="hello"} 704
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 41598.8 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2007738
telemt_connections_bad_total 129314
telemt_connections_current 2169
telemt_connections_me_current 2169
telemt_handshake_timeouts_total 751397
telemt_upstream_connect_attempt_total 17917
telemt_upstream_connect_success_total 17883
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 17886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 453
telemt_me_reconnect_success_total 272
telemt_me_reader_eof_total 274
telemt_me_idle_close_by_peer_total 274
telemt_me_route_drop_no_conn_total 359474
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 994906
telemt_me_endpoint_quarantine_total 346
telemt_me_single_endpoint_shadow_rotate_total 335
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
telemt_desync_total 4947
telemt_desync_full_logged_total 1757
telemt_desync_suppressed_total 3190
telemt_desync_frames_bucket_total{bucket="1_2"} 861
telemt_desync_frames_bucket_total{bucket="3_10"} 2013
telemt_desync_frames_bucket_total{bucket="gt_10"} 2073
telemt_pool_swap_total 46
telemt_pool_force_close_total 1098
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 16053
telemt_me_writer_removed_unexpected_total 264
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 993
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15343
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1081
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14955
telemt_me_writer_teardown_success_total{mode="normal"} 16336
telemt_me_writer_teardown_noop_total 16053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32389
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.660056
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32389
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 242
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 991455
telemt_user_connections_current{user="hello"} 2169
telemt_user_octets_from_client{user="hello"} 17001233396 (15.83 GB)
telemt_user_octets_to_client{user="hello"} 505525320940 (470.81 GB)
telemt_user_unique_ips_current{user="hello"} 800
telemt_user_unique_ips_recent_window{user="hello"} 750
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 39590.2 (10h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419070
telemt_connections_bad_total 13557
telemt_connections_current 536
telemt_connections_me_current 536
telemt_handshake_timeouts_total 137881
telemt_upstream_connect_attempt_total 19701
telemt_upstream_connect_success_total 19699
telemt_upstream_connect_attempts_per_request{bucket="1"} 19699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 736
telemt_me_reconnect_success_total 305
telemt_me_reader_eof_total 308
telemt_me_idle_close_by_peer_total 308
telemt_me_route_drop_no_conn_total 93754
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239758
telemt_me_endpoint_quarantine_total 382
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 340
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
telemt_me_writers_active_current 44
telemt_desync_total 1501
telemt_desync_full_logged_total 646
telemt_desync_suppressed_total 855
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 621
telemt_desync_frames_bucket_total{bucket="gt_10"} 582
telemt_pool_swap_total 43
telemt_pool_force_close_total 906
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 53
telemt_me_draining_writers_reap_progress_total 17598
telemt_me_writer_removed_unexpected_total 290
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1235
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16656
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16692
telemt_me_writer_teardown_success_total{mode="normal"} 17891
telemt_me_writer_teardown_noop_total 17598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35489
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.382270
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35489
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 53
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 256
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 239977
telemt_user_connections_current{user="hello"} 536
telemt_user_octets_from_client{user="hello"} 3151799111 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 100093947805 (93.22 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 41608.8 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1563179
telemt_connections_bad_total 123538
telemt_connections_current 3381
telemt_connections_me_current 3381
telemt_handshake_timeouts_total 40222
telemt_upstream_connect_attempt_total 18483
telemt_upstream_connect_success_total 18399
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 18454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9137
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 619
telemt_me_reconnect_success_total 378
telemt_me_reader_eof_total 352
telemt_me_idle_close_by_peer_total 352
telemt_me_route_drop_no_conn_total 363382
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1231105
telemt_me_endpoint_quarantine_total 337
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 335
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
telemt_desync_total 4904
telemt_desync_full_logged_total 1648
telemt_desync_suppressed_total 3256
telemt_desync_frames_bucket_total{bucket="1_2"} 1217
telemt_desync_frames_bucket_total{bucket="3_10"} 1842
telemt_desync_frames_bucket_total{bucket="gt_10"} 1845
telemt_pool_swap_total 46
telemt_pool_force_close_total 1106
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 16679
telemt_me_writer_removed_unexpected_total 352
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1200
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15839
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1090
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15573
telemt_me_writer_teardown_success_total{mode="normal"} 17039
telemt_me_writer_teardown_noop_total 16679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33718
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.958420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33718
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1226162
telemt_user_connections_current{user="hello"} 3381
telemt_user_octets_from_client{user="hello"} 24927879120 (23.22 GB)
telemt_user_octets_to_client{user="hello"} 567301941888 (528.34 GB)
telemt_user_unique_ips_current{user="hello"} 1161
telemt_user_unique_ips_recent_window{user="hello"} 910
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 41605.6 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1500556
telemt_connections_bad_total 114443
telemt_connections_current 3579
telemt_connections_me_current 3579
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 38562
telemt_upstream_connect_attempt_total 26917
telemt_upstream_connect_success_total 26725
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 2757
telemt_me_reconnect_success_total 521
telemt_me_reader_eof_total 441
telemt_me_idle_close_by_peer_total 441
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 370203
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1194496
telemt_me_endpoint_quarantine_total 395
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 331
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
telemt_me_writers_active_current 52
telemt_desync_total 4749
telemt_desync_full_logged_total 1523
telemt_desync_suppressed_total 3226
telemt_desync_frames_bucket_total{bucket="1_2"} 1335
telemt_desync_frames_bucket_total{bucket="3_10"} 1720
telemt_desync_frames_bucket_total{bucket="gt_10"} 1694
telemt_pool_swap_total 46
telemt_pool_force_close_total 1060
telemt_me_writer_close_signal_drop_total 85
telemt_me_draining_writers_reap_progress_total 15745
telemt_me_writer_removed_unexpected_total 452
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1404
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14816
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14685
telemt_me_writer_teardown_success_total{mode="normal"} 16220
telemt_me_writer_teardown_noop_total 15745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31965
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.133866
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31965
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 85
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 392
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1198781
telemt_user_connections_current{user="hello"} 3579
telemt_user_octets_from_client{user="hello"} 18253779771 (17.00 GB)
telemt_user_octets_to_client{user="hello"} 530113737719 (493.71 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1364
telemt_user_unique_ips_recent_window{user="hello"} 801
```