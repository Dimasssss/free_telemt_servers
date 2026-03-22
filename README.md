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

# Server Metrics 2026-03-22 14:11:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 61505.4 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1966850
telemt_connections_bad_total 84320
telemt_connections_current 1731
telemt_connections_me_current 1731
telemt_handshake_timeouts_total 80942
telemt_upstream_connect_attempt_total 23014
telemt_upstream_connect_success_total 23013
telemt_upstream_connect_attempts_per_request{bucket="1"} 23013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 921
telemt_me_reconnect_success_total 375
telemt_me_reader_eof_total 380
telemt_me_idle_close_by_peer_total 380
telemt_me_route_drop_no_conn_total 1439993
telemt_me_route_drop_channel_closed_total 636
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1677639
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 422
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 485
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
telemt_desync_total 9039
telemt_desync_full_logged_total 2786
telemt_desync_suppressed_total 6253
telemt_desync_frames_bucket_total{bucket="1_2"} 2507
telemt_desync_frames_bucket_total{bucket="3_10"} 3397
telemt_desync_frames_bucket_total{bucket="gt_10"} 3135
telemt_pool_swap_total 68
telemt_pool_force_close_total 2056
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 348
telemt_me_draining_writers_reap_progress_total 21002
telemt_me_writer_removed_unexpected_total 370
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1500
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19711
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2018
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18946
telemt_me_writer_teardown_success_total{mode="normal"} 21211
telemt_me_writer_teardown_noop_total 21006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42217
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 164.617006
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42217
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 348
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 333
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1674661
telemt_user_connections_current{user="hello"} 1731
telemt_user_octets_from_client{user="hello"} 26020113660 (24.23 GB)
telemt_user_octets_to_client{user="hello"} 483188139728 (450.00 GB)
telemt_user_unique_ips_current{user="hello"} 654
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 74871.6 (20h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3156726
telemt_connections_bad_total 291911
telemt_connections_current 3330
telemt_connections_me_current 3330
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 75290
telemt_upstream_connect_attempt_total 48101
telemt_upstream_connect_success_total 47522
telemt_upstream_connect_fail_total 514
telemt_upstream_connect_attempts_per_request{bucket="1"} 48036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 514
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 4527
telemt_me_reconnect_success_total 1735
telemt_me_reader_eof_total 1632
telemt_me_idle_close_by_peer_total 1632
telemt_me_route_drop_no_conn_total 2958373
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2488151
telemt_me_endpoint_quarantine_total 614
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 582
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 126
telemt_me_writers_warm_current 19
telemt_desync_total 9861
telemt_desync_full_logged_total 5501
telemt_desync_suppressed_total 4360
telemt_desync_frames_bucket_total{bucket="1_2"} 2325
telemt_desync_frames_bucket_total{bucket="3_10"} 3884
telemt_desync_frames_bucket_total{bucket="gt_10"} 3652
telemt_pool_swap_total 72
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 29710
telemt_me_writer_removed_unexpected_total 1590
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3303
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27998
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27640
telemt_me_writer_teardown_success_total{mode="normal"} 31301
telemt_me_writer_teardown_noop_total 29710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61011
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.890949
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61011
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 115
telemt_me_writer_restored_same_endpoint_total 1456
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 2499712
telemt_user_connections_current{user="hello"} 3330
telemt_user_octets_from_client{user="hello"} 30055101159 (27.99 GB)
telemt_user_octets_to_client{user="hello"} 573045954510 (533.69 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1770
telemt_user_unique_ips_recent_window{user="hello"} 646
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 149731.3 (41h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14207011
telemt_connections_bad_total 1252492
telemt_connections_current 5004
telemt_connections_me_current 5004
telemt_handshake_timeouts_total 356426
telemt_upstream_connect_attempt_total 54247
telemt_upstream_connect_success_total 54165
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 54173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29391
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2463
telemt_me_reconnect_success_total 1287
telemt_me_reader_eof_total 1231
telemt_me_idle_close_by_peer_total 1230
telemt_me_route_drop_no_conn_total 12551085
telemt_me_route_drop_channel_closed_total 126
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11397069
telemt_me_endpoint_quarantine_total 952
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1115
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
telemt_desync_total 46327
telemt_desync_full_logged_total 14641
telemt_desync_suppressed_total 31686
telemt_desync_frames_bucket_total{bucket="1_2"} 10474
telemt_desync_frames_bucket_total{bucket="3_10"} 18136
telemt_desync_frames_bucket_total{bucket="gt_10"} 17717
telemt_pool_swap_total 161
telemt_pool_force_close_total 5506
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 884
telemt_me_draining_writers_reap_progress_total 49484
telemt_me_writer_removed_unexpected_total 1186
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4301
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45696
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5066
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43978
telemt_me_writer_teardown_success_total{mode="normal"} 49997
telemt_me_writer_teardown_noop_total 49533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99530
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 257.590123
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99530
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 884
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1109
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 11384585
telemt_user_connections_current{user="hello"} 5004
telemt_user_octets_from_client{user="hello"} 162725394308 (151.55 GB)
telemt_user_octets_to_client{user="hello"} 3008013076008 (2.74 TB)
telemt_user_unique_ips_current{user="hello"} 1789
telemt_user_unique_ips_recent_window{user="hello"} 842
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 149733.0 (41h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10486319
telemt_connections_bad_total 999821
telemt_connections_current 4529
telemt_connections_me_current 4529
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 312231
telemt_upstream_connect_attempt_total 80631
telemt_upstream_connect_success_total 79487
telemt_upstream_connect_fail_total 822
telemt_upstream_connect_attempts_per_request{bucket="1"} 80309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31932
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3681
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 822
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3701
telemt_me_reconnect_success_total 1473
telemt_me_reader_eof_total 1348
telemt_me_idle_close_by_peer_total 1348
telemt_me_route_drop_no_conn_total 4165649
telemt_me_route_drop_channel_closed_total 456
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7826606
telemt_me_endpoint_quarantine_total 940
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1137
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
telemt_me_writers_active_current 44
telemt_desync_total 34917
telemt_desync_full_logged_total 11748
telemt_desync_suppressed_total 23169
telemt_desync_frames_bucket_total{bucket="1_2"} 8612
telemt_desync_frames_bucket_total{bucket="3_10"} 13433
telemt_desync_frames_bucket_total{bucket="gt_10"} 12872
telemt_pool_swap_total 160
telemt_pool_force_close_total 4942
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 620
telemt_me_draining_writers_reap_progress_total 47692
telemt_me_writer_removed_unexpected_total 1380
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4338
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44591
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4514
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 428
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42750
telemt_me_writer_teardown_success_total{mode="normal"} 48929
telemt_me_writer_teardown_noop_total 47707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96636
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 95.121590
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96636
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 620
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 1250
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 7765928
telemt_user_connections_current{user="hello"} 4529
telemt_user_octets_from_client{user="hello"} 196307597265 (182.83 GB)
telemt_user_octets_to_client{user="hello"} 3499241867966 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1769
telemt_user_unique_ips_recent_window{user="hello"} 681
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 149696.6 (41h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9935669
telemt_connections_bad_total 840786
telemt_connections_current 4445
telemt_connections_me_current 4445
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 320522
telemt_upstream_connect_attempt_total 66087
telemt_upstream_connect_success_total 65182
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 65363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2014
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4529
telemt_me_reconnect_success_total 1840
telemt_me_reader_eof_total 1592
telemt_me_idle_close_by_peer_total 1591
telemt_me_route_drop_no_conn_total 4888081
telemt_me_route_drop_channel_closed_total 331
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7503828
telemt_me_endpoint_quarantine_total 1035
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1097
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 34791
telemt_desync_full_logged_total 11527
telemt_desync_suppressed_total 23264
telemt_desync_frames_bucket_total{bucket="1_2"} 8804
telemt_desync_frames_bucket_total{bucket="3_10"} 13311
telemt_desync_frames_bucket_total{bucket="gt_10"} 12676
telemt_pool_swap_total 156
telemt_pool_force_close_total 4885
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 660
telemt_me_draining_writers_reap_progress_total 48334
telemt_me_writer_removed_unexpected_total 1737
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4850
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45134
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4363
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 522
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43449
telemt_me_writer_teardown_success_total{mode="normal"} 49984
telemt_me_writer_teardown_noop_total 48401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98385
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3163.814880
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98385
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 660
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1597
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 7497520
telemt_user_connections_current{user="hello"} 4445
telemt_user_octets_from_client{user="hello"} 175607801241 (163.55 GB)
telemt_user_octets_to_client{user="hello"} 3129105683265 (2.85 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1747
telemt_user_unique_ips_recent_window{user="hello"} 647
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 19976.2 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8441039
telemt_connections_bad_total 525833
telemt_connections_current 7111
telemt_connections_me_current 7111
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 136502
telemt_upstream_connect_attempt_total 28626
telemt_upstream_connect_success_total 27211
telemt_upstream_connect_fail_total 1030
telemt_upstream_connect_attempts_per_request{bucket="1"} 28241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4737
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1030
telemt_me_keepalive_timeout_total 752
telemt_me_reconnect_attempts_total 5498
telemt_me_reconnect_success_total 577
telemt_me_reader_eof_total 361
telemt_me_idle_close_by_peer_total 361
telemt_me_route_drop_no_conn_total 20664078
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7029259
telemt_me_endpoint_quarantine_total 126
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 154
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
telemt_me_writers_active_current 88
telemt_me_writers_warm_current 13
telemt_desync_total 10398
telemt_desync_full_logged_total 2675
telemt_desync_suppressed_total 7723
telemt_desync_frames_bucket_total{bucket="1_2"} 1828
telemt_desync_frames_bucket_total{bucket="3_10"} 4188
telemt_desync_frames_bucket_total{bucket="gt_10"} 4382
telemt_pool_swap_total 18
telemt_pool_force_close_total 745
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 268
telemt_me_draining_writers_reap_progress_total 5166
telemt_me_writer_removed_unexpected_total 491
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 921
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4693
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 535
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4421
telemt_me_writer_teardown_success_total{mode="normal"} 5614
telemt_me_writer_teardown_noop_total 5169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10783
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 24.041527
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10783
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 268
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 407
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 7044178
telemt_user_connections_current{user="hello"} 7111
telemt_user_octets_from_client{user="hello"} 40680059183 (37.89 GB)
telemt_user_octets_to_client{user="hello"} 205974530096 (191.83 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2617
telemt_user_unique_ips_recent_window{user="hello"} 1456
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 149703.2 (41h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9660827
telemt_connections_bad_total 796739
telemt_connections_current 5213
telemt_connections_me_current 5213
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 209092
telemt_upstream_connect_attempt_total 90407
telemt_upstream_connect_success_total 89494
telemt_upstream_connect_fail_total 791
telemt_upstream_connect_attempts_per_request{bucket="1"} 90285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1253
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 791
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71398
telemt_me_reconnect_success_total 2466
telemt_me_reader_eof_total 2197
telemt_me_idle_close_by_peer_total 2196
telemt_me_route_drop_no_conn_total 4748892
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7629105
telemt_me_endpoint_quarantine_total 1001
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1117
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 39208
telemt_desync_full_logged_total 13402
telemt_desync_suppressed_total 25806
telemt_desync_frames_bucket_total{bucket="1_2"} 7967
telemt_desync_frames_bucket_total{bucket="3_10"} 15210
telemt_desync_frames_bucket_total{bucket="gt_10"} 16031
telemt_pool_swap_total 153
telemt_pool_force_close_total 4532
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 555
telemt_me_draining_writers_reap_progress_total 50920
telemt_me_writer_removed_unexpected_total 2224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5405
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47756
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3915
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 617
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46388
telemt_me_writer_teardown_success_total{mode="normal"} 53161
telemt_me_writer_teardown_noop_total 50921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104082
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.834617
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104082
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 555
telemt_me_refill_failed_total 4253
telemt_me_writer_restored_same_endpoint_total 2074
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 7630160
telemt_user_connections_current{user="hello"} 5213
telemt_user_octets_from_client{user="hello"} 175044671135 (163.02 GB)
telemt_user_octets_to_client{user="hello"} 2889540595121 (2.63 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2022
telemt_user_unique_ips_recent_window{user="hello"} 765
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 86539.2 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9722985
telemt_connections_bad_total 353819
telemt_connections_current 4965
telemt_connections_me_current 4965
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4080333
telemt_upstream_connect_attempt_total 42619
telemt_upstream_connect_success_total 42309
telemt_upstream_connect_fail_total 303
telemt_upstream_connect_attempts_per_request{bucket="1"} 42612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 303
telemt_me_reconnect_attempts_total 47934
telemt_me_reconnect_success_total 1448
telemt_me_reader_eof_total 1116
telemt_me_idle_close_by_peer_total 1116
telemt_me_route_drop_no_conn_total 3572766
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4688396
telemt_me_endpoint_quarantine_total 570
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 651
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 25641
telemt_desync_full_logged_total 8614
telemt_desync_suppressed_total 17027
telemt_desync_frames_bucket_total{bucket="1_2"} 5176
telemt_desync_frames_bucket_total{bucket="3_10"} 10162
telemt_desync_frames_bucket_total{bucket="gt_10"} 10303
telemt_pool_swap_total 91
telemt_pool_force_close_total 2803
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 289
telemt_me_draining_writers_reap_progress_total 29930
telemt_me_writer_removed_unexpected_total 1181
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2702
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28437
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2394
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 409
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27127
telemt_me_writer_teardown_success_total{mode="normal"} 31139
telemt_me_writer_teardown_noop_total 29937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61076
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.207825
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61076
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 289
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1295
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4682817
telemt_user_connections_current{user="hello"} 4965
telemt_user_octets_from_client{user="hello"} 101905766708 (94.91 GB)
telemt_user_octets_to_client{user="hello"} 1780199961638 (1.62 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1965
telemt_user_unique_ips_recent_window{user="hello"} 746
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 67510.4 (18h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816294
telemt_connections_bad_total 10693
telemt_connections_current 1092
telemt_connections_me_current 1092
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15248
telemt_upstream_connect_attempt_total 34064
telemt_upstream_connect_success_total 33979
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 34048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 446
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1561
telemt_me_reconnect_success_total 664
telemt_me_reader_eof_total 639
telemt_me_idle_close_by_peer_total 639
telemt_me_route_drop_no_conn_total 280398
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 729229
telemt_me_endpoint_quarantine_total 601
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 560
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
telemt_me_writers_active_current 50
telemt_desync_total 4021
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2803
telemt_desync_frames_bucket_total{bucket="1_2"} 976
telemt_desync_frames_bucket_total{bucket="3_10"} 1600
telemt_desync_frames_bucket_total{bucket="gt_10"} 1445
telemt_pool_swap_total 71
telemt_pool_force_close_total 1769
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 27981
telemt_me_writer_removed_unexpected_total 618
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2152
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26470
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1691
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26212
telemt_me_writer_teardown_success_total{mode="normal"} 28622
telemt_me_writer_teardown_noop_total 27983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56605
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.063108
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56605
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 567
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 730466
telemt_user_connections_current{user="hello"} 1092
telemt_user_octets_from_client{user="hello"} 13602545993 (12.67 GB)
telemt_user_octets_to_client{user="hello"} 342600475547 (319.07 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 392
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 149707.7 (41h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11776869
telemt_connections_bad_total 1373904
telemt_connections_current 6369
telemt_connections_me_current 6369
telemt_handshake_timeouts_total 321864
telemt_upstream_connect_attempt_total 56333
telemt_upstream_connect_success_total 56111
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 56283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28391
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_reconnect_attempts_total 2200
telemt_me_reconnect_success_total 1177
telemt_me_reader_eof_total 1140
telemt_me_idle_close_by_peer_total 1140
telemt_me_route_drop_no_conn_total 3759650
telemt_me_route_drop_channel_closed_total 110
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8866388
telemt_me_endpoint_quarantine_total 1025
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1122
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
telemt_me_writers_active_current 45
telemt_desync_total 36539
telemt_desync_full_logged_total 11943
telemt_desync_suppressed_total 24596
telemt_desync_frames_bucket_total{bucket="1_2"} 8729
telemt_desync_frames_bucket_total{bucket="3_10"} 13518
telemt_desync_frames_bucket_total{bucket="gt_10"} 14292
telemt_pool_swap_total 166
telemt_pool_force_close_total 4582
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 582
telemt_me_draining_writers_reap_progress_total 50761
telemt_me_writer_removed_unexpected_total 1095
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4176
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47710
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4418
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 164
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46179
telemt_me_writer_teardown_success_total{mode="normal"} 51886
telemt_me_writer_teardown_noop_total 50763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102649
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.085181
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102649
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 582
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1031
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8836421
telemt_user_connections_current{user="hello"} 6369
telemt_user_octets_from_client{user="hello"} 170248438296 (158.56 GB)
telemt_user_octets_to_client{user="hello"} 3968553635740 (3.61 TB)
telemt_user_unique_ips_current{user="hello"} 2225
telemt_user_unique_ips_recent_window{user="hello"} 810
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 149704.1 (41h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10198555
telemt_connections_bad_total 1143475
telemt_connections_current 4855
telemt_connections_me_current 4855
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 265842
telemt_upstream_connect_attempt_total 81942
telemt_upstream_connect_success_total 81338
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 81861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_reconnect_attempts_total 8672
telemt_me_reconnect_success_total 1956
telemt_me_reader_eof_total 1823
telemt_me_idle_close_by_peer_total 1823
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 4735740
telemt_me_route_drop_channel_closed_total 325
telemt_me_route_drop_queue_full_total 17
telemt_me_route_drop_queue_full_profile_total{profile="high"} 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7860669
telemt_me_endpoint_quarantine_total 1143
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1126
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 35807
telemt_desync_full_logged_total 11614
telemt_desync_suppressed_total 24193
telemt_desync_frames_bucket_total{bucket="1_2"} 8851
telemt_desync_frames_bucket_total{bucket="3_10"} 13367
telemt_desync_frames_bucket_total{bucket="gt_10"} 13589
telemt_pool_swap_total 159
telemt_pool_force_close_total 4442
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 574
telemt_me_draining_writers_reap_progress_total 50088
telemt_me_writer_removed_unexpected_total 1848
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5196
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46807
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4034
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 408
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45646
telemt_me_writer_teardown_success_total{mode="normal"} 52003
telemt_me_writer_teardown_noop_total 50092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102095
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.683555
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102095
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 574
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 1585
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 7867380
telemt_user_connections_current{user="hello"} 4855
telemt_user_octets_from_client{user="hello"} 138164257745 (128.68 GB)
telemt_user_octets_to_client{user="hello"} 3067853269763 (2.79 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1767
telemt_user_unique_ips_recent_window{user="hello"} 693
```