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

# Server Metrics 2026-03-22 06:41:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 34484.1 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 670037
telemt_connections_bad_total 41514
telemt_connections_current 1366
telemt_connections_me_current 1366
telemt_handshake_timeouts_total 32480
telemt_upstream_connect_attempt_total 14129
telemt_upstream_connect_success_total 14128
telemt_upstream_connect_attempts_per_request{bucket="1"} 14128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 371
telemt_me_reconnect_success_total 220
telemt_me_reader_eof_total 216
telemt_me_idle_close_by_peer_total 216
telemt_me_route_drop_no_conn_total 240496
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 554643
telemt_me_endpoint_quarantine_total 255
telemt_me_single_endpoint_shadow_rotate_total 286
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
telemt_me_writers_active_current 45
telemt_desync_total 4634
telemt_desync_full_logged_total 1294
telemt_desync_suppressed_total 3340
telemt_desync_frames_bucket_total{bucket="1_2"} 1519
telemt_desync_frames_bucket_total{bucket="3_10"} 1730
telemt_desync_frames_bucket_total{bucket="gt_10"} 1385
telemt_pool_swap_total 38
telemt_pool_force_close_total 1018
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 12791
telemt_me_writer_removed_unexpected_total 213
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 889
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12102
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1007
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11773
telemt_me_writer_teardown_success_total{mode="normal"} 12991
telemt_me_writer_teardown_noop_total 12792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25783
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.243486
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25783
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 201
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 553519
telemt_user_connections_current{user="hello"} 1366
telemt_user_octets_from_client{user="hello"} 7763464520 (7.23 GB)
telemt_user_octets_to_client{user="hello"} 193952102464 (180.63 GB)
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 47850.1 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1138238
telemt_connections_bad_total 109105
telemt_connections_current 1752
telemt_connections_me_current 1752
telemt_handshake_timeouts_total 36815
telemt_upstream_connect_attempt_total 25267
telemt_upstream_connect_success_total 24897
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 25222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1892
telemt_me_reconnect_success_total 731
telemt_me_reader_eof_total 647
telemt_me_idle_close_by_peer_total 647
telemt_me_route_drop_no_conn_total 420745
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 864195
telemt_me_endpoint_quarantine_total 436
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 382
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
telemt_me_writers_active_current 52
telemt_me_writers_warm_current 34
telemt_desync_total 3653
telemt_desync_full_logged_total 2134
telemt_desync_suppressed_total 1519
telemt_desync_frames_bucket_total{bucket="1_2"} 772
telemt_desync_frames_bucket_total{bucket="3_10"} 1410
telemt_desync_frames_bucket_total{bucket="gt_10"} 1471
telemt_pool_swap_total 50
telemt_pool_force_close_total 1353
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 19749
telemt_me_writer_removed_unexpected_total 621
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1712
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18642
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1292
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18396
telemt_me_writer_teardown_success_total{mode="normal"} 20354
telemt_me_writer_teardown_noop_total 19749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40103
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.079938
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40103
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 560
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 865829
telemt_user_connections_current{user="hello"} 1752
telemt_user_octets_from_client{user="hello"} 14007602611 (13.05 GB)
telemt_user_octets_to_client{user="hello"} 322518529974 (300.37 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 1078
telemt_user_unique_ips_recent_window{user="hello"} 382
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 122710.0 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8710728
telemt_connections_bad_total 790815
telemt_connections_current 3532
telemt_connections_me_current 3532
telemt_handshake_timeouts_total 276991
telemt_upstream_connect_attempt_total 45491
telemt_upstream_connect_success_total 45413
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 45421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1742
telemt_me_reconnect_success_total 905
telemt_me_reader_eof_total 908
telemt_me_idle_close_by_peer_total 908
telemt_me_route_drop_no_conn_total 4773353
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6906333
telemt_me_endpoint_quarantine_total 783
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 923
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
telemt_me_writers_active_current 43
telemt_desync_total 29488
telemt_desync_full_logged_total 9787
telemt_desync_suppressed_total 19701
telemt_desync_frames_bucket_total{bucket="1_2"} 6384
telemt_desync_frames_bucket_total{bucket="3_10"} 11497
telemt_desync_frames_bucket_total{bucket="gt_10"} 11607
telemt_pool_swap_total 133
telemt_pool_force_close_total 4395
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 661
telemt_me_draining_writers_reap_progress_total 41541
telemt_me_writer_removed_unexpected_total 873
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3455
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38458
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4131
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 264
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37146
telemt_me_writer_teardown_success_total{mode="normal"} 41913
telemt_me_writer_teardown_noop_total 41585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83498
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 174.787897
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83498
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 661
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 808
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 6897333
telemt_user_connections_current{user="hello"} 3532
telemt_user_octets_from_client{user="hello"} 116560181988 (108.56 GB)
telemt_user_octets_to_client{user="hello"} 2355381081780 (2.14 TB)
telemt_user_unique_ips_current{user="hello"} 1439
telemt_user_unique_ips_recent_window{user="hello"} 534
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 122711.3 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7191373
telemt_connections_bad_total 634840
telemt_connections_current 3760
telemt_connections_me_current 3760
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 238324
telemt_upstream_connect_attempt_total 49462
telemt_upstream_connect_success_total 49055
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 49264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2610
telemt_me_reconnect_success_total 969
telemt_me_reader_eof_total 936
telemt_me_idle_close_by_peer_total 936
telemt_me_route_drop_no_conn_total 2426200
telemt_me_route_drop_channel_closed_total 296
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5327792
telemt_me_endpoint_quarantine_total 779
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 946
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_me_writers_active_current 54
telemt_desync_total 24679
telemt_desync_full_logged_total 8480
telemt_desync_suppressed_total 16199
telemt_desync_frames_bucket_total{bucket="1_2"} 5905
telemt_desync_frames_bucket_total{bucket="3_10"} 9585
telemt_desync_frames_bucket_total{bucket="gt_10"} 9189
telemt_pool_swap_total 134
telemt_pool_force_close_total 3991
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 412
telemt_me_draining_writers_reap_progress_total 39964
telemt_me_writer_removed_unexpected_total 913
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3304
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37502
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3766
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 225
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35973
telemt_me_writer_teardown_success_total{mode="normal"} 40806
telemt_me_writer_teardown_noop_total 39970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80776
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.292815
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80776
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 412
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 847
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 5249004
telemt_user_connections_current{user="hello"} 3760
telemt_user_octets_from_client{user="hello"} 150774994793 (140.42 GB)
telemt_user_octets_to_client{user="hello"} 2538043238103 (2.31 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1392
telemt_user_unique_ips_recent_window{user="hello"} 482
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 122675.3 (34h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6947456
telemt_connections_bad_total 579581
telemt_connections_current 3108
telemt_connections_me_current 3108
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 233591
telemt_upstream_connect_attempt_total 55931
telemt_upstream_connect_success_total 55323
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 55467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2647
telemt_me_reconnect_success_total 1123
telemt_me_reader_eof_total 1046
telemt_me_idle_close_by_peer_total 1046
telemt_me_route_drop_no_conn_total 2517629
telemt_me_route_drop_channel_closed_total 157
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5167752
telemt_me_endpoint_quarantine_total 876
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 912
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 24515
telemt_desync_full_logged_total 8321
telemt_desync_suppressed_total 16194
telemt_desync_frames_bucket_total{bucket="1_2"} 5940
telemt_desync_frames_bucket_total{bucket="3_10"} 9408
telemt_desync_frames_bucket_total{bucket="gt_10"} 9167
telemt_pool_swap_total 132
telemt_pool_force_close_total 3865
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 432
telemt_me_draining_writers_reap_progress_total 40920
telemt_me_writer_removed_unexpected_total 1037
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3572
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38398
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3609
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 256
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37055
telemt_me_writer_teardown_success_total{mode="normal"} 41970
telemt_me_writer_teardown_noop_total 40932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82902
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.155680
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82902
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 432
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 967
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 5161694
telemt_user_connections_current{user="hello"} 3108
telemt_user_octets_from_client{user="hello"} 140466479499 (130.82 GB)
telemt_user_octets_to_client{user="hello"} 2346847889043 (2.13 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1214
telemt_user_unique_ips_recent_window{user="hello"} 518
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 122714.7 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22246430
telemt_connections_bad_total 1882554
telemt_connections_current 4654
telemt_connections_me_current 4654
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 668024
telemt_upstream_connect_attempt_total 238260
telemt_upstream_connect_success_total 218648
telemt_upstream_connect_fail_total 17674
telemt_upstream_connect_attempts_per_request{bucket="1"} 236322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51135
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17674
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66387
telemt_me_reconnect_success_total 2616
telemt_me_reader_eof_total 1646
telemt_me_idle_close_by_peer_total 1644
telemt_me_route_drop_no_conn_total 42109068
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17876027
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 961
telemt_me_single_endpoint_outage_enter_total 155
telemt_me_single_endpoint_outage_exit_total 155
telemt_me_single_endpoint_outage_reconnect_attempt_total 324
telemt_me_single_endpoint_outage_reconnect_success_total 81
telemt_me_single_endpoint_quarantine_bypass_total 324
telemt_me_single_endpoint_shadow_rotate_total 963
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 34494
telemt_desync_full_logged_total 10373
telemt_desync_suppressed_total 24121
telemt_desync_frames_bucket_total{bucket="1_2"} 7639
telemt_desync_frames_bucket_total{bucket="3_10"} 15226
telemt_desync_frames_bucket_total{bucket="gt_10"} 11629
telemt_pool_swap_total 127
telemt_pool_force_close_total 4025
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 920
telemt_me_draining_writers_reap_progress_total 38476
telemt_me_writer_removed_unexpected_total 2422
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5222
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35407
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3450
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 575
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34451
telemt_me_writer_teardown_success_total{mode="normal"} 40629
telemt_me_writer_teardown_noop_total 38506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79135
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 279.133669
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79135
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 920
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1779
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 18040882
telemt_user_connections_current{user="hello"} 4654
telemt_user_octets_from_client{user="hello"} 267015334863 (248.68 GB)
telemt_user_octets_to_client{user="hello"} 1376944392942 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 500908
telemt_user_msgs_to_client{user="hello"} 1006528
telemt_user_unique_ips_current{user="hello"} 1742
telemt_user_unique_ips_recent_window{user="hello"} 810
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 122682.3 (34h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6672346
telemt_connections_bad_total 621170
telemt_connections_current 2764
telemt_connections_me_current 2764
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 138829
telemt_upstream_connect_attempt_total 64546
telemt_upstream_connect_success_total 63805
telemt_upstream_connect_fail_total 635
telemt_upstream_connect_attempts_per_request{bucket="1"} 64440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 635
telemt_me_reconnect_attempts_total 69995
telemt_me_reconnect_success_total 1914
telemt_me_reader_eof_total 1691
telemt_me_idle_close_by_peer_total 1690
telemt_me_route_drop_no_conn_total 2555630
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5213089
telemt_me_endpoint_quarantine_total 826
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 933
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 26018
telemt_desync_full_logged_total 9073
telemt_desync_suppressed_total 16945
telemt_desync_frames_bucket_total{bucket="1_2"} 5180
telemt_desync_frames_bucket_total{bucket="3_10"} 10000
telemt_desync_frames_bucket_total{bucket="gt_10"} 10838
telemt_pool_swap_total 128
telemt_pool_force_close_total 3672
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 433
telemt_me_draining_writers_reap_progress_total 43148
telemt_me_writer_removed_unexpected_total 1722
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4330
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40577
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3263
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 409
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39476
telemt_me_writer_teardown_success_total{mode="normal"} 44907
telemt_me_writer_teardown_noop_total 43149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88056
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.913196
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88056
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 433
telemt_me_refill_failed_total 4217
telemt_me_writer_restored_same_endpoint_total 1598
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5204669
telemt_user_connections_current{user="hello"} 2764
telemt_user_octets_from_client{user="hello"} 134070058008 (124.86 GB)
telemt_user_octets_to_client{user="hello"} 2176737628646 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1126
telemt_user_unique_ips_recent_window{user="hello"} 480
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 59518.4 (16h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4823105
telemt_connections_bad_total 199228
telemt_connections_current 3866
telemt_connections_me_current 3866
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1902446
telemt_upstream_connect_attempt_total 33359
telemt_upstream_connect_success_total 33130
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 33352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_reconnect_attempts_total 46184
telemt_me_reconnect_success_total 1062
telemt_me_reader_eof_total 753
telemt_me_idle_close_by_peer_total 753
telemt_me_route_drop_no_conn_total 1189975
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2401166
telemt_me_endpoint_quarantine_total 420
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 455
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 12835
telemt_desync_full_logged_total 4428
telemt_desync_suppressed_total 8407
telemt_desync_frames_bucket_total{bucket="1_2"} 2507
telemt_desync_frames_bucket_total{bucket="3_10"} 4909
telemt_desync_frames_bucket_total{bucket="gt_10"} 5419
telemt_pool_swap_total 65
telemt_pool_force_close_total 1880
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 164
telemt_me_draining_writers_reap_progress_total 21789
telemt_me_writer_removed_unexpected_total 823
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1844
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20798
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1661
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 219
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19909
telemt_me_writer_teardown_success_total{mode="normal"} 22642
telemt_me_writer_teardown_noop_total 21791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44433
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.773158
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44433
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 164
telemt_me_refill_failed_total 2621
telemt_me_writer_restored_same_endpoint_total 947
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2403218
telemt_user_connections_current{user="hello"} 3866
telemt_user_octets_from_client{user="hello"} 62607460084 (58.31 GB)
telemt_user_octets_to_client{user="hello"} 1065465601074 (992.29 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1601
telemt_user_unique_ips_recent_window{user="hello"} 490
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 40488.9 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301494
telemt_connections_bad_total 2098
telemt_connections_current 593
telemt_connections_me_current 593
telemt_handshake_timeouts_total 7137
telemt_upstream_connect_attempt_total 19436
telemt_upstream_connect_success_total 19388
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 19432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 828
telemt_me_reconnect_success_total 279
telemt_me_reader_eof_total 274
telemt_me_idle_close_by_peer_total 274
telemt_me_route_drop_no_conn_total 88348
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 271865
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 349
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
telemt_me_writers_active_current 49
telemt_desync_total 1340
telemt_desync_full_logged_total 376
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 454
telemt_desync_frames_bucket_total{bucket="3_10"} 512
telemt_desync_frames_bucket_total{bucket="gt_10"} 374
telemt_pool_swap_total 44
telemt_pool_force_close_total 986
telemt_me_writer_close_signal_drop_total 36
telemt_me_draining_writers_reap_progress_total 17585
telemt_me_writer_removed_unexpected_total 262
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1131
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16728
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 984
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16599
telemt_me_writer_teardown_success_total{mode="normal"} 17859
telemt_me_writer_teardown_noop_total 17585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35444
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.367363
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35444
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 36
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 238
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 271453
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 4463997792 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 157169535428 (146.38 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 122686.6 (34h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8102318
telemt_connections_bad_total 826879
telemt_connections_current 3524
telemt_connections_me_current 3524
telemt_handshake_timeouts_total 228884
telemt_upstream_connect_attempt_total 48248
telemt_upstream_connect_success_total 48072
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 48209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1771
telemt_me_reconnect_success_total 952
telemt_me_reader_eof_total 936
telemt_me_idle_close_by_peer_total 936
telemt_me_route_drop_no_conn_total 2288942
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6049300
telemt_me_endpoint_quarantine_total 874
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 938
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
telemt_me_writers_active_current 44
telemt_desync_total 23870
telemt_desync_full_logged_total 7857
telemt_desync_suppressed_total 16013
telemt_desync_frames_bucket_total{bucket="1_2"} 5956
telemt_desync_frames_bucket_total{bucket="3_10"} 8701
telemt_desync_frames_bucket_total{bucket="gt_10"} 9213
telemt_pool_swap_total 136
telemt_pool_force_close_total 3630
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 43570
telemt_me_writer_removed_unexpected_total 899
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3416
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41080
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3538
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39940
telemt_me_writer_teardown_success_total{mode="normal"} 44496
telemt_me_writer_teardown_noop_total 43572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88068
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.265116
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88068
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 6023350
telemt_user_connections_current{user="hello"} 3524
telemt_user_octets_from_client{user="hello"} 118009797108 (109.91 GB)
telemt_user_octets_to_client{user="hello"} 2824609371356 (2.57 TB)
telemt_user_unique_ips_current{user="hello"} 1393
telemt_user_unique_ips_recent_window{user="hello"} 480
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 122683.3 (34h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7085394
telemt_connections_bad_total 723544
telemt_connections_current 3786
telemt_connections_me_current 3786
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 189424
telemt_upstream_connect_attempt_total 64013
telemt_upstream_connect_success_total 63524
telemt_upstream_connect_fail_total 426
telemt_upstream_connect_attempts_per_request{bucket="1"} 63950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25865
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 426
telemt_me_reconnect_attempts_total 5886
telemt_me_reconnect_success_total 1317
telemt_me_reader_eof_total 1182
telemt_me_idle_close_by_peer_total 1182
telemt_me_seq_mismatch_total 59
telemt_me_route_drop_no_conn_total 2349826
telemt_me_route_drop_channel_closed_total 197
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5412137
telemt_me_endpoint_quarantine_total 971
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 940
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 22819
telemt_desync_full_logged_total 7576
telemt_desync_suppressed_total 15243
telemt_desync_frames_bucket_total{bucket="1_2"} 5689
telemt_desync_frames_bucket_total{bucket="3_10"} 8341
telemt_desync_frames_bucket_total{bucket="gt_10"} 8789
telemt_pool_swap_total 134
telemt_pool_force_close_total 3579
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 42034
telemt_me_writer_removed_unexpected_total 1195
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3964
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39326
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3352
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 227
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38455
telemt_me_writer_teardown_success_total{mode="normal"} 43290
telemt_me_writer_teardown_noop_total 42038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85328
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.268596
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85328
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 263
telemt_me_writer_restored_same_endpoint_total 1023
telemt_me_writer_restored_fallback_total 78
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 5414112
telemt_user_connections_current{user="hello"} 3786
telemt_user_octets_from_client{user="hello"} 100871868853 (93.94 GB)
telemt_user_octets_to_client{user="hello"} 2352753440288 (2.14 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1481
telemt_user_unique_ips_recent_window{user="hello"} 539
```