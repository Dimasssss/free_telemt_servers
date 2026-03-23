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

# Server Metrics 2026-03-23 06:32:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 120351.5 (33h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4331126
telemt_connections_bad_total 412122
telemt_connections_current 1599
telemt_connections_me_current 1599
telemt_handshake_timeouts_total 147934
telemt_upstream_connect_attempt_total 44630
telemt_upstream_connect_success_total 44629
telemt_upstream_connect_attempts_per_request{bucket="1"} 44629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 98
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1560
telemt_me_reconnect_success_total 704
telemt_me_reader_eof_total 729
telemt_me_idle_close_by_peer_total 729
telemt_me_route_drop_no_conn_total 3578019
telemt_me_route_drop_channel_closed_total 1387
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3542201
telemt_me_writer_pick_total{mode="p2c",result="full"} 22
telemt_me_endpoint_quarantine_total 851
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 942
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
telemt_me_writers_active_current 46
telemt_desync_total 14695
telemt_desync_full_logged_total 4666
telemt_desync_suppressed_total 10029
telemt_desync_frames_bucket_total{bucket="1_2"} 3795
telemt_desync_frames_bucket_total{bucket="3_10"} 5490
telemt_desync_frames_bucket_total{bucket="gt_10"} 5410
telemt_pool_swap_total 133
telemt_pool_force_close_total 4102
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 783
telemt_me_draining_writers_reap_progress_total 40884
telemt_me_writer_removed_unexpected_total 701
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2941
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38216
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4031
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 71
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36782
telemt_me_writer_teardown_success_total{mode="normal"} 41157
telemt_me_writer_teardown_noop_total 40897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82054
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 452.873620
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82054
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 783
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 632
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 3529414
telemt_user_connections_current{user="hello"} 1599
telemt_user_octets_from_client{user="hello"} 46636833972 (43.43 GB)
telemt_user_octets_to_client{user="hello"} 919133718144 (856.01 GB)
telemt_user_unique_ips_current{user="hello"} 606
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 133717.7 (37h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4220520
telemt_connections_bad_total 393033
telemt_connections_current 1030
telemt_connections_me_current 1030
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 111579
telemt_upstream_connect_attempt_total 83047
telemt_upstream_connect_success_total 82050
telemt_upstream_connect_fail_total 885
telemt_upstream_connect_attempts_per_request{bucket="1"} 82935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 885
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 11151
telemt_me_reconnect_success_total 4026
telemt_me_reader_eof_total 3995
telemt_me_idle_close_by_peer_total 3994
telemt_me_route_drop_no_conn_total 3688006
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3346602
telemt_me_endpoint_quarantine_total 1085
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1055
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_me_writers_active_current 89
telemt_desync_total 13821
telemt_desync_full_logged_total 7804
telemt_desync_suppressed_total 6017
telemt_desync_frames_bucket_total{bucket="1_2"} 3131
telemt_desync_frames_bucket_total{bucket="3_10"} 5421
telemt_desync_frames_bucket_total{bucket="gt_10"} 5269
telemt_pool_swap_total 125
telemt_pool_force_close_total 3492
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 272
telemt_me_draining_writers_reap_progress_total 56187
telemt_me_writer_removed_unexpected_total 3916
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7072
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53075
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2983
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52695
telemt_me_writer_teardown_success_total{mode="normal"} 60147
telemt_me_writer_teardown_noop_total 56188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116335
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.029136
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116335
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 272
telemt_me_refill_failed_total 283
telemt_me_writer_restored_same_endpoint_total 3566
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 3360942
telemt_user_connections_current{user="hello"} 1030
telemt_user_octets_from_client{user="hello"} 45237734307 (42.13 GB)
telemt_user_octets_to_client{user="hello"} 851990724997 (793.48 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 584
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 208577.5 (57h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16832044
telemt_connections_bad_total 1710613
telemt_connections_current 2280
telemt_connections_me_current 2280
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 416600
telemt_upstream_connect_attempt_total 93607
telemt_upstream_connect_success_total 93496
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 93513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1735
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3326
telemt_me_reconnect_success_total 1750
telemt_me_reader_eof_total 1708
telemt_me_idle_close_by_peer_total 1705
telemt_me_route_drop_no_conn_total 14158466
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13368750
telemt_me_endpoint_quarantine_total 1413
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1580
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 56149
telemt_desync_full_logged_total 17945
telemt_desync_suppressed_total 38204
telemt_desync_frames_bucket_total{bucket="1_2"} 12471
telemt_desync_frames_bucket_total{bucket="3_10"} 22004
telemt_desync_frames_bucket_total{bucket="gt_10"} 21674
telemt_pool_swap_total 225
telemt_pool_force_close_total 7200
telemt_pool_stale_pick_total 20
telemt_me_writer_close_signal_drop_total 1116
telemt_me_draining_writers_reap_progress_total 72191
telemt_me_writer_removed_unexpected_total 1641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6083
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67035
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6730
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64991
telemt_me_writer_teardown_success_total{mode="normal"} 73118
telemt_me_writer_teardown_noop_total 72245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 142031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 144753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 145324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 145354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 145355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 145359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 145361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 145363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 145363
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.978040
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 145363
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1116
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1521
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13368492
telemt_user_connections_current{user="hello"} 2280
telemt_user_octets_from_client{user="hello"} 202323339281 (188.43 GB)
telemt_user_octets_to_client{user="hello"} 3644957373671 (3.32 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 859
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 208582.3 (57h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12290885
telemt_connections_bad_total 1311501
telemt_connections_current 1443
telemt_connections_me_current 1443
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 356102
telemt_upstream_connect_attempt_total 107900
telemt_upstream_connect_success_total 106485
telemt_upstream_connect_fail_total 901
telemt_upstream_connect_attempts_per_request{bucket="1"} 107386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46227
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3809
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 901
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4771
telemt_me_reconnect_success_total 2059
telemt_me_reader_eof_total 1915
telemt_me_idle_close_by_peer_total 1915
telemt_me_route_drop_no_conn_total 4637602
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9086536
telemt_me_endpoint_quarantine_total 1425
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1596
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 61
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
telemt_me_writers_active_current 43
telemt_desync_total 39984
telemt_desync_full_logged_total 13529
telemt_desync_suppressed_total 26455
telemt_desync_frames_bucket_total{bucket="1_2"} 9914
telemt_desync_frames_bucket_total{bucket="3_10"} 15347
telemt_desync_frames_bucket_total{bucket="gt_10"} 14723
telemt_pool_swap_total 223
telemt_pool_force_close_total 6583
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 725
telemt_me_draining_writers_reap_progress_total 70264
telemt_me_writer_removed_unexpected_total 1944
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6150
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65922
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6068
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63681
telemt_me_writer_teardown_success_total{mode="normal"} 72072
telemt_me_writer_teardown_noop_total 70289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 135547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 138814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 139972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142361
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 105.116245
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142361
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 725
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1755
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 9024026
telemt_user_connections_current{user="hello"} 1443
telemt_user_octets_from_client{user="hello"} 221239480192 (206.05 GB)
telemt_user_octets_to_client{user="hello"} 4057203011275 (3.69 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 535
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 208543.4 (57h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11423269
telemt_connections_bad_total 1052297
telemt_connections_current 1037
telemt_connections_me_current 1037
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 362596
telemt_upstream_connect_attempt_total 92321
telemt_upstream_connect_success_total 90740
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 90945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5955
telemt_me_reconnect_success_total 2519
telemt_me_reader_eof_total 2256
telemt_me_idle_close_by_peer_total 2255
telemt_me_route_drop_no_conn_total 5405811
telemt_me_route_drop_channel_closed_total 388
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8586701
telemt_me_endpoint_quarantine_total 1478
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1559
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 75
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
telemt_desync_total 39082
telemt_desync_full_logged_total 12997
telemt_desync_suppressed_total 26085
telemt_desync_frames_bucket_total{bucket="1_2"} 9855
telemt_desync_frames_bucket_total{bucket="3_10"} 14954
telemt_desync_frames_bucket_total{bucket="gt_10"} 14273
telemt_pool_swap_total 219
telemt_pool_force_close_total 6470
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 769
telemt_me_draining_writers_reap_progress_total 70885
telemt_me_writer_removed_unexpected_total 2401
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6898
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66325
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5893
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 577
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64415
telemt_me_writer_teardown_success_total{mode="normal"} 73223
telemt_me_writer_teardown_noop_total 70956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 138254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 141017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 141991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 143097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 143698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 143912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 144040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 144071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 144079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 144092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 144125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 144128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 144179
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3175.555232
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 144179
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 769
telemt_me_refill_failed_total 182
telemt_me_writer_restored_same_endpoint_total 2187
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 8578417
telemt_user_connections_current{user="hello"} 1037
telemt_user_octets_from_client{user="hello"} 194911802019 (181.53 GB)
telemt_user_octets_to_client{user="hello"} 3560105267849 (3.24 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 78823.1 (21h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11886390
telemt_connections_bad_total 723792
telemt_connections_current 2424
telemt_connections_me_current 2424
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 337465
telemt_upstream_connect_attempt_total 72731
telemt_upstream_connect_success_total 68972
telemt_upstream_connect_fail_total 2457
telemt_upstream_connect_attempts_per_request{bucket="1"} 71429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25110
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1537
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6059
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2457
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8651
telemt_me_reconnect_success_total 1614
telemt_me_reader_eof_total 1030
telemt_me_idle_close_by_peer_total 1029
telemt_me_route_drop_no_conn_total 25438545
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9802155
telemt_me_endpoint_quarantine_total 626
telemt_me_single_endpoint_outage_enter_total 113
telemt_me_single_endpoint_outage_exit_total 113
telemt_me_single_endpoint_outage_reconnect_attempt_total 215
telemt_me_single_endpoint_outage_reconnect_success_total 58
telemt_me_single_endpoint_quarantine_bypass_total 215
telemt_me_single_endpoint_shadow_rotate_total 633
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
telemt_desync_total 17621
telemt_desync_full_logged_total 4960
telemt_desync_suppressed_total 12661
telemt_desync_frames_bucket_total{bucket="1_2"} 3425
telemt_desync_frames_bucket_total{bucket="3_10"} 7202
telemt_desync_frames_bucket_total{bucket="gt_10"} 6994
telemt_pool_swap_total 81
telemt_pool_force_close_total 2505
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 550
telemt_me_draining_writers_reap_progress_total 26147
telemt_me_writer_removed_unexpected_total 1484
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3381
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24196
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2153
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 352
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23642
telemt_me_writer_teardown_success_total{mode="normal"} 27577
telemt_me_writer_teardown_noop_total 26166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53743
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.485507
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53743
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 550
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 1030
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3157
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 9833270
telemt_user_connections_current{user="hello"} 2424
telemt_user_octets_from_client{user="hello"} 92417485540 (86.07 GB)
telemt_user_octets_to_client{user="hello"} 779061523564 (725.56 GB)
telemt_user_msgs_from_client{user="hello"} 78576
telemt_user_msgs_to_client{user="hello"} 74228
telemt_user_unique_ips_current{user="hello"} 812
telemt_user_unique_ips_recent_window{user="hello"} 332
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 208549.8 (57h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11425068
telemt_connections_bad_total 1008264
telemt_connections_current 1643
telemt_connections_me_current 1643
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 260866
telemt_upstream_connect_attempt_total 121631
telemt_upstream_connect_success_total 120334
telemt_upstream_connect_fail_total 1118
telemt_upstream_connect_attempts_per_request{bucket="1"} 121452
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48406
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1382
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1118
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73763
telemt_me_reconnect_success_total 3364
telemt_me_reader_eof_total 3041
telemt_me_idle_close_by_peer_total 3038
telemt_me_route_drop_no_conn_total 5357471
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8990143
telemt_me_endpoint_quarantine_total 1431
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1587
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 47735
telemt_desync_full_logged_total 16432
telemt_desync_suppressed_total 31303
telemt_desync_frames_bucket_total{bucket="1_2"} 9712
telemt_desync_frames_bucket_total{bucket="3_10"} 18286
telemt_desync_frames_bucket_total{bucket="gt_10"} 19737
telemt_pool_swap_total 214
telemt_pool_force_close_total 6170
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 75243
telemt_me_writer_removed_unexpected_total 3057
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7480
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70868
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5400
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 770
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69073
telemt_me_writer_teardown_success_total{mode="normal"} 78348
telemt_me_writer_teardown_noop_total 75244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 152840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 153275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 153548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 153582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 153585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 153585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 153588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 153592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 153592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 153592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 153592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 153592
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.507068
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 153592
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 4327
telemt_me_writer_restored_same_endpoint_total 2832
telemt_me_writer_restored_fallback_total 59
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7375
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8992720
telemt_user_connections_current{user="hello"} 1643
telemt_user_octets_from_client{user="hello"} 200303838749 (186.55 GB)
telemt_user_octets_to_client{user="hello"} 3445951691056 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 635
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 145386.0 (40h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12243546
telemt_connections_bad_total 506760
telemt_connections_current 1305
telemt_connections_me_current 1305
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4929375
telemt_upstream_connect_attempt_total 70341
telemt_upstream_connect_success_total 69838
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 70328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_reconnect_attempts_total 49487
telemt_me_reconnect_success_total 2010
telemt_me_reader_eof_total 1691
telemt_me_idle_close_by_peer_total 1690
telemt_me_route_drop_no_conn_total 4172040
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5883077
telemt_me_endpoint_quarantine_total 1000
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1121
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
telemt_me_writers_active_current 41
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 33125
telemt_desync_full_logged_total 11366
telemt_desync_suppressed_total 21759
telemt_desync_frames_bucket_total{bucket="1_2"} 6667
telemt_desync_frames_bucket_total{bucket="3_10"} 13027
telemt_desync_frames_bucket_total{bucket="gt_10"} 13431
telemt_pool_swap_total 155
telemt_pool_force_close_total 4363
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 55002
telemt_me_writer_removed_unexpected_total 1726
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4363
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52425
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3917
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 446
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50639
telemt_me_writer_teardown_success_total{mode="normal"} 56788
telemt_me_writer_teardown_noop_total 55009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111797
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.114169
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111797
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 2758
telemt_me_writer_restored_same_endpoint_total 1774
telemt_me_writer_restored_fallback_total 31
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4336
telemt_user_connections_total{user="hello"} 5874873
telemt_user_connections_current{user="hello"} 1305
telemt_user_octets_from_client{user="hello"} 122836905868 (114.40 GB)
telemt_user_octets_to_client{user="hello"} 2292396292826 (2.08 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 552
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 126356.9 (35h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1813367
telemt_connections_bad_total 37745
telemt_connections_current 1103
telemt_connections_me_current 1103
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 40191
telemt_upstream_connect_attempt_total 59132
telemt_upstream_connect_success_total 58933
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 59093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 870
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 2562
telemt_me_reconnect_success_total 1036
telemt_me_reader_eof_total 1034
telemt_me_idle_close_by_peer_total 1034
telemt_me_route_drop_no_conn_total 700972
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1612042
telemt_me_endpoint_quarantine_total 1069
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1040
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
telemt_desync_total 10752
telemt_desync_full_logged_total 3038
telemt_desync_suppressed_total 7714
telemt_desync_frames_bucket_total{bucket="1_2"} 3422
telemt_desync_frames_bucket_total{bucket="3_10"} 4020
telemt_desync_frames_bucket_total{bucket="gt_10"} 3310
telemt_pool_swap_total 137
telemt_pool_force_close_total 3473
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 50487
telemt_me_writer_removed_unexpected_total 996
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3813
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47718
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3384
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 89
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47014
telemt_me_writer_teardown_success_total{mode="normal"} 51531
telemt_me_writer_teardown_noop_total 50491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102022
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.751956
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102022
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 889
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 1607563
telemt_user_connections_current{user="hello"} 1103
telemt_user_octets_from_client{user="hello"} 28453404089 (26.50 GB)
telemt_user_octets_to_client{user="hello"} 629680129683 (586.44 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 208554.1 (57h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13708785
telemt_connections_bad_total 1667878
telemt_connections_current 1669
telemt_connections_me_current 1669
telemt_handshake_timeouts_total 402158
telemt_upstream_connect_attempt_total 84218
telemt_upstream_connect_success_total 83849
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 84081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3313
telemt_me_reconnect_success_total 1658
telemt_me_reader_eof_total 1650
telemt_me_idle_close_by_peer_total 1650
telemt_me_route_drop_no_conn_total 4558732
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10334239
telemt_me_endpoint_quarantine_total 1545
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1587
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 43533
telemt_desync_full_logged_total 14161
telemt_desync_suppressed_total 29372
telemt_desync_frames_bucket_total{bucket="1_2"} 10593
telemt_desync_frames_bucket_total{bucket="3_10"} 16004
telemt_desync_frames_bucket_total{bucket="gt_10"} 16936
telemt_pool_swap_total 231
telemt_pool_force_close_total 6017
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 713
telemt_me_draining_writers_reap_progress_total 76238
telemt_me_writer_removed_unexpected_total 1577
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5854
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 72024
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5843
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70221
telemt_me_writer_teardown_success_total{mode="normal"} 77878
telemt_me_writer_teardown_noop_total 76240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 153221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 153609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 153985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 154105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 154118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 154118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 154118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 154118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 154118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 154118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 154118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 154118
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.198461
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 154118
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 713
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1457
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10300544
telemt_user_connections_current{user="hello"} 1669
telemt_user_octets_from_client{user="hello"} 198061228024 (184.46 GB)
telemt_user_octets_to_client{user="hello"} 4597470114168 (4.18 TB)
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 208550.9 (57h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12031143
telemt_connections_bad_total 1425275
telemt_connections_current 1464
telemt_connections_me_current 1464
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 323174
telemt_upstream_connect_attempt_total 112242
telemt_upstream_connect_success_total 111281
telemt_upstream_connect_fail_total 752
telemt_upstream_connect_attempts_per_request{bucket="1"} 112033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 752
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11221
telemt_me_reconnect_success_total 2806
telemt_me_reader_eof_total 2602
telemt_me_idle_close_by_peer_total 2601
telemt_me_seq_mismatch_total 113
telemt_me_route_drop_no_conn_total 5728715
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9253545
telemt_me_endpoint_quarantine_total 1735
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1590
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 61
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
telemt_desync_total 43493
telemt_desync_full_logged_total 13891
telemt_desync_suppressed_total 29602
telemt_desync_frames_bucket_total{bucket="1_2"} 11261
telemt_desync_frames_bucket_total{bucket="3_10"} 16092
telemt_desync_frames_bucket_total{bucket="gt_10"} 16140
telemt_pool_swap_total 221
telemt_pool_force_close_total 5763
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 691
telemt_me_draining_writers_reap_progress_total 76741
telemt_me_writer_removed_unexpected_total 2636
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7275
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 72210
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5291
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 472
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 70978
telemt_me_writer_teardown_success_total{mode="normal"} 79485
telemt_me_writer_teardown_noop_total 76746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 153468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 155290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 155846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 156181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 156231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 156231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 156231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 156231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 156231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 156231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 156231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 156231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 156231
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.070149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 156231
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 691
telemt_me_refill_failed_total 437
telemt_me_writer_restored_same_endpoint_total 2234
telemt_me_writer_restored_fallback_total 148
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 141
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 9257756
telemt_user_connections_current{user="hello"} 1464
telemt_user_octets_from_client{user="hello"} 160679775856 (149.64 GB)
telemt_user_octets_to_client{user="hello"} 3624020087094 (3.30 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 218
```