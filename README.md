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

# Server Metrics 2026-03-22 11:37:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 52260.6 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1484671
telemt_connections_bad_total 73098
telemt_connections_current 1795
telemt_connections_me_current 1795
telemt_handshake_timeouts_total 67963
telemt_upstream_connect_attempt_total 20087
telemt_upstream_connect_success_total 20086
telemt_upstream_connect_attempts_per_request{bucket="1"} 20086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 50
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 681
telemt_me_reconnect_success_total 333
telemt_me_reader_eof_total 328
telemt_me_idle_close_by_peer_total 328
telemt_me_route_drop_no_conn_total 914021
telemt_me_route_drop_channel_closed_total 449
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1250144
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 370
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 417
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
telemt_me_writers_active_current 48
telemt_me_writers_warm_current 16
telemt_desync_total 7818
telemt_desync_full_logged_total 2332
telemt_desync_suppressed_total 5486
telemt_desync_frames_bucket_total{bucket="1_2"} 2244
telemt_desync_frames_bucket_total{bucket="3_10"} 2931
telemt_desync_frames_bucket_total{bucket="gt_10"} 2643
telemt_pool_swap_total 57
telemt_pool_force_close_total 1669
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 254
telemt_me_draining_writers_reap_progress_total 18261
telemt_me_writer_removed_unexpected_total 323
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1283
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17210
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1634
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16592
telemt_me_writer_teardown_success_total{mode="normal"} 18493
telemt_me_writer_teardown_noop_total 18263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36756
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 119.080010
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36756
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 254
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1247644
telemt_user_connections_current{user="hello"} 1795
telemt_user_octets_from_client{user="hello"} 19945832884 (18.58 GB)
telemt_user_octets_to_client{user="hello"} 382854916488 (356.56 GB)
telemt_user_unique_ips_current{user="hello"} 665
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 65627.1 (18h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2437891
telemt_connections_bad_total 204367
telemt_connections_current 2683
telemt_connections_me_current 2683
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 55890
telemt_upstream_connect_attempt_total 43920
telemt_upstream_connect_success_total 43407
telemt_upstream_connect_fail_total 453
telemt_upstream_connect_attempts_per_request{bucket="1"} 43860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 453
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3373
telemt_me_reconnect_success_total 1504
telemt_me_reader_eof_total 1388
telemt_me_idle_close_by_peer_total 1388
telemt_me_route_drop_no_conn_total 2106273
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1922292
telemt_me_endpoint_quarantine_total 556
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 516
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
telemt_me_writers_active_current 87
telemt_desync_total 7643
telemt_desync_full_logged_total 4313
telemt_desync_suppressed_total 3330
telemt_desync_frames_bucket_total{bucket="1_2"} 1761
telemt_desync_frames_bucket_total{bucket="3_10"} 2993
telemt_desync_frames_bucket_total{bucket="gt_10"} 2889
telemt_pool_swap_total 65
telemt_pool_force_close_total 1814
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 26159
telemt_me_writer_removed_unexpected_total 1350
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2891
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24616
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24345
telemt_me_writer_teardown_success_total{mode="normal"} 27507
telemt_me_writer_teardown_noop_total 26159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53666
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.956262
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53666
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1251
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1934191
telemt_user_connections_current{user="hello"} 2683
telemt_user_octets_from_client{user="hello"} 24355206827 (22.68 GB)
telemt_user_octets_to_client{user="hello"} 483774615590 (450.55 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1487
telemt_user_unique_ips_recent_window{user="hello"} 608
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 140487.0 (39h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12332006
telemt_connections_bad_total 1073225
telemt_connections_current 5291
telemt_connections_me_current 5291
telemt_handshake_timeouts_total 323069
telemt_upstream_connect_attempt_total 51039
telemt_upstream_connect_success_total 50959
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 50967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27677
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2194
telemt_me_reconnect_success_total 1122
telemt_me_reader_eof_total 1103
telemt_me_idle_close_by_peer_total 1102
telemt_me_route_drop_no_conn_total 9870267
telemt_me_route_drop_channel_closed_total 107
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9842551
telemt_me_endpoint_quarantine_total 888
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1045
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 15
telemt_desync_total 40319
telemt_desync_full_logged_total 12944
telemt_desync_suppressed_total 27375
telemt_desync_frames_bucket_total{bucket="1_2"} 9080
telemt_desync_frames_bucket_total{bucket="3_10"} 15747
telemt_desync_frames_bucket_total{bucket="gt_10"} 15492
telemt_pool_swap_total 151
telemt_pool_force_close_total 5094
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 798
telemt_me_draining_writers_reap_progress_total 46540
telemt_me_writer_removed_unexpected_total 1062
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3994
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43007
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4753
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 341
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41446
telemt_me_writer_teardown_success_total{mode="normal"} 47001
telemt_me_writer_teardown_noop_total 46584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93585
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.104314
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93585
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 798
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 976
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 9831564
telemt_user_connections_current{user="hello"} 5291
telemt_user_octets_from_client{user="hello"} 146332747716 (136.28 GB)
telemt_user_octets_to_client{user="hello"} 2781839903496 (2.53 TB)
telemt_user_unique_ips_current{user="hello"} 2114
telemt_user_unique_ips_recent_window{user="hello"} 912
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 140488.2 (39h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9284338
telemt_connections_bad_total 832225
telemt_connections_current 4885
telemt_connections_me_current 4885
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 283089
telemt_upstream_connect_attempt_total 57632
telemt_upstream_connect_success_total 57051
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 57318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3223
telemt_me_reconnect_success_total 1307
telemt_me_reader_eof_total 1198
telemt_me_idle_close_by_peer_total 1198
telemt_me_route_drop_no_conn_total 3764444
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6929093
telemt_me_endpoint_quarantine_total 884
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 1070
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 28
telemt_desync_total 31458
telemt_desync_full_logged_total 10624
telemt_desync_suppressed_total 20834
telemt_desync_frames_bucket_total{bucket="1_2"} 7746
telemt_desync_frames_bucket_total{bucket="3_10"} 12114
telemt_desync_frames_bucket_total{bucket="gt_10"} 11598
telemt_pool_swap_total 150
telemt_pool_force_close_total 4602
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 531
telemt_me_draining_writers_reap_progress_total 45065
telemt_me_writer_removed_unexpected_total 1231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3968
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42224
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4240
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40463
telemt_me_writer_teardown_success_total{mode="normal"} 46192
telemt_me_writer_teardown_noop_total 45073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91265
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 70.083848
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91265
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 531
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 1121
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 6850518
telemt_user_connections_current{user="hello"} 4885
telemt_user_octets_from_client{user="hello"} 179302176935 (166.99 GB)
telemt_user_octets_to_client{user="hello"} 3150964544994 (2.87 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1939
telemt_user_unique_ips_recent_window{user="hello"} 677
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 140452.4 (39h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8807028
telemt_connections_bad_total 736309
telemt_connections_current 4175
telemt_connections_me_current 4175
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 280293
telemt_upstream_connect_attempt_total 61844
telemt_upstream_connect_success_total 61129
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 61276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1401
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3730
telemt_me_reconnect_success_total 1544
telemt_me_reader_eof_total 1432
telemt_me_idle_close_by_peer_total 1432
telemt_me_route_drop_no_conn_total 3737791
telemt_me_route_drop_channel_closed_total 251
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6622984
telemt_me_endpoint_quarantine_total 961
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1026
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_me_writers_warm_current 15
telemt_desync_total 30648
telemt_desync_full_logged_total 10372
telemt_desync_suppressed_total 20276
telemt_desync_frames_bucket_total{bucket="1_2"} 7512
telemt_desync_frames_bucket_total{bucket="3_10"} 11824
telemt_desync_frames_bucket_total{bucket="gt_10"} 11312
telemt_pool_swap_total 147
telemt_pool_force_close_total 4522
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 536
telemt_me_draining_writers_reap_progress_total 45771
telemt_me_writer_removed_unexpected_total 1459
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4346
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42822
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4087
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 435
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41249
telemt_me_writer_teardown_success_total{mode="normal"} 47168
telemt_me_writer_teardown_noop_total 45788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92956
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.998807
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92956
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 536
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1363
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6614169
telemt_user_connections_current{user="hello"} 4175
telemt_user_octets_from_client{user="hello"} 162568142047 (151.40 GB)
telemt_user_octets_to_client{user="hello"} 2865298438499 (2.61 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1668
telemt_user_unique_ips_recent_window{user="hello"} 654
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 10732.4 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4568637
telemt_connections_bad_total 286947
telemt_connections_current 6646
telemt_connections_me_current 6646
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 71492
telemt_upstream_connect_attempt_total 23148
telemt_upstream_connect_success_total 22110
telemt_upstream_connect_fail_total 831
telemt_upstream_connect_attempts_per_request{bucket="1"} 22941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 831
telemt_me_keepalive_timeout_total 439
telemt_me_reconnect_attempts_total 2229
telemt_me_reconnect_success_total 332
telemt_me_reader_eof_total 203
telemt_me_idle_close_by_peer_total 203
telemt_me_route_drop_no_conn_total 10467034
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3814084
telemt_me_endpoint_quarantine_total 77
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 89
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
telemt_me_writers_active_current 47
telemt_desync_total 5511
telemt_desync_full_logged_total 1445
telemt_desync_suppressed_total 4066
telemt_desync_frames_bucket_total{bucket="1_2"} 1015
telemt_desync_frames_bucket_total{bucket="3_10"} 2212
telemt_desync_frames_bucket_total{bucket="gt_10"} 2284
telemt_pool_swap_total 9
telemt_pool_force_close_total 399
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 166
telemt_me_draining_writers_reap_progress_total 2784
telemt_me_writer_removed_unexpected_total 292
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 521
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2518
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 269
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 130
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2385
telemt_me_writer_teardown_success_total{mode="normal"} 3039
telemt_me_writer_teardown_noop_total 2787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5826
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.011506
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5826
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 166
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 220
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 3829410
telemt_user_connections_current{user="hello"} 6646
telemt_user_octets_from_client{user="hello"} 20680467658 (19.26 GB)
telemt_user_octets_to_client{user="hello"} 111768126623 (104.09 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2433
telemt_user_unique_ips_recent_window{user="hello"} 1427
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 140459.3 (39h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8550536
telemt_connections_bad_total 738002
telemt_connections_current 4979
telemt_connections_me_current 4979
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 178851
telemt_upstream_connect_attempt_total 87103
telemt_upstream_connect_success_total 86237
telemt_upstream_connect_fail_total 745
telemt_upstream_connect_attempts_per_request{bucket="1"} 86982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 745
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70707
telemt_me_reconnect_success_total 2206
telemt_me_reader_eof_total 1937
telemt_me_idle_close_by_peer_total 1936
telemt_me_route_drop_no_conn_total 3839482
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6751530
telemt_me_endpoint_quarantine_total 942
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1051
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_warm_current 14
telemt_desync_total 34490
telemt_desync_full_logged_total 11876
telemt_desync_suppressed_total 22614
telemt_desync_frames_bucket_total{bucket="1_2"} 7076
telemt_desync_frames_bucket_total{bucket="3_10"} 13229
telemt_desync_frames_bucket_total{bucket="gt_10"} 14185
telemt_pool_swap_total 145
telemt_pool_force_close_total 4223
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 48169
telemt_me_writer_removed_unexpected_total 1966
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4962
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45198
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3681
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43946
telemt_me_writer_teardown_success_total{mode="normal"} 50160
telemt_me_writer_teardown_noop_total 48170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98330
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.821881
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98330
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 4235
telemt_me_writer_restored_same_endpoint_total 1831
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6754564
telemt_user_connections_current{user="hello"} 4979
telemt_user_octets_from_client{user="hello"} 161325907463 (150.25 GB)
telemt_user_octets_to_client{user="hello"} 2645553948085 (2.41 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1989
telemt_user_unique_ips_recent_window{user="hello"} 730
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 77295.2 (21h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7807797
telemt_connections_bad_total 285254
telemt_connections_current 4395
telemt_connections_me_current 4395
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3239817
telemt_upstream_connect_attempt_total 39573
telemt_upstream_connect_success_total 39287
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 39566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_reconnect_attempts_total 47790
telemt_me_reconnect_success_total 1345
telemt_me_reader_eof_total 1013
telemt_me_idle_close_by_peer_total 1013
telemt_me_route_drop_no_conn_total 2511496
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3833359
telemt_me_endpoint_quarantine_total 524
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 586
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
telemt_me_writers_active_current 41
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 20981
telemt_desync_full_logged_total 7018
telemt_desync_suppressed_total 13963
telemt_desync_frames_bucket_total{bucket="1_2"} 4292
telemt_desync_frames_bucket_total{bucket="3_10"} 8126
telemt_desync_frames_bucket_total{bucket="gt_10"} 8563
telemt_pool_swap_total 81
telemt_pool_force_close_total 2487
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 248
telemt_me_draining_writers_reap_progress_total 27254
telemt_me_writer_removed_unexpected_total 1080
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2429
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25931
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2126
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 361
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24767
telemt_me_writer_teardown_success_total{mode="normal"} 28360
telemt_me_writer_teardown_noop_total 27261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55621
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.433669
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55621
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 248
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1197
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3831404
telemt_user_connections_current{user="hello"} 4395
telemt_user_octets_from_client{user="hello"} 88858962808 (82.76 GB)
telemt_user_octets_to_client{user="hello"} 1537421162182 (1.40 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1769
telemt_user_unique_ips_recent_window{user="hello"} 645
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 58265.9 (16h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624848
telemt_connections_bad_total 5909
telemt_connections_current 965
telemt_connections_me_current 965
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 12023
telemt_upstream_connect_attempt_total 30231
telemt_upstream_connect_success_total 30162
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 30223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 332
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 1330
telemt_me_reconnect_success_total 567
telemt_me_reader_eof_total 551
telemt_me_idle_close_by_peer_total 551
telemt_me_route_drop_no_conn_total 207902
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564492
telemt_me_endpoint_quarantine_total 530
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 491
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
telemt_desync_total 3103
telemt_desync_full_logged_total 891
telemt_desync_suppressed_total 2212
telemt_desync_frames_bucket_total{bucket="1_2"} 806
telemt_desync_frames_bucket_total{bucket="3_10"} 1211
telemt_desync_frames_bucket_total{bucket="gt_10"} 1086
telemt_pool_swap_total 61
telemt_pool_force_close_total 1490
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 24650
telemt_me_writer_removed_unexpected_total 534
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1847
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23355
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1414
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23160
telemt_me_writer_teardown_success_total{mode="normal"} 25202
telemt_me_writer_teardown_noop_total 24650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49852
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.690304
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49852
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 497
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 566381
telemt_user_connections_current{user="hello"} 965
telemt_user_octets_from_client{user="hello"} 10752822689 (10.01 GB)
telemt_user_octets_to_client{user="hello"} 265049689515 (246.85 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 140463.5 (39h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10354865
telemt_connections_bad_total 1209251
telemt_connections_current 5859
telemt_connections_me_current 5859
telemt_handshake_timeouts_total 274172
telemt_upstream_connect_attempt_total 53588
telemt_upstream_connect_success_total 53383
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 53541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26990
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_reconnect_attempts_total 2056
telemt_me_reconnect_success_total 1103
telemt_me_reader_eof_total 1068
telemt_me_idle_close_by_peer_total 1068
telemt_me_route_drop_no_conn_total 3023607
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 29
telemt_me_route_drop_queue_full_profile_total{profile="high"} 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7737124
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1055
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
telemt_me_writers_warm_current 15
telemt_desync_total 31602
telemt_desync_full_logged_total 10387
telemt_desync_suppressed_total 21215
telemt_desync_frames_bucket_total{bucket="1_2"} 7643
telemt_desync_frames_bucket_total{bucket="3_10"} 11614
telemt_desync_frames_bucket_total{bucket="gt_10"} 12345
telemt_pool_swap_total 155
telemt_pool_force_close_total 4216
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 517
telemt_me_draining_writers_reap_progress_total 48312
telemt_me_writer_removed_unexpected_total 1026
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3912
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45459
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4087
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 129
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44096
telemt_me_writer_teardown_success_total{mode="normal"} 49371
telemt_me_writer_teardown_noop_total 48314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.672346
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 517
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 963
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7708707
telemt_user_connections_current{user="hello"} 5859
telemt_user_octets_from_client{user="hello"} 149638879856 (139.36 GB)
telemt_user_octets_to_client{user="hello"} 3572257923332 (3.25 TB)
telemt_user_unique_ips_current{user="hello"} 2173
telemt_user_unique_ips_recent_window{user="hello"} 771
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 140460.4 (39h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9068682
telemt_connections_bad_total 1026322
telemt_connections_current 4854
telemt_connections_me_current 4854
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 230967
telemt_upstream_connect_attempt_total 78132
telemt_upstream_connect_success_total 77573
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 78061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1970
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_reconnect_attempts_total 6650
telemt_me_reconnect_success_total 1583
telemt_me_reader_eof_total 1404
telemt_me_idle_close_by_peer_total 1404
telemt_me_seq_mismatch_total 67
telemt_me_route_drop_no_conn_total 3524569
telemt_me_route_drop_channel_closed_total 281
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6950660
telemt_me_endpoint_quarantine_total 1088
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1061
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_me_writers_warm_current 16
telemt_desync_total 30946
telemt_desync_full_logged_total 10151
telemt_desync_suppressed_total 20795
telemt_desync_frames_bucket_total{bucket="1_2"} 7640
telemt_desync_frames_bucket_total{bucket="3_10"} 11494
telemt_desync_frames_bucket_total{bucket="gt_10"} 11812
telemt_pool_swap_total 152
telemt_pool_force_close_total 4151
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 516
telemt_me_draining_writers_reap_progress_total 46997
telemt_me_writer_removed_unexpected_total 1423
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4571
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43913
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3840
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 311
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42846
telemt_me_writer_teardown_success_total{mode="normal"} 48484
telemt_me_writer_teardown_noop_total 47001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95447
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95485
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.941731
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95485
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 516
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1233
telemt_me_writer_restored_fallback_total 91
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 6958456
telemt_user_connections_current{user="hello"} 4854
telemt_user_octets_from_client{user="hello"} 124574731861 (116.02 GB)
telemt_user_octets_to_client{user="hello"} 2854849629223 (2.60 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1895
telemt_user_unique_ips_recent_window{user="hello"} 652
```