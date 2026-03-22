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

# Server Metrics 2026-03-22 09:50:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 45818.2 (12h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1170714
telemt_connections_bad_total 63461
telemt_connections_current 1752
telemt_connections_me_current 1752
telemt_handshake_timeouts_total 53998
telemt_upstream_connect_attempt_total 17843
telemt_upstream_connect_success_total 17842
telemt_upstream_connect_attempts_per_request{bucket="1"} 17842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11590
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 539
telemt_me_reconnect_success_total 272
telemt_me_reader_eof_total 271
telemt_me_idle_close_by_peer_total 271
telemt_me_route_drop_no_conn_total 624458
telemt_me_route_drop_channel_closed_total 261
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 974494
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 319
telemt_me_single_endpoint_shadow_rotate_total 366
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
telemt_desync_total 6834
telemt_desync_full_logged_total 1984
telemt_desync_suppressed_total 4850
telemt_desync_frames_bucket_total{bucket="1_2"} 2012
telemt_desync_frames_bucket_total{bucket="3_10"} 2582
telemt_desync_frames_bucket_total{bucket="gt_10"} 2240
telemt_pool_swap_total 50
telemt_pool_force_close_total 1437
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 16233
telemt_me_writer_removed_unexpected_total 268
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1121
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15319
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14796
telemt_me_writer_teardown_success_total{mode="normal"} 16440
telemt_me_writer_teardown_noop_total 16235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32675
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 67.424159
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32675
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 248
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 972731
telemt_user_connections_current{user="hello"} 1752
telemt_user_octets_from_client{user="hello"} 15303847800 (14.25 GB)
telemt_user_octets_to_client{user="hello"} 313086115212 (291.58 GB)
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 59184.5 (16h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1775421
telemt_connections_bad_total 161744
telemt_connections_current 2917
telemt_connections_me_current 2917
telemt_handshake_timeouts_total 46924
telemt_upstream_connect_attempt_total 35288
telemt_upstream_connect_success_total 34829
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 35233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2850
telemt_me_reconnect_success_total 1321
telemt_me_reader_eof_total 1219
telemt_me_idle_close_by_peer_total 1219
telemt_me_route_drop_no_conn_total 995507
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1361703
telemt_me_endpoint_quarantine_total 506
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 468
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
telemt_me_writers_active_current 127
telemt_desync_total 6014
telemt_desync_full_logged_total 3450
telemt_desync_suppressed_total 2564
telemt_desync_frames_bucket_total{bucket="1_2"} 1339
telemt_desync_frames_bucket_total{bucket="3_10"} 2352
telemt_desync_frames_bucket_total{bucket="gt_10"} 2323
telemt_pool_swap_total 59
telemt_pool_force_close_total 1610
telemt_me_writer_close_signal_drop_total 135
telemt_me_draining_writers_reap_progress_total 23919
telemt_me_writer_removed_unexpected_total 1187
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2550
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22548
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22309
telemt_me_writer_teardown_success_total{mode="normal"} 25098
telemt_me_writer_teardown_noop_total 23919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49017
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.417233
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49017
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 135
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1102
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 1367851
telemt_user_connections_current{user="hello"} 2917
telemt_user_octets_from_client{user="hello"} 19868162906 (18.50 GB)
telemt_user_octets_to_client{user="hello"} 431412331684 (401.78 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 1620
telemt_user_unique_ips_recent_window{user="hello"} 516
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 134044.4 (37h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10534921
telemt_connections_bad_total 933198
telemt_connections_current 5430
telemt_connections_me_current 5430
telemt_handshake_timeouts_total 302851
telemt_upstream_connect_attempt_total 49169
telemt_upstream_connect_success_total 49089
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 49097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26687
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2058
telemt_me_reconnect_success_total 1056
telemt_me_reader_eof_total 1049
telemt_me_idle_close_by_peer_total 1048
telemt_me_route_drop_no_conn_total 6562190
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8311306
telemt_me_endpoint_quarantine_total 851
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 999
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 35665
telemt_desync_full_logged_total 11631
telemt_desync_suppressed_total 24034
telemt_desync_frames_bucket_total{bucket="1_2"} 7957
telemt_desync_frames_bucket_total{bucket="3_10"} 13843
telemt_desync_frames_bucket_total{bucket="gt_10"} 13865
telemt_pool_swap_total 144
telemt_pool_force_close_total 4820
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 738
telemt_me_draining_writers_reap_progress_total 44849
telemt_me_writer_removed_unexpected_total 1007
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3805
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41501
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4497
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 323
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40029
telemt_me_writer_teardown_success_total{mode="normal"} 45306
telemt_me_writer_teardown_noop_total 44893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90199
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 200.473962
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90199
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 738
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 928
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 8301000
telemt_user_connections_current{user="hello"} 5430
telemt_user_octets_from_client{user="hello"} 133093039632 (123.95 GB)
telemt_user_octets_to_client{user="hello"} 2651634024524 (2.41 TB)
telemt_user_unique_ips_current{user="hello"} 2103
telemt_user_unique_ips_recent_window{user="hello"} 721
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 134046.5 (37h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8462729
telemt_connections_bad_total 768101
telemt_connections_current 4430
telemt_connections_me_current 4430
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 266755
telemt_upstream_connect_attempt_total 55347
telemt_upstream_connect_success_total 54853
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 55103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3007
telemt_me_reconnect_success_total 1173
telemt_me_reader_eof_total 1081
telemt_me_idle_close_by_peer_total 1081
telemt_me_route_drop_no_conn_total 2928357
telemt_me_route_drop_channel_closed_total 347
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6259513
telemt_me_endpoint_quarantine_total 850
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1029
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
telemt_me_writers_active_current 47
telemt_desync_total 28643
telemt_desync_full_logged_total 9736
telemt_desync_suppressed_total 18907
telemt_desync_frames_bucket_total{bucket="1_2"} 6920
telemt_desync_frames_bucket_total{bucket="3_10"} 11093
telemt_desync_frames_bucket_total{bucket="gt_10"} 10630
telemt_pool_swap_total 145
telemt_pool_force_close_total 4395
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 487
telemt_me_draining_writers_reap_progress_total 43197
telemt_me_writer_removed_unexpected_total 1097
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3733
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40456
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4098
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 297
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38802
telemt_me_writer_teardown_success_total{mode="normal"} 44189
telemt_me_writer_teardown_noop_total 43203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87392
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 62.898524
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87392
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 487
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 996
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6181682
telemt_user_connections_current{user="hello"} 4430
telemt_user_octets_from_client{user="hello"} 167269145171 (155.78 GB)
telemt_user_octets_to_client{user="hello"} 2936699223870 (2.67 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1834
telemt_user_unique_ips_recent_window{user="hello"} 612
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 134010.1 (37h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8114184
telemt_connections_bad_total 682548
telemt_connections_current 4132
telemt_connections_me_current 4132
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 264864
telemt_upstream_connect_attempt_total 59910
telemt_upstream_connect_success_total 59215
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 59362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3416
telemt_me_reconnect_success_total 1457
telemt_me_reader_eof_total 1346
telemt_me_idle_close_by_peer_total 1346
telemt_me_route_drop_no_conn_total 3366609
telemt_me_route_drop_channel_closed_total 218
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6057174
telemt_me_endpoint_quarantine_total 924
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 982
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
telemt_me_writers_active_current 44
telemt_desync_total 28348
telemt_desync_full_logged_total 9628
telemt_desync_suppressed_total 18720
telemt_desync_frames_bucket_total{bucket="1_2"} 6844
telemt_desync_frames_bucket_total{bucket="3_10"} 10889
telemt_desync_frames_bucket_total{bucket="gt_10"} 10615
telemt_pool_swap_total 141
telemt_pool_force_close_total 4281
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 504
telemt_me_draining_writers_reap_progress_total 44138
telemt_me_writer_removed_unexpected_total 1372
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4130
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41335
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3902
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 379
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39857
telemt_me_writer_teardown_success_total{mode="normal"} 45465
telemt_me_writer_teardown_noop_total 44155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89620
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.295893
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89620
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 504
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 1283
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 6049722
telemt_user_connections_current{user="hello"} 4132
telemt_user_octets_from_client{user="hello"} 152836643831 (142.34 GB)
telemt_user_octets_to_client{user="hello"} 2649331206935 (2.41 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1659
telemt_user_unique_ips_recent_window{user="hello"} 636
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 4289.3 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1790183
telemt_connections_bad_total 143899
telemt_connections_current 6298
telemt_connections_me_current 6298
telemt_handshake_timeouts_total 22514
telemt_upstream_connect_attempt_total 8152
telemt_upstream_connect_success_total 7728
telemt_upstream_connect_fail_total 338
telemt_upstream_connect_attempts_per_request{bucket="1"} 8066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1354
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2670
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 338
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 315
telemt_me_reconnect_success_total 113
telemt_me_reader_eof_total 62
telemt_me_idle_close_by_peer_total 62
telemt_me_route_drop_no_conn_total 3942167
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1477294
telemt_me_endpoint_quarantine_total 23
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 2428
telemt_desync_full_logged_total 600
telemt_desync_suppressed_total 1828
telemt_desync_frames_bucket_total{bucket="1_2"} 464
telemt_desync_frames_bucket_total{bucket="3_10"} 914
telemt_desync_frames_bucket_total{bucket="gt_10"} 1050
telemt_pool_swap_total 3
telemt_pool_force_close_total 125
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 1095
telemt_me_writer_removed_unexpected_total 106
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1017
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 970
telemt_me_writer_teardown_success_total{mode="normal"} 1201
telemt_me_writer_teardown_noop_total 1095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.575062
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 68
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1483251
telemt_user_connections_current{user="hello"} 6298
telemt_user_octets_from_client{user="hello"} 8594751998 (8.00 GB)
telemt_user_octets_to_client{user="hello"} 43953813179 (40.94 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2369
telemt_user_unique_ips_recent_window{user="hello"} 1353
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 134016.2 (37h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7727389
telemt_connections_bad_total 686090
telemt_connections_current 4686
telemt_connections_me_current 4686
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 159292
telemt_upstream_connect_attempt_total 76029
telemt_upstream_connect_success_total 75203
telemt_upstream_connect_fail_total 706
telemt_upstream_connect_attempts_per_request{bucket="1"} 75909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28984
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 444
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 706
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70462
telemt_me_reconnect_success_total 2080
telemt_me_reader_eof_total 1825
telemt_me_idle_close_by_peer_total 1824
telemt_me_route_drop_no_conn_total 3136334
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6085711
telemt_me_endpoint_quarantine_total 896
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1009
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
telemt_me_writers_active_current 44
telemt_desync_total 30805
telemt_desync_full_logged_total 10671
telemt_desync_suppressed_total 20134
telemt_desync_frames_bucket_total{bucket="1_2"} 6224
telemt_desync_frames_bucket_total{bucket="3_10"} 11825
telemt_desync_frames_bucket_total{bucket="gt_10"} 12756
telemt_pool_swap_total 139
telemt_pool_force_close_total 4031
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 483
telemt_me_draining_writers_reap_progress_total 46361
telemt_me_writer_removed_unexpected_total 1854
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4719
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43523
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3544
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 487
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42330
telemt_me_writer_teardown_success_total{mode="normal"} 48242
telemt_me_writer_teardown_noop_total 46362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94604
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.699569
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94604
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 483
telemt_me_refill_failed_total 4230
telemt_me_writer_restored_same_endpoint_total 1726
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 6083445
telemt_user_connections_current{user="hello"} 4686
telemt_user_octets_from_client{user="hello"} 151215206099 (140.83 GB)
telemt_user_octets_to_client{user="hello"} 2478515034131 (2.25 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1907
telemt_user_unique_ips_recent_window{user="hello"} 678
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 70852.1 (19h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6469294
telemt_connections_bad_total 248653
telemt_connections_current 4015
telemt_connections_me_current 4015
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2622341
telemt_upstream_connect_attempt_total 37446
telemt_upstream_connect_success_total 37182
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 37439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_reconnect_attempts_total 47489
telemt_me_reconnect_success_total 1260
telemt_me_reader_eof_total 923
telemt_me_idle_close_by_peer_total 923
telemt_me_route_drop_no_conn_total 1718123
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3216096
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 541
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 17658
telemt_desync_full_logged_total 5941
telemt_desync_suppressed_total 11717
telemt_desync_frames_bucket_total{bucket="1_2"} 3541
telemt_desync_frames_bucket_total{bucket="3_10"} 6754
telemt_desync_frames_bucket_total{bucket="gt_10"} 7363
telemt_pool_swap_total 75
telemt_pool_force_close_total 2279
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 218
telemt_me_draining_writers_reap_progress_total 25405
telemt_me_writer_removed_unexpected_total 993
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2218
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24203
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1960
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 319
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23126
telemt_me_writer_teardown_success_total{mode="normal"} 26421
telemt_me_writer_teardown_noop_total 25411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51832
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.845425
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51832
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 218
telemt_me_refill_failed_total 2688
telemt_me_writer_restored_same_endpoint_total 1124
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3216437
telemt_user_connections_current{user="hello"} 4015
telemt_user_octets_from_client{user="hello"} 79491631784 (74.03 GB)
telemt_user_octets_to_client{user="hello"} 1369192970122 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1669
telemt_user_unique_ips_recent_window{user="hello"} 617
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 51823.1 (14h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499360
telemt_connections_bad_total 3708
telemt_connections_current 1047
telemt_connections_me_current 1047
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9256
telemt_upstream_connect_attempt_total 27395
telemt_upstream_connect_success_total 27332
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 273
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1129
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 452
telemt_me_idle_close_by_peer_total 452
telemt_me_route_drop_no_conn_total 162777
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 451141
telemt_me_endpoint_quarantine_total 480
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 445
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
telemt_desync_total 2142
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1512
telemt_desync_frames_bucket_total{bucket="1_2"} 633
telemt_desync_frames_bucket_total{bucket="3_10"} 823
telemt_desync_frames_bucket_total{bucket="gt_10"} 686
telemt_pool_swap_total 55
telemt_pool_force_close_total 1299
telemt_me_writer_close_signal_drop_total 62
telemt_me_draining_writers_reap_progress_total 22162
telemt_me_writer_removed_unexpected_total 435
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1622
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20992
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1248
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20863
telemt_me_writer_teardown_success_total{mode="normal"} 22614
telemt_me_writer_teardown_noop_total 22162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44776
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.153134
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44776
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 62
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 401
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 453206
telemt_user_connections_current{user="hello"} 1047
telemt_user_octets_from_client{user="hello"} 9102406649 (8.48 GB)
telemt_user_octets_to_client{user="hello"} 221996883775 (206.75 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 134020.7 (37h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9505974
telemt_connections_bad_total 1112982
telemt_connections_current 5167
telemt_connections_me_current 5167
telemt_handshake_timeouts_total 257949
telemt_upstream_connect_attempt_total 51693
telemt_upstream_connect_success_total 51495
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 51647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_reconnect_attempts_total 1925
telemt_me_reconnect_success_total 1053
telemt_me_reader_eof_total 1025
telemt_me_idle_close_by_peer_total 1025
telemt_me_route_drop_no_conn_total 2693596
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7055026
telemt_me_endpoint_quarantine_total 945
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1014
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
telemt_desync_total 28509
telemt_desync_full_logged_total 9345
telemt_desync_suppressed_total 19164
telemt_desync_frames_bucket_total{bucket="1_2"} 7046
telemt_desync_frames_bucket_total{bucket="3_10"} 10374
telemt_desync_frames_bucket_total{bucket="gt_10"} 11089
telemt_pool_swap_total 148
telemt_pool_force_close_total 3993
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 486
telemt_me_draining_writers_reap_progress_total 46626
telemt_me_writer_removed_unexpected_total 985
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3744
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43898
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3885
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42633
telemt_me_writer_teardown_success_total{mode="normal"} 47642
telemt_me_writer_teardown_noop_total 46628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94270
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.927661
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94270
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 486
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 924
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7027565
telemt_user_connections_current{user="hello"} 5167
telemt_user_octets_from_client{user="hello"} 136288521460 (126.93 GB)
telemt_user_octets_to_client{user="hello"} 3285677415644 (2.99 TB)
telemt_user_unique_ips_current{user="hello"} 1974
telemt_user_unique_ips_recent_window{user="hello"} 734
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 134017.0 (37h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8249940
telemt_connections_bad_total 921769
telemt_connections_current 4536
telemt_connections_me_current 4537
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 215667
telemt_upstream_connect_attempt_total 76162
telemt_upstream_connect_success_total 75625
telemt_upstream_connect_fail_total 468
telemt_upstream_connect_attempts_per_request{bucket="1"} 76093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1966
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 468
telemt_me_reconnect_attempts_total 6500
telemt_me_reconnect_success_total 1516
telemt_me_reader_eof_total 1347
telemt_me_idle_close_by_peer_total 1347
telemt_me_seq_mismatch_total 63
telemt_me_route_drop_no_conn_total 2890518
telemt_me_route_drop_channel_closed_total 246
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6290760
telemt_me_endpoint_quarantine_total 1044
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 1014
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
telemt_desync_total 27580
telemt_desync_full_logged_total 9128
telemt_desync_suppressed_total 18452
telemt_desync_frames_bucket_total{bucket="1_2"} 6781
telemt_desync_frames_bucket_total{bucket="3_10"} 10150
telemt_desync_frames_bucket_total{bucket="gt_10"} 10649
telemt_pool_swap_total 145
telemt_pool_force_close_total 3920
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 484
telemt_me_draining_writers_reap_progress_total 45299
telemt_me_writer_removed_unexpected_total 1364
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4387
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42338
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3633
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 287
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41379
telemt_me_writer_teardown_success_total{mode="normal"} 46725
telemt_me_writer_teardown_noop_total 45303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92028
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.430011
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92028
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 484
telemt_me_refill_failed_total 287
telemt_me_writer_restored_same_endpoint_total 1185
telemt_me_writer_restored_fallback_total 87
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 6299215
telemt_user_connections_current{user="hello"} 4537
telemt_user_octets_from_client{user="hello"} 115006729185 (107.11 GB)
telemt_user_octets_to_client{user="hello"} 2680964677099 (2.44 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1875
telemt_user_unique_ips_recent_window{user="hello"} 640
```