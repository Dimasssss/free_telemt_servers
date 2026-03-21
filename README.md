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

# Server Metrics 2026-03-21 07:24:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 38892.4 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 890391
telemt_connections_bad_total 47249
telemt_connections_current 1060
telemt_connections_me_current 1060
telemt_handshake_timeouts_total 41900
telemt_upstream_connect_attempt_total 15576
telemt_upstream_connect_success_total 15505
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 15553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 502
telemt_me_reconnect_success_total 246
telemt_me_reader_eof_total 261
telemt_me_idle_close_by_peer_total 261
telemt_me_route_drop_no_conn_total 286862
telemt_me_route_drop_channel_closed_total 105
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 652348
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 277
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 321
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
telemt_desync_total 2887
telemt_desync_full_logged_total 1034
telemt_desync_suppressed_total 1853
telemt_desync_frames_bucket_total{bucket="1_2"} 600
telemt_desync_frames_bucket_total{bucket="3_10"} 1132
telemt_desync_frames_bucket_total{bucket="gt_10"} 1155
telemt_pool_swap_total 43
telemt_pool_force_close_total 1192
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 14058
telemt_me_writer_removed_unexpected_total 245
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1044
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13214
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1185
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12866
telemt_me_writer_teardown_success_total{mode="normal"} 14258
telemt_me_writer_teardown_noop_total 14059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28317
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.752854
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28317
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 651573
telemt_user_connections_current{user="hello"} 1060
telemt_user_octets_from_client{user="hello"} 7846282436 (7.31 GB)
telemt_user_octets_to_client{user="hello"} 205635619372 (191.51 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 38893.5 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2199844
telemt_connections_bad_total 241833
telemt_connections_current 3814
telemt_connections_me_current 3814
telemt_handshake_timeouts_total 66896
telemt_upstream_connect_attempt_total 14530
telemt_upstream_connect_success_total 14463
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 14509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 862
telemt_me_reconnect_success_total 293
telemt_me_reader_eof_total 301
telemt_me_idle_close_by_peer_total 300
telemt_me_route_drop_no_conn_total 465593
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1356243
telemt_me_endpoint_quarantine_total 253
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 310
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
telemt_desync_total 5813
telemt_desync_full_logged_total 2039
telemt_desync_suppressed_total 3774
telemt_desync_frames_bucket_total{bucket="1_2"} 1176
telemt_desync_frames_bucket_total{bucket="3_10"} 2287
telemt_desync_frames_bucket_total{bucket="gt_10"} 2350
telemt_pool_swap_total 42
telemt_pool_force_close_total 1250
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 13028
telemt_me_writer_removed_unexpected_total 282
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1162
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12140
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1192
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11778
telemt_me_writer_teardown_success_total{mode="normal"} 13302
telemt_me_writer_teardown_noop_total 13028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26330
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.064085
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26330
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1353120
telemt_user_connections_current{user="hello"} 3814
telemt_user_octets_from_client{user="hello"} 18635250716 (17.36 GB)
telemt_user_octets_to_client{user="hello"} 554794045820 (516.69 GB)
telemt_user_unique_ips_current{user="hello"} 1349
telemt_user_unique_ips_recent_window{user="hello"} 940
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 38889.9 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1491194
telemt_connections_bad_total 165008
telemt_connections_current 3135
telemt_connections_me_current 3135
telemt_handshake_timeouts_total 66768
telemt_upstream_connect_attempt_total 15657
telemt_upstream_connect_success_total 15647
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 487
telemt_me_reconnect_success_total 256
telemt_me_reader_eof_total 265
telemt_me_idle_close_by_peer_total 265
telemt_me_route_drop_no_conn_total 390718
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1164395
telemt_me_endpoint_quarantine_total 279
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 311
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
telemt_desync_total 4734
telemt_desync_full_logged_total 1694
telemt_desync_suppressed_total 3040
telemt_desync_frames_bucket_total{bucket="1_2"} 1035
telemt_desync_frames_bucket_total{bucket="3_10"} 1816
telemt_desync_frames_bucket_total{bucket="gt_10"} 1883
telemt_pool_swap_total 43
telemt_pool_force_close_total 1214
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 138
telemt_me_draining_writers_reap_progress_total 14266
telemt_me_writer_removed_unexpected_total 247
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1113
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13314
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1196
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13052
telemt_me_writer_teardown_success_total{mode="normal"} 14427
telemt_me_writer_teardown_noop_total 14269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28696
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.052653
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28696
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 138
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 219
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1162014
telemt_user_connections_current{user="hello"} 3135
telemt_user_octets_from_client{user="hello"} 15992471184 (14.89 GB)
telemt_user_octets_to_client{user="hello"} 514580358612 (479.24 GB)
telemt_user_unique_ips_current{user="hello"} 1136
telemt_user_unique_ips_recent_window{user="hello"} 648
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 38891.1 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1291097
telemt_connections_bad_total 159327
telemt_connections_current 2346
telemt_connections_me_current 2346
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 59586
telemt_upstream_connect_attempt_total 20485
telemt_upstream_connect_success_total 20262
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 20381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8924
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 732
telemt_me_reconnect_success_total 314
telemt_me_reader_eof_total 298
telemt_me_idle_close_by_peer_total 298
telemt_me_route_drop_no_conn_total 367533
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 894019
telemt_me_endpoint_quarantine_total 285
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 316
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 4129
telemt_desync_full_logged_total 1478
telemt_desync_suppressed_total 2651
telemt_desync_frames_bucket_total{bucket="1_2"} 943
telemt_desync_frames_bucket_total{bucket="3_10"} 1738
telemt_desync_frames_bucket_total{bucket="gt_10"} 1448
telemt_pool_swap_total 43
telemt_pool_force_close_total 1076
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 57
telemt_me_draining_writers_reap_progress_total 14089
telemt_me_writer_removed_unexpected_total 290
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1077
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13316
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1050
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13013
telemt_me_writer_teardown_success_total{mode="normal"} 14393
telemt_me_writer_teardown_noop_total 14090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28483
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.502695
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28483
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 57
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 263
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 896930
telemt_user_connections_current{user="hello"} 2346
telemt_user_octets_from_client{user="hello"} 15539078777 (14.47 GB)
telemt_user_octets_to_client{user="hello"} 417822753699 (389.13 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 923
telemt_user_unique_ips_recent_window{user="hello"} 377
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 38855.3 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1242820
telemt_connections_bad_total 149514
telemt_connections_current 3107
telemt_connections_me_current 3107
telemt_handshake_timeouts_total 44436
telemt_upstream_connect_attempt_total 16411
telemt_upstream_connect_success_total 16402
telemt_upstream_connect_attempts_per_request{bucket="1"} 16402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9079
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 323
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 242
telemt_me_idle_close_by_peer_total 242
telemt_me_route_drop_no_conn_total 263917
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 884295
telemt_me_endpoint_quarantine_total 317
telemt_me_single_endpoint_shadow_rotate_total 307
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
telemt_me_writers_active_current 42
telemt_desync_total 4265
telemt_desync_full_logged_total 1545
telemt_desync_suppressed_total 2720
telemt_desync_frames_bucket_total{bucket="1_2"} 1056
telemt_desync_frames_bucket_total{bucket="3_10"} 1658
telemt_desync_frames_bucket_total{bucket="gt_10"} 1551
telemt_pool_swap_total 43
telemt_pool_force_close_total 1048
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 71
telemt_me_draining_writers_reap_progress_total 14849
telemt_me_writer_removed_unexpected_total 222
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 991
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14101
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1038
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13801
telemt_me_writer_teardown_success_total{mode="normal"} 15092
telemt_me_writer_teardown_noop_total 14850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29942
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.664979
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29942
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 71
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 216
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 882720
telemt_user_connections_current{user="hello"} 3107
telemt_user_octets_from_client{user="hello"} 22302046812 (20.77 GB)
telemt_user_octets_to_client{user="hello"} 460605414736 (428.97 GB)
telemt_user_unique_ips_current{user="hello"} 1168
telemt_user_unique_ips_recent_window{user="hello"} 414
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 38894.5 (10h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2871731
telemt_connections_bad_total 185062
telemt_connections_current 4691
telemt_connections_me_current 4691
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 167711
telemt_upstream_connect_attempt_total 41895
telemt_upstream_connect_success_total 39994
telemt_upstream_connect_fail_total 1352
telemt_upstream_connect_attempts_per_request{bucket="1"} 41346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1352
telemt_me_reconnect_attempts_total 1971
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 419
telemt_me_idle_close_by_peer_total 418
telemt_me_route_drop_no_conn_total 2996575
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2314748
telemt_me_endpoint_quarantine_total 316
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 84
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 84
telemt_me_single_endpoint_shadow_rotate_total 313
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
telemt_me_writers_active_current 45
telemt_desync_total 5527
telemt_desync_full_logged_total 1998
telemt_desync_suppressed_total 3529
telemt_desync_frames_bucket_total{bucket="1_2"} 1255
telemt_desync_frames_bucket_total{bucket="3_10"} 2337
telemt_desync_frames_bucket_total{bucket="gt_10"} 1935
telemt_pool_swap_total 42
telemt_pool_force_close_total 1154
telemt_me_writer_close_signal_drop_total 185
telemt_me_draining_writers_reap_progress_total 13161
telemt_me_writer_removed_unexpected_total 635
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1545
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12220
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1074
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12007
telemt_me_writer_teardown_success_total{mode="normal"} 13765
telemt_me_writer_teardown_noop_total 13166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26931
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.675747
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26931
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 185
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 422
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 2337294
telemt_user_connections_current{user="hello"} 4691
telemt_user_octets_from_client{user="hello"} 35393243866 (32.96 GB)
telemt_user_octets_to_client{user="hello"} 479998036146 (447.03 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1650
telemt_user_unique_ips_recent_window{user="hello"} 814
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 38862.2 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1326063
telemt_connections_bad_total 191674
telemt_connections_current 2446
telemt_connections_me_current 2446
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 27559
telemt_upstream_connect_attempt_total 18239
telemt_upstream_connect_success_total 18076
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 18223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_reconnect_attempts_total 1631
telemt_me_reconnect_success_total 505
telemt_me_reader_eof_total 520
telemt_me_idle_close_by_peer_total 520
telemt_me_route_drop_no_conn_total 329760
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 959440
telemt_me_endpoint_quarantine_total 245
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 312
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
telemt_desync_total 4049
telemt_desync_full_logged_total 1533
telemt_desync_suppressed_total 2516
telemt_desync_frames_bucket_total{bucket="1_2"} 776
telemt_desync_frames_bucket_total{bucket="3_10"} 1635
telemt_desync_frames_bucket_total{bucket="gt_10"} 1638
telemt_pool_swap_total 41
telemt_pool_force_close_total 1007
telemt_me_writer_close_signal_drop_total 63
telemt_me_draining_writers_reap_progress_total 14989
telemt_me_writer_removed_unexpected_total 499
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1277
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14232
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13982
telemt_me_writer_teardown_success_total{mode="normal"} 15509
telemt_me_writer_teardown_noop_total 14989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30498
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.078612
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30498
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 63
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 426
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 956951
telemt_user_connections_current{user="hello"} 2446
telemt_user_octets_from_client{user="hello"} 15948788428 (14.85 GB)
telemt_user_octets_to_client{user="hello"} 468047789490 (435.90 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 941
telemt_user_unique_ips_recent_window{user="hello"} 400
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 38856.6 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1707612
telemt_connections_bad_total 113183
telemt_connections_current 2857
telemt_connections_me_current 2857
telemt_handshake_timeouts_total 623200
telemt_upstream_connect_attempt_total 17035
telemt_upstream_connect_success_total 17007
telemt_upstream_connect_attempts_per_request{bucket="1"} 17007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 266
telemt_me_reconnect_attempts_total 360
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 261
telemt_me_idle_close_by_peer_total 261
telemt_me_route_drop_no_conn_total 295729
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 852367
telemt_me_endpoint_quarantine_total 331
telemt_me_single_endpoint_shadow_rotate_total 315
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
telemt_me_writers_active_current 43
telemt_desync_total 4028
telemt_desync_full_logged_total 1425
telemt_desync_suppressed_total 2603
telemt_desync_frames_bucket_total{bucket="1_2"} 708
telemt_desync_frames_bucket_total{bucket="3_10"} 1638
telemt_desync_frames_bucket_total{bucket="gt_10"} 1682
telemt_pool_swap_total 43
telemt_pool_force_close_total 975
telemt_me_writer_close_signal_drop_total 62
telemt_me_draining_writers_reap_progress_total 15238
telemt_me_writer_removed_unexpected_total 244
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 914
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14586
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 967
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14263
telemt_me_writer_teardown_success_total{mode="normal"} 15500
telemt_me_writer_teardown_noop_total 15238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30738
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.547922
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30738
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 62
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 226
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 849339
telemt_user_connections_current{user="hello"} 2857
telemt_user_octets_from_client{user="hello"} 14261346128 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 436313140300 (406.35 GB)
telemt_user_unique_ips_current{user="hello"} 1177
telemt_user_unique_ips_recent_window{user="hello"} 372
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 36848.2 (10h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 335717
telemt_connections_bad_total 11956
telemt_connections_current 559
telemt_connections_me_current 559
telemt_handshake_timeouts_total 94635
telemt_upstream_connect_attempt_total 18564
telemt_upstream_connect_success_total 18563
telemt_upstream_connect_attempts_per_request{bucket="1"} 18563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 690
telemt_me_reconnect_success_total 291
telemt_me_reader_eof_total 293
telemt_me_idle_close_by_peer_total 293
telemt_me_route_drop_no_conn_total 78795
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206972
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 318
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 1267
telemt_desync_full_logged_total 581
telemt_desync_suppressed_total 686
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 528
telemt_desync_frames_bucket_total{bucket="gt_10"} 497
telemt_pool_swap_total 40
telemt_pool_force_close_total 824
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 48
telemt_me_draining_writers_reap_progress_total 16552
telemt_me_writer_removed_unexpected_total 276
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1154
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15676
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 824
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15728
telemt_me_writer_teardown_success_total{mode="normal"} 16830
telemt_me_writer_teardown_noop_total 16552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33382
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.207218
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33382
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 48
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 207177
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 2447296283 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 89212608805 (83.09 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 38866.4 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1344158
telemt_connections_bad_total 100455
telemt_connections_current 3334
telemt_connections_me_current 3334
telemt_handshake_timeouts_total 35625
telemt_upstream_connect_attempt_total 17490
telemt_upstream_connect_success_total 17409
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 17460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 592
telemt_me_reconnect_success_total 347
telemt_me_reader_eof_total 330
telemt_me_idle_close_by_peer_total 330
telemt_me_route_drop_no_conn_total 299947
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1054951
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 315
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
telemt_me_writers_active_current 45
telemt_desync_total 4163
telemt_desync_full_logged_total 1402
telemt_desync_suppressed_total 2761
telemt_desync_frames_bucket_total{bucket="1_2"} 1076
telemt_desync_frames_bucket_total{bucket="3_10"} 1557
telemt_desync_frames_bucket_total{bucket="gt_10"} 1530
telemt_pool_swap_total 43
telemt_pool_force_close_total 991
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 80
telemt_me_draining_writers_reap_progress_total 15776
telemt_me_writer_removed_unexpected_total 331
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1107
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15007
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 986
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14785
telemt_me_writer_teardown_success_total{mode="normal"} 16114
telemt_me_writer_teardown_noop_total 15776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31890
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.635548
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31890
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 80
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 316
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 1050453
telemt_user_connections_current{user="hello"} 3334
telemt_user_octets_from_client{user="hello"} 17064345392 (15.89 GB)
telemt_user_octets_to_client{user="hello"} 482589015920 (449.45 GB)
telemt_user_unique_ips_current{user="hello"} 1288
telemt_user_unique_ips_recent_window{user="hello"} 443
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 38863.1 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1283537
telemt_connections_bad_total 92619
telemt_connections_current 3180
telemt_connections_me_current 3180
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 33079
telemt_upstream_connect_attempt_total 26022
telemt_upstream_connect_success_total 25834
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 25982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_reconnect_attempts_total 2589
telemt_me_reconnect_success_total 467
telemt_me_reader_eof_total 410
telemt_me_idle_close_by_peer_total 410
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 304262
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1022041
telemt_me_endpoint_quarantine_total 384
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 311
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
telemt_me_writers_active_current 42
telemt_desync_total 4098
telemt_desync_full_logged_total 1277
telemt_desync_suppressed_total 2821
telemt_desync_frames_bucket_total{bucket="1_2"} 1183
telemt_desync_frames_bucket_total{bucket="3_10"} 1500
telemt_desync_frames_bucket_total{bucket="gt_10"} 1415
telemt_pool_swap_total 43
telemt_pool_force_close_total 961
telemt_me_writer_close_signal_drop_total 80
telemt_me_draining_writers_reap_progress_total 14969
telemt_me_writer_removed_unexpected_total 422
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1316
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14097
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 941
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14008
telemt_me_writer_teardown_success_total{mode="normal"} 15413
telemt_me_writer_teardown_noop_total 14969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30382
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.506464
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30382
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 80
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 347
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1026715
telemt_user_connections_current{user="hello"} 3180
telemt_user_octets_from_client{user="hello"} 13308347055 (12.39 GB)
telemt_user_octets_to_client{user="hello"} 452371231559 (421.30 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1216
telemt_user_unique_ips_recent_window{user="hello"} 451
```