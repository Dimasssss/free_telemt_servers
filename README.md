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

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
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
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
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

# Server Metrics 2026-03-22 10:20:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 47666.2 (13h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1258406
telemt_connections_bad_total 66269
telemt_connections_current 1773
telemt_connections_me_current 1773
telemt_handshake_timeouts_total 58060
telemt_upstream_connect_attempt_total 18459
telemt_upstream_connect_success_total 18458
telemt_upstream_connect_attempts_per_request{bucket="1"} 18458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 555
telemt_me_reconnect_success_total 285
telemt_me_reader_eof_total 285
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 694045
telemt_me_route_drop_channel_closed_total 314
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1050277
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 330
telemt_me_single_endpoint_shadow_rotate_total 380
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
telemt_me_writers_active_current 47
telemt_desync_total 7051
telemt_desync_full_logged_total 2058
telemt_desync_suppressed_total 4993
telemt_desync_frames_bucket_total{bucket="1_2"} 2058
telemt_desync_frames_bucket_total{bucket="3_10"} 2666
telemt_desync_frames_bucket_total{bucket="gt_10"} 2327
telemt_pool_swap_total 52
telemt_pool_force_close_total 1516
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 196
telemt_me_draining_writers_reap_progress_total 16803
telemt_me_writer_removed_unexpected_total 281
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1158
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15845
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1484
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15287
telemt_me_writer_teardown_success_total{mode="normal"} 17003
telemt_me_writer_teardown_noop_total 16805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33808
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 83.617567
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33808
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 196
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 261
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1048429
telemt_user_connections_current{user="hello"} 1773
telemt_user_octets_from_client{user="hello"} 16722002832 (15.57 GB)
telemt_user_octets_to_client{user="hello"} 332668957540 (309.82 GB)
telemt_user_unique_ips_current{user="hello"} 660
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 61032.2 (16h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1996832
telemt_connections_bad_total 170685
telemt_connections_current 2078
telemt_connections_me_current 2078
telemt_handshake_timeouts_total 48905
telemt_upstream_connect_attempt_total 36123
telemt_upstream_connect_success_total 35642
telemt_upstream_connect_fail_total 421
telemt_upstream_connect_attempts_per_request{bucket="1"} 36063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 421
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3147
telemt_me_reconnect_success_total 1396
telemt_me_reader_eof_total 1289
telemt_me_idle_close_by_peer_total 1289
telemt_me_route_drop_no_conn_total 1393011
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1556297
telemt_me_endpoint_quarantine_total 520
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 482
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 6557
telemt_desync_full_logged_total 3721
telemt_desync_suppressed_total 2836
telemt_desync_frames_bucket_total{bucket="1_2"} 1484
telemt_desync_frames_bucket_total{bucket="3_10"} 2562
telemt_desync_frames_bucket_total{bucket="gt_10"} 2511
telemt_pool_swap_total 61
telemt_pool_force_close_total 1725
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 24673
telemt_me_writer_removed_unexpected_total 1255
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2691
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23231
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1542
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22948
telemt_me_writer_teardown_success_total{mode="normal"} 25922
telemt_me_writer_teardown_noop_total 24673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50595
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.401668
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50595
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1165
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1562346
telemt_user_connections_current{user="hello"} 2078
telemt_user_octets_from_client{user="hello"} 21713781934 (20.22 GB)
telemt_user_octets_to_client{user="hello"} 449127744008 (418.28 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1240
telemt_user_unique_ips_recent_window{user="hello"} 889
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 135892.3 (37h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11107984
telemt_connections_bad_total 958597
telemt_connections_current 5917
telemt_connections_me_current 5917
telemt_handshake_timeouts_total 308928
telemt_upstream_connect_attempt_total 49692
telemt_upstream_connect_success_total 49612
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 49620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26977
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2131
telemt_me_reconnect_success_total 1093
telemt_me_reader_eof_total 1076
telemt_me_idle_close_by_peer_total 1075
telemt_me_route_drop_no_conn_total 7673785
telemt_me_route_drop_channel_closed_total 95
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8808097
telemt_me_endpoint_quarantine_total 869
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1012
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 37180
telemt_desync_full_logged_total 12058
telemt_desync_suppressed_total 25122
telemt_desync_frames_bucket_total{bucket="1_2"} 8371
telemt_desync_frames_bucket_total{bucket="3_10"} 14421
telemt_desync_frames_bucket_total{bucket="gt_10"} 14388
telemt_pool_swap_total 146
telemt_pool_force_close_total 4885
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 762
telemt_me_draining_writers_reap_progress_total 45303
telemt_me_writer_removed_unexpected_total 1034
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3868
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41919
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4553
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 332
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40418
telemt_me_writer_teardown_success_total{mode="normal"} 45787
telemt_me_writer_teardown_noop_total 45347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 205.592496
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 762
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 950
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 8797501
telemt_user_connections_current{user="hello"} 5917
telemt_user_octets_from_client{user="hello"} 138447292148 (128.94 GB)
telemt_user_octets_to_client{user="hello"} 2688387699708 (2.45 TB)
telemt_user_unique_ips_current{user="hello"} 2187
telemt_user_unique_ips_recent_window{user="hello"} 1092
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 135897.4 (37h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8758915
telemt_connections_bad_total 786451
telemt_connections_current 4704
telemt_connections_me_current 4704
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 270016
telemt_upstream_connect_attempt_total 55891
telemt_upstream_connect_success_total 55368
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 55621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 3030
telemt_me_reconnect_success_total 1189
telemt_me_reader_eof_total 1093
telemt_me_idle_close_by_peer_total 1093
telemt_me_route_drop_no_conn_total 3427840
telemt_me_route_drop_channel_closed_total 357
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6508283
telemt_me_endpoint_quarantine_total 860
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1043
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 29436
telemt_desync_full_logged_total 9981
telemt_desync_suppressed_total 19455
telemt_desync_frames_bucket_total{bucket="1_2"} 7109
telemt_desync_frames_bucket_total{bucket="3_10"} 11373
telemt_desync_frames_bucket_total{bucket="gt_10"} 10954
telemt_pool_swap_total 147
telemt_pool_force_close_total 4461
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 492
telemt_me_draining_writers_reap_progress_total 43659
telemt_me_writer_removed_unexpected_total 1109
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3770
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40893
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4156
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 305
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39198
telemt_me_writer_teardown_success_total{mode="normal"} 44663
telemt_me_writer_teardown_noop_total 43665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88328
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 64.302404
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88328
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 492
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1008
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6430219
telemt_user_connections_current{user="hello"} 4704
telemt_user_octets_from_client{user="hello"} 170443866911 (158.74 GB)
telemt_user_octets_to_client{user="hello"} 2990574436902 (2.72 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1858
telemt_user_unique_ips_recent_window{user="hello"} 751
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 135857.5 (37h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8327137
telemt_connections_bad_total 697796
telemt_connections_current 4259
telemt_connections_me_current 4259
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 269608
telemt_upstream_connect_attempt_total 60458
telemt_upstream_connect_success_total 59759
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 59906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28189
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3525
telemt_me_reconnect_success_total 1477
telemt_me_reader_eof_total 1359
telemt_me_idle_close_by_peer_total 1359
telemt_me_route_drop_no_conn_total 3498548
telemt_me_route_drop_channel_closed_total 232
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6234129
telemt_me_endpoint_quarantine_total 934
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 994
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_desync_total 28925
telemt_desync_full_logged_total 9835
telemt_desync_suppressed_total 19090
telemt_desync_frames_bucket_total{bucket="1_2"} 6983
telemt_desync_frames_bucket_total{bucket="3_10"} 11135
telemt_desync_frames_bucket_total{bucket="gt_10"} 10807
telemt_pool_swap_total 143
telemt_pool_force_close_total 4358
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 515
telemt_me_draining_writers_reap_progress_total 44615
telemt_me_writer_removed_unexpected_total 1386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4180
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41767
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3969
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40257
telemt_me_writer_teardown_success_total{mode="normal"} 45947
telemt_me_writer_teardown_noop_total 44632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90579
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.377185
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90579
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 515
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 1298
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 6226088
telemt_user_connections_current{user="hello"} 4259
telemt_user_octets_from_client{user="hello"} 155638942951 (144.95 GB)
telemt_user_octets_to_client{user="hello"} 2715785918791 (2.47 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1698
telemt_user_unique_ips_recent_window{user="hello"} 738
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 6138.0 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2623199
telemt_connections_bad_total 187907
telemt_connections_current 6961
telemt_connections_me_current 6961
telemt_handshake_timeouts_total 36152
telemt_upstream_connect_attempt_total 8831
telemt_upstream_connect_success_total 8367
telemt_upstream_connect_fail_total 342
telemt_upstream_connect_attempts_per_request{bucket="1"} 8709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2693
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 342
telemt_me_keepalive_timeout_total 298
telemt_me_reconnect_attempts_total 454
telemt_me_reconnect_success_total 170
telemt_me_reader_eof_total 121
telemt_me_idle_close_by_peer_total 121
telemt_me_route_drop_no_conn_total 5972422
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2184738
telemt_me_endpoint_quarantine_total 28
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 50
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
telemt_me_writers_active_current 88
telemt_desync_total 3381
telemt_desync_full_logged_total 862
telemt_desync_suppressed_total 2519
telemt_desync_frames_bucket_total{bucket="1_2"} 579
telemt_desync_frames_bucket_total{bucket="3_10"} 1333
telemt_desync_frames_bucket_total{bucket="gt_10"} 1469
telemt_pool_swap_total 4
telemt_pool_force_close_total 156
telemt_me_writer_close_signal_drop_total 69
telemt_me_draining_writers_reap_progress_total 1567
telemt_me_writer_removed_unexpected_total 165
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 272
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1461
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1411
telemt_me_writer_teardown_success_total{mode="normal"} 1733
telemt_me_writer_teardown_noop_total 1568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3301
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.540730
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3301
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 69
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 122
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2189928
telemt_user_connections_current{user="hello"} 6961
telemt_user_octets_from_client{user="hello"} 11696037286 (10.89 GB)
telemt_user_octets_to_client{user="hello"} 63804650051 (59.42 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2448
telemt_user_unique_ips_recent_window{user="hello"} 1520
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 135864.0 (37h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7967864
telemt_connections_bad_total 697009
telemt_connections_current 4431
telemt_connections_me_current 4431
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 162964
telemt_upstream_connect_attempt_total 76763
telemt_upstream_connect_success_total 75930
telemt_upstream_connect_fail_total 713
telemt_upstream_connect_attempts_per_request{bucket="1"} 76643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 713
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70595
telemt_me_reconnect_success_total 2152
telemt_me_reader_eof_total 1893
telemt_me_idle_close_by_peer_total 1892
telemt_me_route_drop_no_conn_total 3419362
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6293697
telemt_me_endpoint_quarantine_total 910
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 1021
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 31900
telemt_desync_full_logged_total 10999
telemt_desync_suppressed_total 20901
telemt_desync_frames_bucket_total{bucket="1_2"} 6481
telemt_desync_frames_bucket_total{bucket="3_10"} 12264
telemt_desync_frames_bucket_total{bucket="gt_10"} 13155
telemt_pool_swap_total 140
telemt_pool_force_close_total 4087
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 491
telemt_me_draining_writers_reap_progress_total 46963
telemt_me_writer_removed_unexpected_total 1922
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4818
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44094
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3568
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 519
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42876
telemt_me_writer_teardown_success_total{mode="normal"} 48912
telemt_me_writer_teardown_noop_total 46964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95876
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.855705
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95876
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 491
telemt_me_refill_failed_total 4233
telemt_me_writer_restored_same_endpoint_total 1791
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 6288807
telemt_user_connections_current{user="hello"} 4431
telemt_user_octets_from_client{user="hello"} 153849805647 (143.28 GB)
telemt_user_octets_to_client{user="hello"} 2525414194655 (2.30 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1708
telemt_user_unique_ips_recent_window{user="hello"} 772
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 72700.0 (20h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6905753
telemt_connections_bad_total 258327
telemt_connections_current 4892
telemt_connections_me_current 4892
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2811143
telemt_upstream_connect_attempt_total 38173
telemt_upstream_connect_success_total 37898
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 38166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_reconnect_attempts_total 47622
telemt_me_reconnect_success_total 1317
telemt_me_reader_eof_total 981
telemt_me_idle_close_by_peer_total 981
telemt_me_route_drop_no_conn_total 2061424
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3432668
telemt_me_endpoint_quarantine_total 493
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 554
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
telemt_me_writers_active_current 88
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 18355
telemt_desync_full_logged_total 6165
telemt_desync_suppressed_total 12190
telemt_desync_frames_bucket_total{bucket="1_2"} 3707
telemt_desync_frames_bucket_total{bucket="3_10"} 7032
telemt_desync_frames_bucket_total{bucket="gt_10"} 7616
telemt_pool_swap_total 76
telemt_pool_force_close_total 2310
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 222
telemt_me_draining_writers_reap_progress_total 25947
telemt_me_writer_removed_unexpected_total 1051
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2304
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24717
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1988
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23637
telemt_me_writer_teardown_success_total{mode="normal"} 27021
telemt_me_writer_teardown_noop_total 25953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52974
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.910619
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52974
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 222
telemt_me_refill_failed_total 2692
telemt_me_writer_restored_same_endpoint_total 1177
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3432403
telemt_user_connections_current{user="hello"} 4892
telemt_user_octets_from_client{user="hello"} 82630286084 (76.96 GB)
telemt_user_octets_to_client{user="hello"} 1415704979210 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1985
telemt_user_unique_ips_recent_window{user="hello"} 709
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 53670.8 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537796
telemt_connections_bad_total 3799
telemt_connections_current 1068
telemt_connections_me_current 1068
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10066
telemt_upstream_connect_attempt_total 28103
telemt_upstream_connect_success_total 28038
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 28096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 290
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1155
telemt_me_reconnect_success_total 462
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_route_drop_no_conn_total 175837
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486502
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 458
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
telemt_me_writers_active_current 45
telemt_desync_total 2405
telemt_desync_full_logged_total 689
telemt_desync_suppressed_total 1716
telemt_desync_frames_bucket_total{bucket="1_2"} 722
telemt_desync_frames_bucket_total{bucket="3_10"} 924
telemt_desync_frames_bucket_total{bucket="gt_10"} 759
telemt_pool_swap_total 57
telemt_pool_force_close_total 1354
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 22783
telemt_me_writer_removed_unexpected_total 443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1664
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21579
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21429
telemt_me_writer_teardown_success_total{mode="normal"} 23243
telemt_me_writer_teardown_noop_total 22783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46026
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.432391
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46026
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 408
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 488460
telemt_user_connections_current{user="hello"} 1068
telemt_user_octets_from_client{user="hello"} 9664267613 (9.00 GB)
telemt_user_octets_to_client{user="hello"} 235846845211 (219.65 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 135868.6 (37h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9736842
telemt_connections_bad_total 1135010
telemt_connections_current 5950
telemt_connections_me_current 5950
telemt_handshake_timeouts_total 262609
telemt_upstream_connect_attempt_total 52234
telemt_upstream_connect_success_total 52036
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 52188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 1985
telemt_me_reconnect_success_total 1075
telemt_me_reader_eof_total 1042
telemt_me_idle_close_by_peer_total 1042
telemt_me_route_drop_no_conn_total 2786071
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 28
telemt_me_route_drop_queue_full_profile_total{profile="high"} 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7246912
telemt_me_endpoint_quarantine_total 954
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1026
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 29453
telemt_desync_full_logged_total 9654
telemt_desync_suppressed_total 19799
telemt_desync_frames_bucket_total{bucket="1_2"} 7265
telemt_desync_frames_bucket_total{bucket="3_10"} 10770
telemt_desync_frames_bucket_total{bucket="gt_10"} 11418
telemt_pool_swap_total 150
telemt_pool_force_close_total 4056
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 47107
telemt_me_writer_removed_unexpected_total 1001
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3790
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44350
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 114
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43051
telemt_me_writer_teardown_success_total{mode="normal"} 48140
telemt_me_writer_teardown_noop_total 47109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95249
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.036253
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95249
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 47
telemt_me_writer_restored_same_endpoint_total 942
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 7219206
telemt_user_connections_current{user="hello"} 5950
telemt_user_octets_from_client{user="hello"} 139599528180 (130.01 GB)
telemt_user_octets_to_client{user="hello"} 3366877426244 (3.06 TB)
telemt_user_unique_ips_current{user="hello"} 2188
telemt_user_unique_ips_recent_window{user="hello"} 830
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 135864.9 (37h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8453549
telemt_connections_bad_total 938616
telemt_connections_current 5075
telemt_connections_me_current 5075
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 219298
telemt_upstream_connect_attempt_total 76734
telemt_upstream_connect_success_total 76191
telemt_upstream_connect_fail_total 474
telemt_upstream_connect_attempts_per_request{bucket="1"} 76665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30760
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1967
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 474
telemt_me_reconnect_attempts_total 6571
telemt_me_reconnect_success_total 1534
telemt_me_reader_eof_total 1363
telemt_me_idle_close_by_peer_total 1363
telemt_me_seq_mismatch_total 65
telemt_me_route_drop_no_conn_total 3018129
telemt_me_route_drop_channel_closed_total 265
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6465072
telemt_me_endpoint_quarantine_total 1054
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1026
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 28552
telemt_desync_full_logged_total 9427
telemt_desync_suppressed_total 19125
telemt_desync_frames_bucket_total{bucket="1_2"} 7040
telemt_desync_frames_bucket_total{bucket="3_10"} 10517
telemt_desync_frames_bucket_total{bucket="gt_10"} 10995
telemt_pool_swap_total 147
telemt_pool_force_close_total 3985
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 490
telemt_me_draining_writers_reap_progress_total 45787
telemt_me_writer_removed_unexpected_total 1381
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4441
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42790
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3690
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41802
telemt_me_writer_teardown_success_total{mode="normal"} 47231
telemt_me_writer_teardown_noop_total 45791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93022
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.550744
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93022
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 490
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 1195
telemt_me_writer_restored_fallback_total 89
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6473246
telemt_user_connections_current{user="hello"} 5075
telemt_user_octets_from_client{user="hello"} 117583601633 (109.51 GB)
telemt_user_octets_to_client{user="hello"} 2734913824699 (2.49 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1958
telemt_user_unique_ips_recent_window{user="hello"} 757
```