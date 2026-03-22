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

# Server Metrics 2026-03-22 06:15:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 32957.9 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 621011
telemt_connections_bad_total 38732
telemt_connections_current 1250
telemt_connections_me_current 1250
telemt_handshake_timeouts_total 30571
telemt_upstream_connect_attempt_total 13495
telemt_upstream_connect_success_total 13494
telemt_upstream_connect_attempts_per_request{bucket="1"} 13494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8746
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 363
telemt_me_reconnect_success_total 212
telemt_me_reader_eof_total 208
telemt_me_idle_close_by_peer_total 208
telemt_me_route_drop_no_conn_total 227107
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514840
telemt_me_endpoint_quarantine_total 245
telemt_me_single_endpoint_shadow_rotate_total 273
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
telemt_desync_total 4355
telemt_desync_full_logged_total 1210
telemt_desync_suppressed_total 3145
telemt_desync_frames_bucket_total{bucket="1_2"} 1447
telemt_desync_frames_bucket_total{bucket="3_10"} 1642
telemt_desync_frames_bucket_total{bucket="gt_10"} 1266
telemt_pool_swap_total 36
telemt_pool_force_close_total 961
telemt_me_writer_close_signal_drop_total 104
telemt_me_draining_writers_reap_progress_total 12205
telemt_me_writer_removed_unexpected_total 205
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 843
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11554
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 951
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11244
telemt_me_writer_teardown_success_total{mode="normal"} 12397
telemt_me_writer_teardown_noop_total 12206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24603
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.227396
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24603
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 104
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 193
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 513744
telemt_user_connections_current{user="hello"} 1250
telemt_user_octets_from_client{user="hello"} 6611333996 (6.16 GB)
telemt_user_octets_to_client{user="hello"} 178561267556 (166.30 GB)
telemt_user_unique_ips_current{user="hello"} 531
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 46324.4 (12h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1074676
telemt_connections_bad_total 96944
telemt_connections_current 1404
telemt_connections_me_current 1404
telemt_handshake_timeouts_total 35601
telemt_upstream_connect_attempt_total 24503
telemt_upstream_connect_success_total 24165
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 24471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1860
telemt_me_reconnect_success_total 705
telemt_me_reader_eof_total 628
telemt_me_idle_close_by_peer_total 628
telemt_me_route_drop_no_conn_total 400362
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 821869
telemt_me_endpoint_quarantine_total 420
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 375
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
telemt_me_writers_active_current 90
telemt_desync_total 3454
telemt_desync_full_logged_total 2017
telemt_desync_suppressed_total 1437
telemt_desync_frames_bucket_total{bucket="1_2"} 727
telemt_desync_frames_bucket_total{bucket="3_10"} 1328
telemt_desync_frames_bucket_total{bucket="gt_10"} 1399
telemt_pool_swap_total 49
telemt_pool_force_close_total 1287
telemt_me_writer_close_signal_drop_total 98
telemt_me_draining_writers_reap_progress_total 19028
telemt_me_writer_removed_unexpected_total 602
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1669
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17975
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17741
telemt_me_writer_teardown_success_total{mode="normal"} 19644
telemt_me_writer_teardown_noop_total 19028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38672
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.414941
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38672
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 98
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 543
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 823534
telemt_user_connections_current{user="hello"} 1404
telemt_user_octets_from_client{user="hello"} 13486354523 (12.56 GB)
telemt_user_octets_to_client{user="hello"} 304573847114 (283.66 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 855
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 121184.2 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8522219
telemt_connections_bad_total 761218
telemt_connections_current 3375
telemt_connections_me_current 3375
telemt_handshake_timeouts_total 274820
telemt_upstream_connect_attempt_total 45005
telemt_upstream_connect_success_total 44927
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 44935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24420
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1715
telemt_me_reconnect_success_total 879
telemt_me_reader_eof_total 892
telemt_me_idle_close_by_peer_total 892
telemt_me_route_drop_no_conn_total 4714027
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6796757
telemt_me_endpoint_quarantine_total 769
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 911
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
telemt_desync_total 28953
telemt_desync_full_logged_total 9628
telemt_desync_suppressed_total 19325
telemt_desync_frames_bucket_total{bucket="1_2"} 6271
telemt_desync_frames_bucket_total{bucket="3_10"} 11289
telemt_desync_frames_bucket_total{bucket="gt_10"} 11393
telemt_pool_swap_total 131
telemt_pool_force_close_total 4324
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 650
telemt_me_draining_writers_reap_progress_total 41084
telemt_me_writer_removed_unexpected_total 858
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3401
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38047
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4073
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 251
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36760
telemt_me_writer_teardown_success_total{mode="normal"} 41448
telemt_me_writer_teardown_noop_total 41128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 170.834552
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 650
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 786
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 6787939
telemt_user_connections_current{user="hello"} 3375
telemt_user_octets_from_client{user="hello"} 115430525772 (107.50 GB)
telemt_user_octets_to_client{user="hello"} 2317708209712 (2.11 TB)
telemt_user_unique_ips_current{user="hello"} 1369
telemt_user_unique_ips_recent_window{user="hello"} 518
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 121185.7 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7039209
telemt_connections_bad_total 625630
telemt_connections_current 3666
telemt_connections_me_current 3666
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 234283
telemt_upstream_connect_attempt_total 48957
telemt_upstream_connect_success_total 48554
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 48760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2064
telemt_me_reconnect_success_total 940
telemt_me_reader_eof_total 920
telemt_me_idle_close_by_peer_total 920
telemt_me_route_drop_no_conn_total 2388670
telemt_me_route_drop_channel_closed_total 291
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5232535
telemt_me_endpoint_quarantine_total 766
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 934
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 24174
telemt_desync_full_logged_total 8313
telemt_desync_suppressed_total 15861
telemt_desync_frames_bucket_total{bucket="1_2"} 5793
telemt_desync_frames_bucket_total{bucket="3_10"} 9379
telemt_desync_frames_bucket_total{bucket="gt_10"} 9002
telemt_pool_swap_total 132
telemt_pool_force_close_total 3932
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 39511
telemt_me_writer_removed_unexpected_total 897
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3257
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37080
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3710
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 222
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35579
telemt_me_writer_teardown_success_total{mode="normal"} 40337
telemt_me_writer_teardown_noop_total 39517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79854
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.501431
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79854
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 821
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 5153794
telemt_user_connections_current{user="hello"} 3666
telemt_user_octets_from_client{user="hello"} 148626983425 (138.42 GB)
telemt_user_octets_to_client{user="hello"} 2481343456383 (2.26 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1449
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 121150.1 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6833882
telemt_connections_bad_total 573163
telemt_connections_current 2935
telemt_connections_me_current 2935
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 230045
telemt_upstream_connect_attempt_total 55388
telemt_upstream_connect_success_total 54796
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 54940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25540
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 2582
telemt_me_reconnect_success_total 1114
telemt_me_reader_eof_total 1037
telemt_me_idle_close_by_peer_total 1037
telemt_me_route_drop_no_conn_total 2467522
telemt_me_route_drop_channel_closed_total 153
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5085476
telemt_me_endpoint_quarantine_total 868
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 17
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 17
telemt_me_single_endpoint_shadow_rotate_total 899
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
telemt_me_writers_active_current 44
telemt_desync_total 24110
telemt_desync_full_logged_total 8179
telemt_desync_suppressed_total 15931
telemt_desync_frames_bucket_total{bucket="1_2"} 5854
telemt_desync_frames_bucket_total{bucket="3_10"} 9257
telemt_desync_frames_bucket_total{bucket="gt_10"} 8999
telemt_pool_swap_total 130
telemt_pool_force_close_total 3796
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 426
telemt_me_draining_writers_reap_progress_total 40463
telemt_me_writer_removed_unexpected_total 1028
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3511
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37997
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3548
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 248
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36667
telemt_me_writer_teardown_success_total{mode="normal"} 41508
telemt_me_writer_teardown_noop_total 40475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81983
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 38.120582
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81983
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 426
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 961
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 5079690
telemt_user_connections_current{user="hello"} 2935
telemt_user_octets_from_client{user="hello"} 139313454907 (129.75 GB)
telemt_user_octets_to_client{user="hello"} 2310789226743 (2.10 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1199
telemt_user_unique_ips_recent_window{user="hello"} 419
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 121188.9 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21833922
telemt_connections_bad_total 1848818
telemt_connections_current 4866
telemt_connections_me_current 4866
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 660941
telemt_upstream_connect_attempt_total 225087
telemt_upstream_connect_success_total 205937
telemt_upstream_connect_fail_total 17224
telemt_upstream_connect_attempts_per_request{bucket="1"} 223161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17224
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66315
telemt_me_reconnect_success_total 2582
telemt_me_reader_eof_total 1620
telemt_me_idle_close_by_peer_total 1619
telemt_me_route_drop_no_conn_total 41292672
telemt_me_route_drop_channel_closed_total 131
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17546447
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 949
telemt_me_single_endpoint_outage_enter_total 154
telemt_me_single_endpoint_outage_exit_total 154
telemt_me_single_endpoint_outage_reconnect_attempt_total 323
telemt_me_single_endpoint_outage_reconnect_success_total 81
telemt_me_single_endpoint_quarantine_bypass_total 323
telemt_me_single_endpoint_shadow_rotate_total 952
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
telemt_me_writers_active_current 44
telemt_desync_total 33956
telemt_desync_full_logged_total 10186
telemt_desync_suppressed_total 23770
telemt_desync_frames_bucket_total{bucket="1_2"} 7484
telemt_desync_frames_bucket_total{bucket="3_10"} 15051
telemt_desync_frames_bucket_total{bucket="gt_10"} 11421
telemt_pool_swap_total 125
telemt_pool_force_close_total 3979
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 903
telemt_me_draining_writers_reap_progress_total 38056
telemt_me_writer_removed_unexpected_total 2397
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5167
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35034
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3416
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 563
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34077
telemt_me_writer_teardown_success_total{mode="normal"} 40201
telemt_me_writer_teardown_noop_total 38083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78284
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 227.198324
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78284
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 903
telemt_me_refill_failed_total 3862
telemt_me_writer_restored_same_endpoint_total 1755
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 17699141
telemt_user_connections_current{user="hello"} 4866
telemt_user_octets_from_client{user="hello"} 261894059313 (243.91 GB)
telemt_user_octets_to_client{user="hello"} 1360500658575 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 454370
telemt_user_msgs_to_client{user="hello"} 903931
telemt_user_unique_ips_current{user="hello"} 1782
telemt_user_unique_ips_recent_window{user="hello"} 878
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 121156.4 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6574943
telemt_connections_bad_total 617201
telemt_connections_current 3373
telemt_connections_me_current 3373
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 137382
telemt_upstream_connect_attempt_total 64044
telemt_upstream_connect_success_total 63305
telemt_upstream_connect_fail_total 633
telemt_upstream_connect_attempts_per_request{bucket="1"} 63938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 633
telemt_me_reconnect_attempts_total 69967
telemt_me_reconnect_success_total 1905
telemt_me_reader_eof_total 1681
telemt_me_idle_close_by_peer_total 1680
telemt_me_route_drop_no_conn_total 2522092
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5128102
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 921
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
telemt_desync_total 25513
telemt_desync_full_logged_total 8924
telemt_desync_suppressed_total 16589
telemt_desync_frames_bucket_total{bucket="1_2"} 5048
telemt_desync_frames_bucket_total{bucket="3_10"} 9816
telemt_desync_frames_bucket_total{bucket="gt_10"} 10649
telemt_pool_swap_total 126
telemt_pool_force_close_total 3608
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 426
telemt_me_draining_writers_reap_progress_total 42707
telemt_me_writer_removed_unexpected_total 1714
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4292
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40164
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3202
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39099
telemt_me_writer_teardown_success_total{mode="normal"} 44456
telemt_me_writer_teardown_noop_total 42708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87164
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.707754
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87164
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 426
telemt_me_refill_failed_total 4216
telemt_me_writer_restored_same_endpoint_total 1591
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 5119911
telemt_user_connections_current{user="hello"} 3373
telemt_user_octets_from_client{user="hello"} 131548260428 (122.51 GB)
telemt_user_octets_to_client{user="hello"} 2136638712802 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1442
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 57992.3 (16h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4662089
telemt_connections_bad_total 195843
telemt_connections_current 2842
telemt_connections_me_current 2842
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1837324
telemt_upstream_connect_attempt_total 32851
telemt_upstream_connect_success_total 32631
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 32844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_reconnect_attempts_total 46173
telemt_me_reconnect_success_total 1051
telemt_me_reader_eof_total 742
telemt_me_idle_close_by_peer_total 742
telemt_me_route_drop_no_conn_total 1157167
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2316715
telemt_me_endpoint_quarantine_total 414
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 449
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 12412
telemt_desync_full_logged_total 4275
telemt_desync_suppressed_total 8137
telemt_desync_frames_bucket_total{bucket="1_2"} 2395
telemt_desync_frames_bucket_total{bucket="3_10"} 4748
telemt_desync_frames_bucket_total{bucket="gt_10"} 5269
telemt_pool_swap_total 63
telemt_pool_force_close_total 1848
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 162
telemt_me_draining_writers_reap_progress_total 21372
telemt_me_writer_removed_unexpected_total 812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1816
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20398
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1635
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19524
telemt_me_writer_teardown_success_total{mode="normal"} 22214
telemt_me_writer_teardown_noop_total 21374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43588
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.760242
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43588
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 162
telemt_me_refill_failed_total 2621
telemt_me_writer_restored_same_endpoint_total 936
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2318825
telemt_user_connections_current{user="hello"} 2842
telemt_user_octets_from_client{user="hello"} 60898202972 (56.72 GB)
telemt_user_octets_to_client{user="hello"} 1028153611018 (957.54 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1216
telemt_user_unique_ips_recent_window{user="hello"} 448
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 38963.1 (10h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285280
telemt_connections_bad_total 2030
telemt_connections_current 618
telemt_connections_me_current 618
telemt_handshake_timeouts_total 6893
telemt_upstream_connect_attempt_total 18752
telemt_upstream_connect_success_total 18706
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 18748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 485
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 256
telemt_me_idle_close_by_peer_total 256
telemt_me_route_drop_no_conn_total 82274
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256305
telemt_me_endpoint_quarantine_total 370
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 338
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
telemt_desync_total 1292
telemt_desync_full_logged_total 361
telemt_desync_suppressed_total 931
telemt_desync_frames_bucket_total{bucket="1_2"} 440
telemt_desync_frames_bucket_total{bucket="3_10"} 497
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 43
telemt_pool_force_close_total 962
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 16999
telemt_me_writer_removed_unexpected_total 245
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1090
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16165
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 960
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16037
telemt_me_writer_teardown_success_total{mode="normal"} 17255
telemt_me_writer_teardown_noop_total 16999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34254
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.352302
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34254
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 255899
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 4317723276 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 152514876856 (142.04 GB)
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 121160.8 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7973314
telemt_connections_bad_total 803582
telemt_connections_current 3545
telemt_connections_me_current 3545
telemt_handshake_timeouts_total 225612
telemt_upstream_connect_attempt_total 47684
telemt_upstream_connect_success_total 47511
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 1762
telemt_me_reconnect_success_total 944
telemt_me_reader_eof_total 928
telemt_me_idle_close_by_peer_total 928
telemt_me_route_drop_no_conn_total 2256148
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5950320
telemt_me_endpoint_quarantine_total 865
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 929
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
telemt_me_writers_active_current 46
telemt_desync_total 23362
telemt_desync_full_logged_total 7691
telemt_desync_suppressed_total 15671
telemt_desync_frames_bucket_total{bucket="1_2"} 5827
telemt_desync_frames_bucket_total{bucket="3_10"} 8529
telemt_desync_frames_bucket_total{bucket="gt_10"} 9006
telemt_pool_swap_total 134
telemt_pool_force_close_total 3572
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 422
telemt_me_draining_writers_reap_progress_total 43038
telemt_me_writer_removed_unexpected_total 891
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3374
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40582
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3481
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39466
telemt_me_writer_teardown_success_total{mode="normal"} 43956
telemt_me_writer_teardown_noop_total 43040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86996
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.203701
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86996
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 422
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 840
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 5924629
telemt_user_connections_current{user="hello"} 3545
telemt_user_octets_from_client{user="hello"} 116159700260 (108.18 GB)
telemt_user_octets_to_client{user="hello"} 2782556008676 (2.53 TB)
telemt_user_unique_ips_current{user="hello"} 1405
telemt_user_unique_ips_recent_window{user="hello"} 531
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 121157.6 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6946107
telemt_connections_bad_total 685544
telemt_connections_current 3620
telemt_connections_me_current 3620
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 187019
telemt_upstream_connect_attempt_total 63464
telemt_upstream_connect_success_total 62978
telemt_upstream_connect_fail_total 423
telemt_upstream_connect_attempts_per_request{bucket="1"} 63401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 423
telemt_me_reconnect_attempts_total 5860
telemt_me_reconnect_success_total 1309
telemt_me_reader_eof_total 1175
telemt_me_idle_close_by_peer_total 1175
telemt_me_seq_mismatch_total 58
telemt_me_route_drop_no_conn_total 2314970
telemt_me_route_drop_channel_closed_total 193
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5316408
telemt_me_endpoint_quarantine_total 956
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 929
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
telemt_me_writers_active_current 47
telemt_desync_total 22266
telemt_desync_full_logged_total 7411
telemt_desync_suppressed_total 14855
telemt_desync_frames_bucket_total{bucket="1_2"} 5583
telemt_desync_frames_bucket_total{bucket="3_10"} 8138
telemt_desync_frames_bucket_total{bucket="gt_10"} 8545
telemt_pool_swap_total 132
telemt_pool_force_close_total 3519
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 423
telemt_me_draining_writers_reap_progress_total 41528
telemt_me_writer_removed_unexpected_total 1188
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3926
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38850
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3294
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 225
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38009
telemt_me_writer_teardown_success_total{mode="normal"} 42776
telemt_me_writer_teardown_noop_total 41532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84308
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.905586
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84308
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 423
telemt_me_refill_failed_total 262
telemt_me_writer_restored_same_endpoint_total 1018
telemt_me_writer_restored_fallback_total 77
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 5318747
telemt_user_connections_current{user="hello"} 3620
telemt_user_octets_from_client{user="hello"} 99368953313 (92.54 GB)
telemt_user_octets_to_client{user="hello"} 2310943039288 (2.10 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1490
telemt_user_unique_ips_recent_window{user="hello"} 502
```