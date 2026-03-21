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

# Server Metrics 2026-03-21 07:59:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 41025.5 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 992647
telemt_connections_bad_total 51743
telemt_connections_current 1566
telemt_connections_me_current 1566
telemt_handshake_timeouts_total 45777
telemt_upstream_connect_attempt_total 16245
telemt_upstream_connect_success_total 16173
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 16222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 531
telemt_me_reconnect_success_total 260
telemt_me_reader_eof_total 277
telemt_me_idle_close_by_peer_total 277
telemt_me_route_drop_no_conn_total 308391
telemt_me_route_drop_channel_closed_total 117
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 715948
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 284
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
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
telemt_me_writers_active_current 44
telemt_desync_total 3125
telemt_desync_full_logged_total 1124
telemt_desync_suppressed_total 2001
telemt_desync_frames_bucket_total{bucket="1_2"} 653
telemt_desync_frames_bucket_total{bucket="3_10"} 1199
telemt_desync_frames_bucket_total{bucket="gt_10"} 1273
telemt_pool_swap_total 45
telemt_pool_force_close_total 1250
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 14678
telemt_me_writer_removed_unexpected_total 259
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1101
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13781
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13428
telemt_me_writer_teardown_success_total{mode="normal"} 14882
telemt_me_writer_teardown_noop_total 14679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29561
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.286595
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29561
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 236
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 715160
telemt_user_connections_current{user="hello"} 1566
telemt_user_octets_from_client{user="hello"} 9759883288 (9.09 GB)
telemt_user_octets_to_client{user="hello"} 222969555580 (207.66 GB)
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 41027.2 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2425145
telemt_connections_bad_total 265963
telemt_connections_current 4442
telemt_connections_me_current 4442
telemt_handshake_timeouts_total 71334
telemt_upstream_connect_attempt_total 15201
telemt_upstream_connect_success_total 15129
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 15177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 896
telemt_me_reconnect_success_total 340
telemt_me_reader_eof_total 334
telemt_me_idle_close_by_peer_total 333
telemt_me_route_drop_no_conn_total 560124
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1530426
telemt_me_endpoint_quarantine_total 274
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 325
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
telemt_desync_total 6680
telemt_desync_full_logged_total 2309
telemt_desync_suppressed_total 4371
telemt_desync_frames_bucket_total{bucket="1_2"} 1365
telemt_desync_frames_bucket_total{bucket="3_10"} 2613
telemt_desync_frames_bucket_total{bucket="gt_10"} 2702
telemt_pool_swap_total 44
telemt_pool_force_close_total 1320
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 13622
telemt_me_writer_removed_unexpected_total 312
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1236
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12693
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1247
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12302
telemt_me_writer_teardown_success_total{mode="normal"} 13929
telemt_me_writer_teardown_noop_total 13622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27551
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.862388
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27551
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 271
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 1527107
telemt_user_connections_current{user="hello"} 4442
telemt_user_octets_from_client{user="hello"} 20864765588 (19.43 GB)
telemt_user_octets_to_client{user="hello"} 613654362248 (571.51 GB)
telemt_user_unique_ips_current{user="hello"} 1564
telemt_user_unique_ips_recent_window{user="hello"} 606
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 41023.7 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1715489
telemt_connections_bad_total 199589
telemt_connections_current 4178
telemt_connections_me_current 4178
telemt_handshake_timeouts_total 71572
telemt_upstream_connect_attempt_total 16263
telemt_upstream_connect_success_total 16253
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 494
telemt_me_reconnect_success_total 262
telemt_me_reader_eof_total 271
telemt_me_idle_close_by_peer_total 271
telemt_me_route_drop_no_conn_total 475341
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1326341
telemt_me_endpoint_quarantine_total 286
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 327
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
telemt_me_writers_active_current 44
telemt_desync_total 5431
telemt_desync_full_logged_total 1935
telemt_desync_suppressed_total 3496
telemt_desync_frames_bucket_total{bucket="1_2"} 1209
telemt_desync_frames_bucket_total{bucket="3_10"} 2067
telemt_desync_frames_bucket_total{bucket="gt_10"} 2155
telemt_pool_swap_total 45
telemt_pool_force_close_total 1277
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 14828
telemt_me_writer_removed_unexpected_total 253
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13834
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1254
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13551
telemt_me_writer_teardown_success_total{mode="normal"} 14995
telemt_me_writer_teardown_noop_total 14832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29827
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.074788
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29827
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 225
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1323845
telemt_user_connections_current{user="hello"} 4178
telemt_user_octets_from_client{user="hello"} 18564913136 (17.29 GB)
telemt_user_octets_to_client{user="hello"} 568341168616 (529.31 GB)
telemt_user_unique_ips_current{user="hello"} 1483
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 41025.1 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1466247
telemt_connections_bad_total 178311
telemt_connections_current 3392
telemt_connections_me_current 3392
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 64562
telemt_upstream_connect_attempt_total 21153
telemt_upstream_connect_success_total 20925
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 21045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 378
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 738
telemt_me_reconnect_success_total 318
telemt_me_reader_eof_total 302
telemt_me_idle_close_by_peer_total 302
telemt_me_route_drop_no_conn_total 414239
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1010024
telemt_me_endpoint_quarantine_total 295
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 329
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
telemt_desync_total 4631
telemt_desync_full_logged_total 1640
telemt_desync_suppressed_total 2991
telemt_desync_frames_bucket_total{bucket="1_2"} 1077
telemt_desync_frames_bucket_total{bucket="3_10"} 1918
telemt_desync_frames_bucket_total{bucket="gt_10"} 1636
telemt_pool_swap_total 45
telemt_pool_force_close_total 1166
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 14725
telemt_me_writer_removed_unexpected_total 294
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1120
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13913
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1135
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13559
telemt_me_writer_teardown_success_total{mode="normal"} 15033
telemt_me_writer_teardown_noop_total 14726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29759
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.624470
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29759
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 267
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1012589
telemt_user_connections_current{user="hello"} 3392
telemt_user_octets_from_client{user="hello"} 17716987345 (16.50 GB)
telemt_user_octets_to_client{user="hello"} 482875162087 (449.71 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1232
telemt_user_unique_ips_recent_window{user="hello"} 459
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 40988.8 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1392577
telemt_connections_bad_total 156552
telemt_connections_current 2959
telemt_connections_me_current 2959
telemt_handshake_timeouts_total 48358
telemt_upstream_connect_attempt_total 17105
telemt_upstream_connect_success_total 17096
telemt_upstream_connect_attempts_per_request{bucket="1"} 17096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9468
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 339
telemt_me_reconnect_success_total 260
telemt_me_reader_eof_total 257
telemt_me_idle_close_by_peer_total 257
telemt_me_route_drop_no_conn_total 306879
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1003159
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_shadow_rotate_total 323
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
telemt_me_writers_active_current 45
telemt_desync_total 4845
telemt_desync_full_logged_total 1728
telemt_desync_suppressed_total 3117
telemt_desync_frames_bucket_total{bucket="1_2"} 1237
telemt_desync_frames_bucket_total{bucket="3_10"} 1881
telemt_desync_frames_bucket_total{bucket="gt_10"} 1727
telemt_pool_swap_total 45
telemt_pool_force_close_total 1136
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 78
telemt_me_draining_writers_reap_progress_total 15497
telemt_me_writer_removed_unexpected_total 236
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1040
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14716
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1125
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14361
telemt_me_writer_teardown_success_total{mode="normal"} 15756
telemt_me_writer_teardown_noop_total 15500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31256
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.563756
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31256
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 78
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 230
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1001360
telemt_user_connections_current{user="hello"} 2959
telemt_user_octets_from_client{user="hello"} 26174421472 (24.38 GB)
telemt_user_octets_to_client{user="hello"} 521209553032 (485.41 GB)
telemt_user_unique_ips_current{user="hello"} 1095
telemt_user_unique_ips_recent_window{user="hello"} 438
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 41028.1 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3554106
telemt_connections_bad_total 210442
telemt_connections_current 5411
telemt_connections_me_current 5411
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 182788
telemt_upstream_connect_attempt_total 42754
telemt_upstream_connect_success_total 40819
telemt_upstream_connect_fail_total 1360
telemt_upstream_connect_attempts_per_request{bucket="1"} 42179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1360
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 2080
telemt_me_reconnect_success_total 725
telemt_me_reader_eof_total 475
telemt_me_idle_close_by_peer_total 474
telemt_me_route_drop_no_conn_total 4513662
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2918265
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 84
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 84
telemt_me_single_endpoint_shadow_rotate_total 330
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
telemt_me_writers_active_current 89
telemt_desync_total 6654
telemt_desync_full_logged_total 2304
telemt_desync_suppressed_total 4350
telemt_desync_frames_bucket_total{bucket="1_2"} 1478
telemt_desync_frames_bucket_total{bucket="3_10"} 2844
telemt_desync_frames_bucket_total{bucket="gt_10"} 2332
telemt_pool_swap_total 43
telemt_pool_force_close_total 1220
telemt_me_writer_close_signal_drop_total 205
telemt_me_draining_writers_reap_progress_total 13864
telemt_me_writer_removed_unexpected_total 697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1659
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12866
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12644
telemt_me_writer_teardown_success_total{mode="normal"} 14525
telemt_me_writer_teardown_noop_total 13869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28394
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.443125
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28394
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 205
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 477
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 2940694
telemt_user_connections_current{user="hello"} 5411
telemt_user_octets_from_client{user="hello"} 38368064226 (35.73 GB)
telemt_user_octets_to_client{user="hello"} 504430085778 (469.79 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1815
telemt_user_unique_ips_recent_window{user="hello"} 965
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 40995.1 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1482931
telemt_connections_bad_total 209347
telemt_connections_current 3081
telemt_connections_me_current 3081
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 29490
telemt_upstream_connect_attempt_total 18910
telemt_upstream_connect_success_total 18740
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 18893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_reconnect_attempts_total 1649
telemt_me_reconnect_success_total 523
telemt_me_reader_eof_total 536
telemt_me_idle_close_by_peer_total 536
telemt_me_route_drop_no_conn_total 377074
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1084737
telemt_me_endpoint_quarantine_total 257
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 329
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
telemt_me_writers_active_current 45
telemt_desync_total 4655
telemt_desync_full_logged_total 1762
telemt_desync_suppressed_total 2893
telemt_desync_frames_bucket_total{bucket="1_2"} 895
telemt_desync_frames_bucket_total{bucket="3_10"} 1882
telemt_desync_frames_bucket_total{bucket="gt_10"} 1878
telemt_pool_swap_total 43
telemt_pool_force_close_total 1090
telemt_me_writer_close_signal_drop_total 68
telemt_me_draining_writers_reap_progress_total 15607
telemt_me_writer_removed_unexpected_total 515
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1342
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14801
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1028
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14517
telemt_me_writer_teardown_success_total{mode="normal"} 16143
telemt_me_writer_teardown_noop_total 15607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31750
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.134709
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31750
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 68
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 441
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 1081979
telemt_user_connections_current{user="hello"} 3081
telemt_user_octets_from_client{user="hello"} 18161482900 (16.91 GB)
telemt_user_octets_to_client{user="hello"} 519136916862 (483.48 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1229
telemt_user_unique_ips_recent_window{user="hello"} 444
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 40989.7 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1928454
telemt_connections_bad_total 126826
telemt_connections_current 2852
telemt_connections_me_current 2852
telemt_handshake_timeouts_total 715236
telemt_upstream_connect_attempt_total 17715
telemt_upstream_connect_success_total 17681
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 17684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 273
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 413
telemt_me_reconnect_success_total 267
telemt_me_reader_eof_total 267
telemt_me_idle_close_by_peer_total 267
telemt_me_route_drop_no_conn_total 339263
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 959089
telemt_me_endpoint_quarantine_total 341
telemt_me_single_endpoint_shadow_rotate_total 332
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
telemt_desync_total 4660
telemt_desync_full_logged_total 1659
telemt_desync_suppressed_total 3001
telemt_desync_frames_bucket_total{bucket="1_2"} 808
telemt_desync_frames_bucket_total{bucket="3_10"} 1912
telemt_desync_frames_bucket_total{bucket="gt_10"} 1940
telemt_pool_swap_total 45
telemt_pool_force_close_total 1068
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 15878
telemt_me_writer_removed_unexpected_total 258
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 967
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15187
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1055
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14810
telemt_me_writer_teardown_success_total{mode="normal"} 16154
telemt_me_writer_teardown_noop_total 15878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32032
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.622227
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32032
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 238
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 955772
telemt_user_connections_current{user="hello"} 2852
telemt_user_octets_from_client{user="hello"} 16466056208 (15.34 GB)
telemt_user_octets_to_client{user="hello"} 489093900292 (455.50 GB)
telemt_user_unique_ips_current{user="hello"} 1122
telemt_user_unique_ips_recent_window{user="hello"} 433
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 38981.3 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 399972
telemt_connections_bad_total 13150
telemt_connections_current 544
telemt_connections_me_current 544
telemt_handshake_timeouts_total 127667
telemt_upstream_connect_attempt_total 19505
telemt_upstream_connect_success_total 19504
telemt_upstream_connect_attempts_per_request{bucket="1"} 19504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 732
telemt_me_reconnect_success_total 302
telemt_me_reader_eof_total 305
telemt_me_idle_close_by_peer_total 305
telemt_me_route_drop_no_conn_total 89782
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232385
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
telemt_me_writers_active_current 43
telemt_desync_total 1432
telemt_desync_full_logged_total 624
telemt_desync_suppressed_total 808
telemt_desync_frames_bucket_total{bucket="1_2"} 280
telemt_desync_frames_bucket_total{bucket="3_10"} 586
telemt_desync_frames_bucket_total{bucket="gt_10"} 566
telemt_pool_swap_total 43
telemt_pool_force_close_total 906
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 53
telemt_me_draining_writers_reap_progress_total 17426
telemt_me_writer_removed_unexpected_total 287
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1230
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16486
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16520
telemt_me_writer_teardown_success_total{mode="normal"} 17716
telemt_me_writer_teardown_noop_total 17426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35142
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.371540
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35142
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 53
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 253
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 232595
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 3068487507 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 97789651589 (91.07 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 41000.0 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1506732
telemt_connections_bad_total 118066
telemt_connections_current 3792
telemt_connections_me_current 3792
telemt_handshake_timeouts_total 38838
telemt_upstream_connect_attempt_total 18259
telemt_upstream_connect_success_total 18176
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 18230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 617
telemt_me_reconnect_success_total 376
telemt_me_reader_eof_total 350
telemt_me_idle_close_by_peer_total 350
telemt_me_route_drop_no_conn_total 345356
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1185082
telemt_me_endpoint_quarantine_total 331
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 331
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
telemt_me_writers_active_current 47
telemt_desync_total 4760
telemt_desync_full_logged_total 1593
telemt_desync_suppressed_total 3167
telemt_desync_frames_bucket_total{bucket="1_2"} 1200
telemt_desync_frames_bucket_total{bucket="3_10"} 1787
telemt_desync_frames_bucket_total{bucket="gt_10"} 1773
telemt_pool_swap_total 45
telemt_pool_force_close_total 1076
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 16471
telemt_me_writer_removed_unexpected_total 350
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1177
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15652
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1063
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15395
telemt_me_writer_teardown_success_total{mode="normal"} 16829
telemt_me_writer_teardown_noop_total 16471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33300
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.709788
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33300
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 339
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1180255
telemt_user_connections_current{user="hello"} 3792
telemt_user_octets_from_client{user="hello"} 21204714320 (19.75 GB)
telemt_user_octets_to_client{user="hello"} 545393281316 (507.94 GB)
telemt_user_unique_ips_current{user="hello"} 1288
telemt_user_unique_ips_recent_window{user="hello"} 482
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 40996.8 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1448087
telemt_connections_bad_total 108020
telemt_connections_current 3256
telemt_connections_me_current 3256
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 37481
telemt_upstream_connect_attempt_total 26676
telemt_upstream_connect_success_total 26484
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 2661
telemt_me_reconnect_success_total 493
telemt_me_reader_eof_total 426
telemt_me_idle_close_by_peer_total 426
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 349323
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1152535
telemt_me_endpoint_quarantine_total 390
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 327
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
telemt_desync_total 4619
telemt_desync_full_logged_total 1471
telemt_desync_suppressed_total 3148
telemt_desync_frames_bucket_total{bucket="1_2"} 1301
telemt_desync_frames_bucket_total{bucket="3_10"} 1689
telemt_desync_frames_bucket_total{bucket="gt_10"} 1629
telemt_pool_swap_total 45
telemt_pool_force_close_total 1046
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 15560
telemt_me_writer_removed_unexpected_total 437
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1371
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14649
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14514
telemt_me_writer_teardown_success_total{mode="normal"} 16020
telemt_me_writer_teardown_noop_total 15560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31580
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.041915
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31580
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 123
telemt_me_writer_restored_same_endpoint_total 369
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 41
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 1156955
telemt_user_connections_current{user="hello"} 3256
telemt_user_octets_from_client{user="hello"} 15697775027 (14.62 GB)
telemt_user_octets_to_client{user="hello"} 513734983267 (478.45 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1216
telemt_user_unique_ips_recent_window{user="hello"} 473
```