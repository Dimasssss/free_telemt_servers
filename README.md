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

# Server Metrics 2026-03-21 10:22:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 49582.3 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1427621
telemt_connections_bad_total 73901
telemt_connections_current 1630
telemt_connections_me_current 1630
telemt_handshake_timeouts_total 57733
telemt_upstream_connect_attempt_total 19526
telemt_upstream_connect_success_total 19441
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 19501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 910
telemt_me_reconnect_success_total 380
telemt_me_reader_eof_total 393
telemt_me_idle_close_by_peer_total 393
telemt_me_route_drop_no_conn_total 773872
telemt_me_route_drop_channel_closed_total 294
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1085748
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 343
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 393
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 27
telemt_desync_total 4576
telemt_desync_full_logged_total 1592
telemt_desync_suppressed_total 2984
telemt_desync_frames_bucket_total{bucket="1_2"} 955
telemt_desync_frames_bucket_total{bucket="3_10"} 1773
telemt_desync_frames_bucket_total{bucket="gt_10"} 1848
telemt_pool_swap_total 53
telemt_pool_force_close_total 1511
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 240
telemt_me_draining_writers_reap_progress_total 17454
telemt_me_writer_removed_unexpected_total 371
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16334
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1458
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15943
telemt_me_writer_teardown_success_total{mode="normal"} 17721
telemt_me_writer_teardown_noop_total 17456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35177
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 91.306660
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35177
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 240
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 339
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1084926
telemt_user_connections_current{user="hello"} 1630
telemt_user_octets_from_client{user="hello"} 15245527843 (14.20 GB)
telemt_user_octets_to_client{user="hello"} 309521420239 (288.26 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 585
telemt_user_unique_ips_recent_window{user="hello"} 231
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 49583.2 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3652570
telemt_connections_bad_total 376553
telemt_connections_current 4671
telemt_connections_me_current 4671
telemt_handshake_timeouts_total 105785
telemt_upstream_connect_attempt_total 17711
telemt_upstream_connect_success_total 17627
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 1094
telemt_me_reconnect_success_total 407
telemt_me_reader_eof_total 400
telemt_me_idle_close_by_peer_total 399
telemt_me_route_drop_no_conn_total 1591044
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2490246
telemt_me_endpoint_quarantine_total 312
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 379
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
telemt_me_writers_warm_current 32
telemt_desync_total 10750
telemt_desync_full_logged_total 3609
telemt_desync_suppressed_total 7141
telemt_desync_frames_bucket_total{bucket="1_2"} 2193
telemt_desync_frames_bucket_total{bucket="3_10"} 4240
telemt_desync_frames_bucket_total{bucket="gt_10"} 4317
telemt_pool_swap_total 53
telemt_pool_force_close_total 1626
telemt_me_writer_close_signal_drop_total 198
telemt_me_draining_writers_reap_progress_total 15805
telemt_me_writer_removed_unexpected_total 374
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1471
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14694
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1529
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 97
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14179
telemt_me_writer_teardown_success_total{mode="normal"} 16165
telemt_me_writer_teardown_noop_total 15805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31970
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.067853
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31970
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 198
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 325
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2485684
telemt_user_connections_current{user="hello"} 4671
telemt_user_octets_from_client{user="hello"} 34780857848 (32.39 GB)
telemt_user_octets_to_client{user="hello"} 837517665384 (780.00 GB)
telemt_user_unique_ips_current{user="hello"} 1763
telemt_user_unique_ips_recent_window{user="hello"} 635
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 49579.7 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2699422
telemt_connections_bad_total 313556
telemt_connections_current 4224
telemt_connections_me_current 4224
telemt_handshake_timeouts_total 100595
telemt_upstream_connect_attempt_total 19146
telemt_upstream_connect_success_total 19133
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 19134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 629
telemt_me_reconnect_success_total 358
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 1105047
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2119912
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 385
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
telemt_me_writers_warm_current 31
telemt_desync_total 9229
telemt_desync_full_logged_total 3171
telemt_desync_suppressed_total 6058
telemt_desync_frames_bucket_total{bucket="1_2"} 1916
telemt_desync_frames_bucket_total{bucket="3_10"} 3672
telemt_desync_frames_bucket_total{bucket="gt_10"} 3641
telemt_pool_swap_total 53
telemt_pool_force_close_total 1595
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 216
telemt_me_draining_writers_reap_progress_total 17390
telemt_me_writer_removed_unexpected_total 351
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1425
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16198
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1509
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15795
telemt_me_writer_teardown_success_total{mode="normal"} 17623
telemt_me_writer_teardown_noop_total 17402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35025
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 39.617383
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35025
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 216
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 321
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 2116682
telemt_user_connections_current{user="hello"} 4224
telemt_user_octets_from_client{user="hello"} 34028945084 (31.69 GB)
telemt_user_octets_to_client{user="hello"} 797152823308 (742.41 GB)
telemt_user_unique_ips_current{user="hello"} 1619
telemt_user_unique_ips_recent_window{user="hello"} 569
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 49581.2 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2225689
telemt_connections_bad_total 248998
telemt_connections_current 3556
telemt_connections_me_current 3556
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 94569
telemt_upstream_connect_attempt_total 24138
telemt_upstream_connect_success_total 23893
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 24020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10792
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 408
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1023
telemt_me_reconnect_success_total 449
telemt_me_reader_eof_total 417
telemt_me_idle_close_by_peer_total 417
telemt_me_route_drop_no_conn_total 654016
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1558769
telemt_me_endpoint_quarantine_total 339
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 25
telemt_desync_total 7230
telemt_desync_full_logged_total 2488
telemt_desync_suppressed_total 4742
telemt_desync_frames_bucket_total{bucket="1_2"} 1803
telemt_desync_frames_bucket_total{bucket="3_10"} 2854
telemt_desync_frames_bucket_total{bucket="gt_10"} 2573
telemt_pool_swap_total 53
telemt_pool_force_close_total 1446
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 98
telemt_me_draining_writers_reap_progress_total 17274
telemt_me_writer_removed_unexpected_total 410
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1397
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16301
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1363
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15828
telemt_me_writer_teardown_success_total{mode="normal"} 17698
telemt_me_writer_teardown_noop_total 17275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34973
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.689598
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34973
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 98
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 379
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1560649
telemt_user_connections_current{user="hello"} 3556
telemt_user_octets_from_client{user="hello"} 31013825921 (28.88 GB)
telemt_user_octets_to_client{user="hello"} 750395578919 (698.86 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1296
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 49544.7 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2165505
telemt_connections_bad_total 243766
telemt_connections_current 3230
telemt_connections_me_current 3230
telemt_handshake_timeouts_total 66716
telemt_upstream_connect_attempt_total 20513
telemt_upstream_connect_success_total 20467
telemt_upstream_connect_attempts_per_request{bucket="1"} 20467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11169
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 684
telemt_me_reconnect_success_total 468
telemt_me_reader_eof_total 431
telemt_me_idle_close_by_peer_total 431
telemt_me_route_drop_no_conn_total 605951
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1554969
telemt_me_endpoint_quarantine_total 373
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 377
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
telemt_me_writers_warm_current 11
telemt_desync_total 7374
telemt_desync_full_logged_total 2519
telemt_desync_suppressed_total 4855
telemt_desync_frames_bucket_total{bucket="1_2"} 1958
telemt_desync_frames_bucket_total{bucket="3_10"} 2822
telemt_desync_frames_bucket_total{bucket="gt_10"} 2594
telemt_pool_swap_total 52
telemt_pool_force_close_total 1428
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 136
telemt_me_draining_writers_reap_progress_total 18397
telemt_me_writer_removed_unexpected_total 406
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1410
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17424
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 109
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16969
telemt_me_writer_teardown_success_total{mode="normal"} 18834
telemt_me_writer_teardown_noop_total 18400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37234
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.282947
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37234
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 136
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 418
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1552490
telemt_user_connections_current{user="hello"} 3230
telemt_user_octets_from_client{user="hello"} 36532768324 (34.02 GB)
telemt_user_octets_to_client{user="hello"} 761078811488 (708.81 GB)
telemt_user_unique_ips_current{user="hello"} 1329
telemt_user_unique_ips_recent_window{user="hello"} 482
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 49584.2 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6562298
telemt_connections_bad_total 373177
telemt_connections_current 5289
telemt_connections_me_current 5289
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 245573
telemt_upstream_connect_attempt_total 59568
telemt_upstream_connect_success_total 56950
telemt_upstream_connect_fail_total 1924
telemt_upstream_connect_attempts_per_request{bucket="1"} 58874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2021
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1924
telemt_me_keepalive_timeout_total 57
telemt_me_reconnect_attempts_total 2916
telemt_me_reconnect_success_total 998
telemt_me_reader_eof_total 698
telemt_me_idle_close_by_peer_total 697
telemt_me_route_drop_no_conn_total 10943897
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5520829
telemt_me_endpoint_quarantine_total 386
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 116
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 116
telemt_me_single_endpoint_shadow_rotate_total 390
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_warm_current 29
telemt_desync_total 10916
telemt_desync_full_logged_total 3526
telemt_desync_suppressed_total 7390
telemt_desync_frames_bucket_total{bucket="1_2"} 2394
telemt_desync_frames_bucket_total{bucket="3_10"} 4755
telemt_desync_frames_bucket_total{bucket="gt_10"} 3767
telemt_pool_swap_total 50
telemt_pool_force_close_total 1556
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 314
telemt_me_draining_writers_reap_progress_total 16611
telemt_me_writer_removed_unexpected_total 963
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2109
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15394
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1340
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 216
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15055
telemt_me_writer_teardown_success_total{mode="normal"} 17503
telemt_me_writer_teardown_noop_total 16618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34121
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 40.401330
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34121
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 314
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 691
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 5555258
telemt_user_connections_current{user="hello"} 5289
telemt_user_octets_from_client{user="hello"} 50290932616 (46.84 GB)
telemt_user_octets_to_client{user="hello"} 598024343275 (556.95 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1861
telemt_user_unique_ips_recent_window{user="hello"} 982
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 49551.7 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2170063
telemt_connections_bad_total 266543
telemt_connections_current 3590
telemt_connections_me_current 3590
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 41689
telemt_upstream_connect_attempt_total 21895
telemt_upstream_connect_success_total 21674
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 21875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_reconnect_attempts_total 2095
telemt_me_reconnect_success_total 684
telemt_me_reader_eof_total 698
telemt_me_idle_close_by_peer_total 698
telemt_me_route_drop_no_conn_total 731679
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1642304
telemt_me_endpoint_quarantine_total 299
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 382
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
telemt_me_writers_active_current 83
telemt_me_writers_warm_current 5
telemt_desync_total 7524
telemt_desync_full_logged_total 2740
telemt_desync_suppressed_total 4784
telemt_desync_frames_bucket_total{bucket="1_2"} 1415
telemt_desync_frames_bucket_total{bucket="3_10"} 3055
telemt_desync_frames_bucket_total{bucket="gt_10"} 3054
telemt_pool_swap_total 50
telemt_pool_force_close_total 1335
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 101
telemt_me_draining_writers_reap_progress_total 18127
telemt_me_writer_removed_unexpected_total 675
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1664
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17161
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1225
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16792
telemt_me_writer_teardown_success_total{mode="normal"} 18825
telemt_me_writer_teardown_noop_total 18127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36952
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.614429
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36952
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 101
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 587
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 1630696
telemt_user_connections_current{user="hello"} 3590
telemt_user_octets_from_client{user="hello"} 29507242968 (27.48 GB)
telemt_user_octets_to_client{user="hello"} 749341939926 (697.88 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1513
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 49546.3 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3109959
telemt_connections_bad_total 171337
telemt_connections_current 3208
telemt_connections_me_current 3208
telemt_handshake_timeouts_total 1294556
telemt_upstream_connect_attempt_total 20374
telemt_upstream_connect_success_total 20340
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 282
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 543
telemt_me_reconnect_success_total 306
telemt_me_reader_eof_total 309
telemt_me_idle_close_by_peer_total 309
telemt_me_route_drop_no_conn_total 582023
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1462170
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_shadow_rotate_total 387
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
telemt_me_writers_warm_current 17
telemt_desync_total 7219
telemt_desync_full_logged_total 2549
telemt_desync_suppressed_total 4670
telemt_desync_frames_bucket_total{bucket="1_2"} 1285
telemt_desync_frames_bucket_total{bucket="3_10"} 2871
telemt_desync_frames_bucket_total{bucket="gt_10"} 3063
telemt_pool_swap_total 54
telemt_pool_force_close_total 1320
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 18247
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1160
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17405
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1302
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16927
telemt_me_writer_teardown_success_total{mode="normal"} 18565
telemt_me_writer_teardown_noop_total 18247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36812
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.953599
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36812
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 273
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1457756
telemt_user_connections_current{user="hello"} 3208
telemt_user_octets_from_client{user="hello"} 26095863120 (24.30 GB)
telemt_user_octets_to_client{user="hello"} 716685344100 (667.47 GB)
telemt_user_unique_ips_current{user="hello"} 1247
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 47537.9 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 648492
telemt_connections_bad_total 22181
telemt_connections_current 617
telemt_connections_me_current 617
telemt_handshake_timeouts_total 241754
telemt_upstream_connect_attempt_total 23098
telemt_upstream_connect_success_total 23096
telemt_upstream_connect_attempts_per_request{bucket="1"} 23096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1026
telemt_me_reconnect_success_total 375
telemt_me_reader_eof_total 376
telemt_me_idle_close_by_peer_total 376
telemt_me_route_drop_no_conn_total 138068
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334420
telemt_me_endpoint_quarantine_total 452
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 406
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
telemt_me_writers_active_current 45
telemt_desync_total 2179
telemt_desync_full_logged_total 866
telemt_desync_suppressed_total 1313
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 820
telemt_desync_frames_bucket_total{bucket="gt_10"} 981
telemt_pool_swap_total 52
telemt_pool_force_close_total 1137
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 20662
telemt_me_writer_removed_unexpected_total 357
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1502
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19521
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1134
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19525
telemt_me_writer_teardown_success_total{mode="normal"} 21023
telemt_me_writer_teardown_noop_total 20662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.200868
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 305
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 334556
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 4975563099 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 129460263137 (120.57 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 49556.2 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2291027
telemt_connections_bad_total 211172
telemt_connections_current 4013
telemt_connections_me_current 4013
telemt_handshake_timeouts_total 56371
telemt_upstream_connect_attempt_total 21183
telemt_upstream_connect_success_total 21091
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 21153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 832
telemt_me_reconnect_success_total 474
telemt_me_reader_eof_total 436
telemt_me_idle_close_by_peer_total 436
telemt_me_route_drop_no_conn_total 594465
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1806710
telemt_me_endpoint_quarantine_total 390
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 388
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
telemt_me_writers_active_current 49
telemt_me_writers_warm_current 16
telemt_desync_total 7078
telemt_desync_full_logged_total 2368
telemt_desync_suppressed_total 4710
telemt_desync_frames_bucket_total{bucket="1_2"} 1711
telemt_desync_frames_bucket_total{bucket="3_10"} 2657
telemt_desync_frames_bucket_total{bucket="gt_10"} 2710
telemt_pool_swap_total 54
telemt_pool_force_close_total 1342
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 19034
telemt_me_writer_removed_unexpected_total 432
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1429
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18049
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17692
telemt_me_writer_teardown_success_total{mode="normal"} 19478
telemt_me_writer_teardown_noop_total 19034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38512
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.764803
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38512
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 423
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 1800727
telemt_user_connections_current{user="hello"} 4013
telemt_user_octets_from_client{user="hello"} 39681524144 (36.96 GB)
telemt_user_octets_to_client{user="hello"} 848128802792 (789.88 GB)
telemt_user_unique_ips_current{user="hello"} 1502
telemt_user_unique_ips_recent_window{user="hello"} 516
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 49556.1 (13h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2116536
telemt_connections_bad_total 172823
telemt_connections_current 3752
telemt_connections_me_current 3752
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 51767
telemt_upstream_connect_attempt_total 29733
telemt_upstream_connect_success_total 29517
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 29690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_reconnect_attempts_total 3034
telemt_me_reconnect_success_total 612
telemt_me_reader_eof_total 539
telemt_me_idle_close_by_peer_total 539
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 591168
telemt_me_route_drop_channel_closed_total 35
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1707338
telemt_me_endpoint_quarantine_total 430
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 384
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
telemt_desync_total 6517
telemt_desync_full_logged_total 2203
telemt_desync_suppressed_total 4314
telemt_desync_frames_bucket_total{bucket="1_2"} 1748
telemt_desync_frames_bucket_total{bucket="3_10"} 2419
telemt_desync_frames_bucket_total{bucket="gt_10"} 2350
telemt_pool_swap_total 53
telemt_pool_force_close_total 1319
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 18239
telemt_me_writer_removed_unexpected_total 549
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1662
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17152
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16920
telemt_me_writer_teardown_success_total{mode="normal"} 18814
telemt_me_writer_teardown_noop_total 18240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37054
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.511941
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37054
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 474
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 1710929
telemt_user_connections_current{user="hello"} 3752
telemt_user_octets_from_client{user="hello"} 28604203127 (26.64 GB)
telemt_user_octets_to_client{user="hello"} 764319276931 (711.83 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1416
telemt_user_unique_ips_recent_window{user="hello"} 507
```