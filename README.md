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

# Server Metrics 2026-03-21 23:57:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 10294.2 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160904
telemt_connections_bad_total 11277
telemt_connections_current 679
telemt_connections_me_current 679
telemt_handshake_timeouts_total 8956
telemt_upstream_connect_attempt_total 4165
telemt_upstream_connect_success_total 4164
telemt_upstream_connect_attempts_per_request{bucket="1"} 4164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 99
telemt_me_reconnect_success_total 65
telemt_me_reader_eof_total 66
telemt_me_idle_close_by_peer_total 66
telemt_me_route_drop_no_conn_total 33479
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131589
telemt_me_endpoint_quarantine_total 69
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 46
telemt_desync_total 802
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 553
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 259
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 11
telemt_pool_force_close_total 299
telemt_me_writer_close_signal_drop_total 19
telemt_me_draining_writers_reap_progress_total 3711
telemt_me_writer_removed_unexpected_total 62
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 273
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3488
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3412
telemt_me_writer_teardown_success_total{mode="normal"} 3761
telemt_me_writer_teardown_noop_total 3711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7472
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.313271
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7472
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 19
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 131419
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 1580057692 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 47657759580 (44.38 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 23660.1 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672901
telemt_connections_bad_total 35331
telemt_connections_current 342
telemt_connections_me_current 342
telemt_handshake_timeouts_total 25628
telemt_upstream_connect_attempt_total 10091
telemt_upstream_connect_success_total 9909
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 10073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_reconnect_attempts_total 853
telemt_me_reconnect_success_total 307
telemt_me_reader_eof_total 264
telemt_me_idle_close_by_peer_total 264
telemt_me_route_drop_no_conn_total 326291
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545677
telemt_me_endpoint_quarantine_total 212
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 193
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 2393
telemt_desync_full_logged_total 1371
telemt_desync_suppressed_total 1022
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 897
telemt_desync_frames_bucket_total{bucket="gt_10"} 986
telemt_pool_swap_total 26
telemt_pool_force_close_total 726
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 8884
telemt_me_writer_removed_unexpected_total 247
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 785
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8350
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 719
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8158
telemt_me_writer_teardown_success_total{mode="normal"} 9135
telemt_me_writer_teardown_noop_total 8884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18019
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.378606
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18019
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 544932
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 9140471308 (8.51 GB)
telemt_user_octets_to_client{user="hello"} 189988793736 (176.94 GB)
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 98520.2 (27h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7446809
telemt_connections_bad_total 590730
telemt_connections_current 1696
telemt_connections_me_current 1696
telemt_handshake_timeouts_total 241612
telemt_upstream_connect_attempt_total 35747
telemt_upstream_connect_success_total 35678
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 35685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1493
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 755
telemt_me_idle_close_by_peer_total 755
telemt_me_route_drop_no_conn_total 4499141
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6071455
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 733
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 25781
telemt_desync_full_logged_total 8518
telemt_desync_suppressed_total 17263
telemt_desync_frames_bucket_total{bucket="1_2"} 5536
telemt_desync_frames_bucket_total{bucket="3_10"} 10061
telemt_desync_frames_bucket_total{bucket="gt_10"} 10184
telemt_pool_swap_total 106
telemt_pool_force_close_total 3583
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 575
telemt_me_draining_writers_reap_progress_total 32584
telemt_me_writer_removed_unexpected_total 726
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2767
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30101
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3344
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29001
telemt_me_writer_teardown_success_total{mode="normal"} 32868
telemt_me_writer_teardown_noop_total 32628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65496
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 153.616012
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65496
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 575
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 666
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6063886
telemt_user_connections_current{user="hello"} 1696
telemt_user_octets_from_client{user="hello"} 103975736924 (96.83 GB)
telemt_user_octets_to_client{user="hello"} 1992571445176 (1.81 TB)
telemt_user_unique_ips_current{user="hello"} 805
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 98521.2 (27h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6124318
telemt_connections_bad_total 578277
telemt_connections_current 1454
telemt_connections_me_current 1454
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 202204
telemt_upstream_connect_attempt_total 39655
telemt_upstream_connect_success_total 39316
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 39495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1805
telemt_me_reconnect_success_total 769
telemt_me_reader_eof_total 747
telemt_me_idle_close_by_peer_total 747
telemt_me_route_drop_no_conn_total 2173780
telemt_me_route_drop_channel_closed_total 254
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4587874
telemt_me_endpoint_quarantine_total 605
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 753
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
telemt_me_writers_active_current 43
telemt_desync_total 22042
telemt_desync_full_logged_total 7457
telemt_desync_suppressed_total 14585
telemt_desync_frames_bucket_total{bucket="1_2"} 5312
telemt_desync_frames_bucket_total{bucket="3_10"} 8552
telemt_desync_frames_bucket_total{bucket="gt_10"} 8178
telemt_pool_swap_total 108
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 31105
telemt_me_writer_removed_unexpected_total 721
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2640
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29121
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3047
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27859
telemt_me_writer_teardown_success_total{mode="normal"} 31761
telemt_me_writer_teardown_noop_total 31111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62872
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.986374
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62872
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 665
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4528691
telemt_user_connections_current{user="hello"} 1454
telemt_user_octets_from_client{user="hello"} 137985090773 (128.51 GB)
telemt_user_octets_to_client{user="hello"} 2118876636183 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 707
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 98485.3 (27h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6035207
telemt_connections_bad_total 540145
telemt_connections_current 1536
telemt_connections_me_current 1536
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 193081
telemt_upstream_connect_attempt_total 46124
telemt_upstream_connect_success_total 45816
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 45951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1808
telemt_me_reconnect_success_total 820
telemt_me_reader_eof_total 769
telemt_me_idle_close_by_peer_total 769
telemt_me_route_drop_no_conn_total 2103956
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4506356
telemt_me_endpoint_quarantine_total 666
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 737
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 21903
telemt_desync_full_logged_total 7292
telemt_desync_suppressed_total 14611
telemt_desync_frames_bucket_total{bucket="1_2"} 5360
telemt_desync_frames_bucket_total{bucket="3_10"} 8385
telemt_desync_frames_bucket_total{bucket="gt_10"} 8158
telemt_pool_swap_total 106
telemt_pool_force_close_total 3123
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 32604
telemt_me_writer_removed_unexpected_total 734
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2734
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30613
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2908
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29481
telemt_me_writer_teardown_success_total{mode="normal"} 33347
telemt_me_writer_teardown_noop_total 32615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65962
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.459534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65962
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 710
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4507665
telemt_user_connections_current{user="hello"} 1536
telemt_user_octets_from_client{user="hello"} 131624512471 (122.58 GB)
telemt_user_octets_to_client{user="hello"} 2065515341311 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 757
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 98525.2 (27h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19976042
telemt_connections_bad_total 1474734
telemt_connections_current 2216
telemt_connections_me_current 2216
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 577544
telemt_upstream_connect_attempt_total 189250
telemt_upstream_connect_success_total 171622
telemt_upstream_connect_fail_total 16036
telemt_upstream_connect_attempts_per_request{bucket="1"} 187658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40070
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8882
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16036
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64360
telemt_me_reconnect_success_total 2165
telemt_me_reader_eof_total 1351
telemt_me_idle_close_by_peer_total 1350
telemt_me_route_drop_no_conn_total 39448463
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16259420
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 762
telemt_me_single_endpoint_outage_enter_total 123
telemt_me_single_endpoint_outage_exit_total 123
telemt_me_single_endpoint_outage_reconnect_attempt_total 259
telemt_me_single_endpoint_outage_reconnect_success_total 62
telemt_me_single_endpoint_quarantine_bypass_total 259
telemt_me_single_endpoint_shadow_rotate_total 771
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 31317
telemt_desync_full_logged_total 9318
telemt_desync_suppressed_total 21999
telemt_desync_frames_bucket_total{bucket="1_2"} 6830
telemt_desync_frames_bucket_total{bucket="3_10"} 13865
telemt_desync_frames_bucket_total{bucket="gt_10"} 10622
telemt_pool_swap_total 101
telemt_pool_force_close_total 3346
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 760
telemt_me_draining_writers_reap_progress_total 30611
telemt_me_writer_removed_unexpected_total 2011
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4212
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28145
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2830
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27265
telemt_me_writer_teardown_success_total{mode="normal"} 32357
telemt_me_writer_teardown_noop_total 30637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62994
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 211.557350
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62994
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 760
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1498
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 16387354
telemt_user_connections_current{user="hello"} 2216
telemt_user_octets_from_client{user="hello"} 186769991068 (173.94 GB)
telemt_user_octets_to_client{user="hello"} 1115012486818 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1015
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 98492.1 (27h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5831929
telemt_connections_bad_total 550320
telemt_connections_current 1479
telemt_connections_me_current 1479
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 120358
telemt_upstream_connect_attempt_total 54283
telemt_upstream_connect_success_total 53661
telemt_upstream_connect_fail_total 531
telemt_upstream_connect_attempts_per_request{bucket="1"} 54192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 531
telemt_me_reconnect_attempts_total 68092
telemt_me_reconnect_success_total 1691
telemt_me_reader_eof_total 1467
telemt_me_idle_close_by_peer_total 1466
telemt_me_route_drop_no_conn_total 2356129
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4544563
telemt_me_endpoint_quarantine_total 656
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 739
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
telemt_me_writers_active_current 43
telemt_desync_total 22958
telemt_desync_full_logged_total 8039
telemt_desync_suppressed_total 14919
telemt_desync_frames_bucket_total{bucket="1_2"} 4348
telemt_desync_frames_bucket_total{bucket="3_10"} 8895
telemt_desync_frames_bucket_total{bucket="gt_10"} 9715
telemt_pool_swap_total 101
telemt_pool_force_close_total 2974
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 33993
telemt_me_writer_removed_unexpected_total 1513
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3618
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31911
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2573
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31019
telemt_me_writer_teardown_success_total{mode="normal"} 35529
telemt_me_writer_teardown_noop_total 33994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69523
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.926956
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69523
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 1427
telemt_me_writer_restored_fallback_total 29
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 4537670
telemt_user_connections_current{user="hello"} 1479
telemt_user_octets_from_client{user="hello"} 121789420692 (113.43 GB)
telemt_user_octets_to_client{user="hello"} 1854800713026 (1.69 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 733
telemt_user_unique_ips_recent_window{user="hello"} 289
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 35328.0 (9h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3702835
telemt_connections_bad_total 130990
telemt_connections_current 1064
telemt_connections_me_current 1064
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1541327
telemt_upstream_connect_attempt_total 22493
telemt_upstream_connect_success_total 22349
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 22486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 45589
telemt_me_reconnect_success_total 888
telemt_me_reader_eof_total 561
telemt_me_idle_close_by_peer_total 561
telemt_me_route_drop_no_conn_total 995231
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1790114
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 266
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9950
telemt_desync_full_logged_total 3410
telemt_desync_suppressed_total 6540
telemt_desync_frames_bucket_total{bucket="1_2"} 1761
telemt_desync_frames_bucket_total{bucket="3_10"} 3810
telemt_desync_frames_bucket_total{bucket="gt_10"} 4379
telemt_pool_swap_total 38
telemt_pool_force_close_total 1246
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 11968
telemt_me_writer_removed_unexpected_total 641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1302
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11327
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1040
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10722
telemt_me_writer_teardown_success_total{mode="normal"} 12629
telemt_me_writer_teardown_noop_total 11970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24599
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.088487
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24599
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 2597
telemt_me_writer_restored_same_endpoint_total 797
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1793850
telemt_user_connections_current{user="hello"} 1064
telemt_user_octets_from_client{user="hello"} 52496196608 (48.89 GB)
telemt_user_octets_to_client{user="hello"} 768124088570 (715.37 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 540
telemt_user_unique_ips_recent_window{user="hello"} 410
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 16298.9 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158975
telemt_connections_bad_total 1396
telemt_connections_current 339
telemt_connections_me_current 339
telemt_handshake_timeouts_total 3802
telemt_upstream_connect_attempt_total 7487
telemt_upstream_connect_success_total 7466
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 7485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 160
telemt_me_reconnect_success_total 98
telemt_me_reader_eof_total 98
telemt_me_idle_close_by_peer_total 98
telemt_me_route_drop_no_conn_total 45159
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139569
telemt_me_endpoint_quarantine_total 152
telemt_me_single_endpoint_shadow_rotate_total 143
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 973
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 731
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 18
telemt_pool_force_close_total 400
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 6688
telemt_me_writer_removed_unexpected_total 96
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 433
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6353
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 398
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6288
telemt_me_writer_teardown_success_total{mode="normal"} 6786
telemt_me_writer_teardown_noop_total 6688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13474
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.781279
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13474
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 90
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 139334
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 2566354552 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 80976419832 (75.42 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 98496.5 (27h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7023307
telemt_connections_bad_total 712402
telemt_connections_current 1736
telemt_connections_me_current 1736
telemt_handshake_timeouts_total 199938
telemt_upstream_connect_attempt_total 37705
telemt_upstream_connect_success_total 37558
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 37668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 1496
telemt_me_reconnect_success_total 783
telemt_me_reader_eof_total 761
telemt_me_idle_close_by_peer_total 761
telemt_me_route_drop_no_conn_total 2096291
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5308220
telemt_me_endpoint_quarantine_total 676
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 755
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_me_writers_active_current 47
telemt_desync_total 20509
telemt_desync_full_logged_total 6841
telemt_desync_suppressed_total 13668
telemt_desync_frames_bucket_total{bucket="1_2"} 5008
telemt_desync_frames_bucket_total{bucket="3_10"} 7433
telemt_desync_frames_bucket_total{bucket="gt_10"} 8068
telemt_pool_swap_total 109
telemt_pool_force_close_total 2968
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 33920
telemt_me_writer_removed_unexpected_total 736
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2746
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31925
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2880
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30952
telemt_me_writer_teardown_success_total{mode="normal"} 34671
telemt_me_writer_teardown_noop_total 33922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68593
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.561935
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68593
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 698
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5283427
telemt_user_connections_current{user="hello"} 1736
telemt_user_octets_from_client{user="hello"} 107352534004 (99.98 GB)
telemt_user_octets_to_client{user="hello"} 2482532948536 (2.26 TB)
telemt_user_unique_ips_current{user="hello"} 775
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 98493.2 (27h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6015690
telemt_connections_bad_total 589965
telemt_connections_current 1623
telemt_connections_me_current 1623
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 167187
telemt_upstream_connect_attempt_total 53723
telemt_upstream_connect_success_total 53314
telemt_upstream_connect_fail_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 53664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20655
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 350
telemt_me_reconnect_attempts_total 5334
telemt_me_reconnect_success_total 1092
telemt_me_reader_eof_total 970
telemt_me_idle_close_by_peer_total 970
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2149605
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4677633
telemt_me_endpoint_quarantine_total 782
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 750
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 19270
telemt_desync_full_logged_total 6466
telemt_desync_suppressed_total 12804
telemt_desync_frames_bucket_total{bucket="1_2"} 4850
telemt_desync_frames_bucket_total{bucket="3_10"} 7010
telemt_desync_frames_bucket_total{bucket="gt_10"} 7410
telemt_pool_swap_total 107
telemt_pool_force_close_total 2933
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 32713
telemt_me_writer_removed_unexpected_total 983
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3231
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30509
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2710
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29780
telemt_me_writer_teardown_success_total{mode="normal"} 33740
telemt_me_writer_teardown_noop_total 32717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66457
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.893184
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66457
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 245
telemt_me_writer_restored_same_endpoint_total 847
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 4680904
telemt_user_connections_current{user="hello"} 1623
telemt_user_octets_from_client{user="hello"} 88654228705 (82.57 GB)
telemt_user_octets_to_client{user="hello"} 2008795018080 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 744
telemt_user_unique_ips_recent_window{user="hello"} 156
```