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

# Server Metrics 2026-03-21 15:28:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 67948.3 (18h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2401689
telemt_connections_bad_total 121161
telemt_connections_current 1354
telemt_connections_me_current 1354
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 77773
telemt_upstream_connect_attempt_total 29000
telemt_upstream_connect_success_total 28873
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 28957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16793
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1650
telemt_me_reconnect_success_total 662
telemt_me_reader_eof_total 635
telemt_me_idle_close_by_peer_total 635
telemt_me_route_drop_no_conn_total 2107344
telemt_me_route_drop_channel_closed_total 640
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1925989
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 476
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 532
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
telemt_me_writers_active_current 45
telemt_desync_total 7512
telemt_desync_full_logged_total 2600
telemt_desync_suppressed_total 4912
telemt_desync_frames_bucket_total{bucket="1_2"} 1648
telemt_desync_frames_bucket_total{bucket="3_10"} 2859
telemt_desync_frames_bucket_total{bucket="gt_10"} 3005
telemt_pool_swap_total 73
telemt_pool_force_close_total 2212
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 23225
telemt_me_writer_removed_unexpected_total 613
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21632
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2096
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21013
telemt_me_writer_teardown_success_total{mode="normal"} 23622
telemt_me_writer_teardown_noop_total 23231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46853
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 220.829661
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46853
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 567
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1927474
telemt_user_connections_current{user="hello"} 1354
telemt_user_octets_from_client{user="hello"} 27116024785 (25.25 GB)
telemt_user_octets_to_client{user="hello"} 474716356866 (442.11 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 341.4 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11363
telemt_connections_bad_total 486
telemt_connections_current 1052
telemt_connections_me_current 1052
telemt_handshake_timeouts_total 274
telemt_upstream_connect_attempt_total 204
telemt_upstream_connect_success_total 201
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 3887
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9895
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
telemt_desync_total 17
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_draining_writers_reap_progress_total 117
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 114
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 117
telemt_me_writer_teardown_success_total{mode="normal"} 117
telemt_me_writer_teardown_noop_total 117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 234
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.012316
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 234
telemt_user_connections_total{user="hello"} 9893
telemt_user_connections_current{user="hello"} 1052
telemt_user_octets_from_client{user="hello"} 97870928 (93.34 MB)
telemt_user_octets_to_client{user="hello"} 2602521616 (2.42 GB)
telemt_user_unique_ips_current{user="hello"} 625
telemt_user_unique_ips_recent_window{user="hello"} 921
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 67945.1 (18h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4800971
telemt_connections_bad_total 429964
telemt_connections_current 5312
telemt_connections_me_current 5312
telemt_handshake_timeouts_total 171781
telemt_upstream_connect_attempt_total 25191
telemt_upstream_connect_success_total 25138
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 25143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1150
telemt_me_reconnect_success_total 577
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_route_drop_no_conn_total 2670977
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3924660
telemt_me_endpoint_quarantine_total 428
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 514
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
telemt_desync_total 16043
telemt_desync_full_logged_total 5403
telemt_desync_suppressed_total 10640
telemt_desync_frames_bucket_total{bucket="1_2"} 3418
telemt_desync_frames_bucket_total{bucket="3_10"} 6319
telemt_desync_frames_bucket_total{bucket="gt_10"} 6306
telemt_pool_swap_total 72
telemt_pool_force_close_total 2342
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 22854
telemt_me_writer_removed_unexpected_total 562
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2005
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21180
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2144
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 198
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20512
telemt_me_writer_teardown_success_total{mode="normal"} 23185
telemt_me_writer_teardown_noop_total 22886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46071
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 80.956600
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46071
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 519
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 3919870
telemt_user_connections_current{user="hello"} 5312
telemt_user_octets_from_client{user="hello"} 63122503308 (58.79 GB)
telemt_user_octets_to_client{user="hello"} 1293073342532 (1.18 TB)
telemt_user_unique_ips_current{user="hello"} 1998
telemt_user_unique_ips_recent_window{user="hello"} 977
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 67947.0 (18h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3893307
telemt_connections_bad_total 420047
telemt_connections_current 3914
telemt_connections_me_current 3914
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 139251
telemt_upstream_connect_attempt_total 29610
telemt_upstream_connect_success_total 29329
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 29468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 485
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1379
telemt_me_reconnect_success_total 600
telemt_me_reader_eof_total 560
telemt_me_idle_close_by_peer_total 560
telemt_me_route_drop_no_conn_total 1225145
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2854580
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 518
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
telemt_me_writers_active_current 44
telemt_desync_total 13275
telemt_desync_full_logged_total 4460
telemt_desync_suppressed_total 8815
telemt_desync_frames_bucket_total{bucket="1_2"} 3345
telemt_desync_frames_bucket_total{bucket="3_10"} 5113
telemt_desync_frames_bucket_total{bucket="gt_10"} 4817
telemt_pool_swap_total 74
telemt_pool_force_close_total 2140
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 212
telemt_me_draining_writers_reap_progress_total 22072
telemt_me_writer_removed_unexpected_total 544
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1904
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20714
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1987
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 153
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19932
telemt_me_writer_teardown_success_total{mode="normal"} 22618
telemt_me_writer_teardown_noop_total 22073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44691
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.929253
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44691
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 212
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 504
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2854262
telemt_user_connections_current{user="hello"} 3914
telemt_user_octets_from_client{user="hello"} 54106169057 (50.39 GB)
telemt_user_octets_to_client{user="hello"} 1329135651639 (1.21 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1521
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 67910.8 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3825887
telemt_connections_bad_total 395151
telemt_connections_current 3571
telemt_connections_me_current 3571
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 115426
telemt_upstream_connect_attempt_total 34875
telemt_upstream_connect_success_total 34640
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 854
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1387
telemt_me_reconnect_success_total 653
telemt_me_reader_eof_total 594
telemt_me_idle_close_by_peer_total 594
telemt_me_route_drop_no_conn_total 1331833
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2841031
telemt_me_endpoint_quarantine_total 483
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 509
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
telemt_desync_total 13041
telemt_desync_full_logged_total 4340
telemt_desync_suppressed_total 8701
telemt_desync_frames_bucket_total{bucket="1_2"} 3267
telemt_desync_frames_bucket_total{bucket="3_10"} 4887
telemt_desync_frames_bucket_total{bucket="gt_10"} 4887
telemt_pool_swap_total 72
telemt_pool_force_close_total 2067
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 235
telemt_me_draining_writers_reap_progress_total 23511
telemt_me_writer_removed_unexpected_total 565
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1985
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22128
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1887
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 180
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21444
telemt_me_writer_teardown_success_total{mode="normal"} 24113
telemt_me_writer_teardown_noop_total 23517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47630
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.699952
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47630
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 235
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 563
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2844885
telemt_user_connections_current{user="hello"} 3571
telemt_user_octets_from_client{user="hello"} 60369481565 (56.22 GB)
telemt_user_octets_to_client{user="hello"} 1317721422708 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1377
telemt_user_unique_ips_recent_window{user="hello"} 565
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 67950.3 (18h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13134985
telemt_connections_bad_total 852767
telemt_connections_current 5607
telemt_connections_me_current 5607
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 399106
telemt_upstream_connect_attempt_total 116026
telemt_upstream_connect_success_total 106132
telemt_upstream_connect_fail_total 8852
telemt_upstream_connect_attempts_per_request{bucket="1"} 114984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25602
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8852
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3868
telemt_me_reconnect_success_total 1411
telemt_me_reader_eof_total 980
telemt_me_idle_close_by_peer_total 979
telemt_me_route_drop_no_conn_total 25433649
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10797470
telemt_me_endpoint_quarantine_total 523
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 530
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 19152
telemt_desync_full_logged_total 5984
telemt_desync_suppressed_total 13168
telemt_desync_frames_bucket_total{bucket="1_2"} 4146
telemt_desync_frames_bucket_total{bucket="3_10"} 8438
telemt_desync_frames_bucket_total{bucket="gt_10"} 6568
telemt_pool_swap_total 69
telemt_pool_force_close_total 2247
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 493
telemt_me_draining_writers_reap_progress_total 21805
telemt_me_writer_removed_unexpected_total 1342
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2881
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20057
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1881
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 366
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19558
telemt_me_writer_teardown_success_total{mode="normal"} 22938
telemt_me_writer_teardown_noop_total 21817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44755
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 172.075920
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44755
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 493
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 985
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 10872704
telemt_user_connections_current{user="hello"} 5607
telemt_user_octets_from_client{user="hello"} 77105552793 (71.81 GB)
telemt_user_octets_to_client{user="hello"} 801596480349 (746.54 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2059
telemt_user_unique_ips_recent_window{user="hello"} 967
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 67917.6 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3839900
telemt_connections_bad_total 423880
telemt_connections_current 4210
telemt_connections_me_current 4210
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 83000
telemt_upstream_connect_attempt_total 28517
telemt_upstream_connect_success_total 28207
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 28473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14676
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_reconnect_attempts_total 2718
telemt_me_reconnect_success_total 981
telemt_me_reader_eof_total 978
telemt_me_idle_close_by_peer_total 978
telemt_me_route_drop_no_conn_total 1623371
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2962064
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 510
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
telemt_me_writers_active_current 42
telemt_desync_total 13950
telemt_desync_full_logged_total 4872
telemt_desync_suppressed_total 9078
telemt_desync_frames_bucket_total{bucket="1_2"} 2725
telemt_desync_frames_bucket_total{bucket="3_10"} 5518
telemt_desync_frames_bucket_total{bucket="gt_10"} 5707
telemt_pool_swap_total 68
telemt_pool_force_close_total 1980
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 200
telemt_me_draining_writers_reap_progress_total 23967
telemt_me_writer_removed_unexpected_total 948
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2367
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22581
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1722
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21987
telemt_me_writer_teardown_success_total{mode="normal"} 24948
telemt_me_writer_teardown_noop_total 23968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48916
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.413837
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48916
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 200
telemt_me_refill_failed_total 95
telemt_me_writer_restored_same_endpoint_total 842
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 2945568
telemt_user_connections_current{user="hello"} 4210
telemt_user_octets_from_client{user="hello"} 76691374472 (71.42 GB)
telemt_user_octets_to_client{user="hello"} 1223518234650 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1601
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 4753.2 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 765555
telemt_connections_bad_total 20617
telemt_connections_current 2943
telemt_connections_me_current 2943
telemt_handshake_timeouts_total 374357
telemt_upstream_connect_attempt_total 1786
telemt_upstream_connect_success_total 1748
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 1780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 246
telemt_me_reconnect_success_total 81
telemt_me_reader_eof_total 72
telemt_me_idle_close_by_peer_total 72
telemt_me_route_drop_no_conn_total 355427
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347633
telemt_me_endpoint_quarantine_total 21
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 40
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
telemt_me_writers_active_current 43
telemt_desync_total 1593
telemt_desync_full_logged_total 530
telemt_desync_suppressed_total 1063
telemt_desync_frames_bucket_total{bucket="1_2"} 268
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 707
telemt_pool_swap_total 4
telemt_pool_force_close_total 143
telemt_me_writer_close_signal_drop_total 11
telemt_me_draining_writers_reap_progress_total 1465
telemt_me_writer_removed_unexpected_total 73
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 159
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1379
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 105
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1322
telemt_me_writer_teardown_success_total{mode="normal"} 1538
telemt_me_writer_teardown_noop_total 1465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3003
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.748747
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3003
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 11
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 70
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 347116
telemt_user_connections_current{user="hello"} 2943
telemt_user_octets_from_client{user="hello"} 10092961560 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 124698216452 (116.13 GB)
telemt_user_unique_ips_current{user="hello"} 1152
telemt_user_unique_ips_recent_window{user="hello"} 493
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 65903.6 (18h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1227156
telemt_connections_bad_total 138397
telemt_connections_current 836
telemt_connections_me_current 836
telemt_handshake_timeouts_total 438581
telemt_upstream_connect_attempt_total 30889
telemt_upstream_connect_success_total 30881
telemt_upstream_connect_attempts_per_request{bucket="1"} 30881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1315
telemt_me_reconnect_success_total 547
telemt_me_reader_eof_total 547
telemt_me_idle_close_by_peer_total 547
telemt_me_route_drop_no_conn_total 267774
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 575248
telemt_me_endpoint_quarantine_total 589
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 551
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
telemt_desync_total 3574
telemt_desync_full_logged_total 1302
telemt_desync_suppressed_total 2272
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 1282
telemt_desync_frames_bucket_total{bucket="gt_10"} 1633
telemt_pool_swap_total 72
telemt_pool_force_close_total 1683
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 112
telemt_me_draining_writers_reap_progress_total 27684
telemt_me_writer_removed_unexpected_total 518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2093
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26124
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1654
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26001
telemt_me_writer_teardown_success_total{mode="normal"} 28217
telemt_me_writer_teardown_noop_total 27684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55901
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.345527
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55901
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 112
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 456
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 574889
telemt_user_connections_current{user="hello"} 836
telemt_user_octets_from_client{user="hello"} 11802417911 (10.99 GB)
telemt_user_octets_to_client{user="hello"} 219148936957 (204.10 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 67922.0 (18h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4213181
telemt_connections_bad_total 379931
telemt_connections_current 4947
telemt_connections_me_current 4947
telemt_handshake_timeouts_total 139030
telemt_upstream_connect_attempt_total 27041
telemt_upstream_connect_success_total 26928
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 27006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13555
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 1183
telemt_me_reconnect_success_total 613
telemt_me_reader_eof_total 580
telemt_me_idle_close_by_peer_total 580
telemt_me_route_drop_no_conn_total 1279557
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3356707
telemt_me_endpoint_quarantine_total 495
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 521
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 13118
telemt_desync_full_logged_total 4338
telemt_desync_suppressed_total 8780
telemt_desync_frames_bucket_total{bucket="1_2"} 3094
telemt_desync_frames_bucket_total{bucket="3_10"} 4890
telemt_desync_frames_bucket_total{bucket="gt_10"} 5134
telemt_pool_swap_total 75
telemt_pool_force_close_total 1970
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 223
telemt_me_draining_writers_reap_progress_total 24257
telemt_me_writer_removed_unexpected_total 568
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1937
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22890
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1924
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22287
telemt_me_writer_teardown_success_total{mode="normal"} 24827
telemt_me_writer_teardown_noop_total 24257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49084
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.892958
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49084
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 223
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 542
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3348304
telemt_user_connections_current{user="hello"} 4947
telemt_user_octets_from_client{user="hello"} 68378913756 (63.68 GB)
telemt_user_octets_to_client{user="hello"} 1575679634476 (1.43 TB)
telemt_user_unique_ips_current{user="hello"} 1677
telemt_user_unique_ips_recent_window{user="hello"} 602
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 67918.9 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3757973
telemt_connections_bad_total 336246
telemt_connections_current 3821
telemt_connections_me_current 3821
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 114576
telemt_upstream_connect_attempt_total 43553
telemt_upstream_connect_success_total 43258
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 43502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15429
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 601
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_reconnect_attempts_total 3838
telemt_me_reconnect_success_total 845
telemt_me_reader_eof_total 742
telemt_me_idle_close_by_peer_total 742
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1361416
telemt_me_route_drop_channel_closed_total 101
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3013868
telemt_me_endpoint_quarantine_total 564
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 518
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 11830
telemt_desync_full_logged_total 4013
telemt_desync_suppressed_total 7817
telemt_desync_frames_bucket_total{bucket="1_2"} 2954
telemt_desync_frames_bucket_total{bucket="3_10"} 4403
telemt_desync_frames_bucket_total{bucket="gt_10"} 4473
telemt_pool_swap_total 73
telemt_pool_force_close_total 1907
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 214
telemt_me_draining_writers_reap_progress_total 23686
telemt_me_writer_removed_unexpected_total 754
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2311
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22161
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1750
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21779
telemt_me_writer_teardown_success_total{mode="normal"} 24472
telemt_me_writer_teardown_noop_total 23687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48159
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.058135
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48159
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 214
telemt_me_refill_failed_total 170
telemt_me_writer_restored_same_endpoint_total 657
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 57
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 3022315
telemt_user_connections_current{user="hello"} 3821
telemt_user_octets_from_client{user="hello"} 54280217109 (50.55 GB)
telemt_user_octets_to_client{user="hello"} 1294311631108 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1448
telemt_user_unique_ips_recent_window{user="hello"} 506
```