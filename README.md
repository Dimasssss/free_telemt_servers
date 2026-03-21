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

# Server Metrics 2026-03-21 16:08:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 70385.7 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2513340
telemt_connections_bad_total 149967
telemt_connections_current 1458
telemt_connections_me_current 1458
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 79246
telemt_upstream_connect_attempt_total 29836
telemt_upstream_connect_success_total 29705
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 29793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17297
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1735
telemt_me_reconnect_success_total 679
telemt_me_reader_eof_total 652
telemt_me_idle_close_by_peer_total 652
telemt_me_route_drop_no_conn_total 2137563
telemt_me_route_drop_channel_closed_total 667
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2001640
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 490
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 546
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
telemt_me_writers_active_current 42
telemt_desync_total 7967
telemt_desync_full_logged_total 2750
telemt_desync_suppressed_total 5217
telemt_desync_frames_bucket_total{bucket="1_2"} 1745
telemt_desync_frames_bucket_total{bucket="3_10"} 3024
telemt_desync_frames_bucket_total{bucket="gt_10"} 3198
telemt_pool_swap_total 76
telemt_pool_force_close_total 2273
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 515
telemt_me_draining_writers_reap_progress_total 23936
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2058
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22292
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2152
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21663
telemt_me_writer_teardown_success_total{mode="normal"} 24350
telemt_me_writer_teardown_noop_total 23942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48292
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 225.932559
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48292
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 515
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 580
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2002992
telemt_user_connections_current{user="hello"} 1458
telemt_user_octets_from_client{user="hello"} 28231822817 (26.29 GB)
telemt_user_octets_to_client{user="hello"} 496856903898 (462.73 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 526
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1511.2 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53808
telemt_connections_bad_total 2727
telemt_connections_current 1272
telemt_connections_me_current 1272
telemt_handshake_timeouts_total 1339
telemt_upstream_connect_attempt_total 645
telemt_upstream_connect_success_total 643
telemt_upstream_connect_attempts_per_request{bucket="1"} 643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 3
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 28090
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45427
telemt_me_endpoint_quarantine_total 14
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_desync_total 178
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 516
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 495
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 489
telemt_me_writer_teardown_success_total{mode="normal"} 519
telemt_me_writer_teardown_noop_total 516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1035
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.040061
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1035
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 45001
telemt_user_connections_current{user="hello"} 1272
telemt_user_octets_from_client{user="hello"} 350191120 (333.97 MB)
telemt_user_octets_to_client{user="hello"} 11654261736 (10.85 GB)
telemt_user_unique_ips_current{user="hello"} 890
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 70383.6 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5137083
telemt_connections_bad_total 446775
telemt_connections_current 4815
telemt_connections_me_current 4815
telemt_handshake_timeouts_total 176266
telemt_upstream_connect_attempt_total 25992
telemt_upstream_connect_success_total 25935
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 25941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1168
telemt_me_reconnect_success_total 591
telemt_me_reader_eof_total 595
telemt_me_idle_close_by_peer_total 595
telemt_me_route_drop_no_conn_total 3104091
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4217396
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 529
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
telemt_me_writers_active_current 44
telemt_desync_total 17311
telemt_desync_full_logged_total 5815
telemt_desync_suppressed_total 11496
telemt_desync_frames_bucket_total{bucket="1_2"} 3654
telemt_desync_frames_bucket_total{bucket="3_10"} 6887
telemt_desync_frames_bucket_total{bucket="gt_10"} 6770
telemt_pool_swap_total 75
telemt_pool_force_close_total 2433
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 384
telemt_me_draining_writers_reap_progress_total 23579
telemt_me_writer_removed_unexpected_total 575
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2064
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21824
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2232
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 201
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21146
telemt_me_writer_teardown_success_total{mode="normal"} 23888
telemt_me_writer_teardown_noop_total 23613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47501
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 91.959286
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47501
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 384
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 532
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4212380
telemt_user_connections_current{user="hello"} 4815
telemt_user_octets_from_client{user="hello"} 66864919872 (62.27 GB)
telemt_user_octets_to_client{user="hello"} 1355874710692 (1.23 TB)
telemt_user_unique_ips_current{user="hello"} 1895
telemt_user_unique_ips_recent_window{user="hello"} 606
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 70384.9 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4124339
telemt_connections_bad_total 432570
telemt_connections_current 3850
telemt_connections_me_current 3850
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 144319
telemt_upstream_connect_attempt_total 30363
telemt_upstream_connect_success_total 30075
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 30216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14137
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 495
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1397
telemt_me_reconnect_success_total 616
telemt_me_reader_eof_total 580
telemt_me_idle_close_by_peer_total 580
telemt_me_route_drop_no_conn_total 1317866
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3038926
telemt_me_endpoint_quarantine_total 448
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 535
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
telemt_me_writers_active_current 43
telemt_desync_total 14479
telemt_desync_full_logged_total 4779
telemt_desync_suppressed_total 9700
telemt_desync_frames_bucket_total{bucket="1_2"} 3621
telemt_desync_frames_bucket_total{bucket="3_10"} 5589
telemt_desync_frames_bucket_total{bucket="gt_10"} 5269
telemt_pool_swap_total 77
telemt_pool_force_close_total 2220
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 228
telemt_me_draining_writers_reap_progress_total 22706
telemt_me_writer_removed_unexpected_total 561
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1966
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21293
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 159
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20486
telemt_me_writer_teardown_success_total{mode="normal"} 23259
telemt_me_writer_teardown_noop_total 22708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45967
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 24.135043
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45967
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 228
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 520
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 3038424
telemt_user_connections_current{user="hello"} 3850
telemt_user_octets_from_client{user="hello"} 67821094081 (63.16 GB)
telemt_user_octets_to_client{user="hello"} 1402225516267 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1526
telemt_user_unique_ips_recent_window{user="hello"} 548
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 70349.1 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4065043
telemt_connections_bad_total 414173
telemt_connections_current 3851
telemt_connections_me_current 3851
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 123089
telemt_upstream_connect_attempt_total 35622
telemt_upstream_connect_success_total 35382
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 35515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 865
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1458
telemt_me_reconnect_success_total 665
telemt_me_reader_eof_total 607
telemt_me_idle_close_by_peer_total 607
telemt_me_route_drop_no_conn_total 1408079
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3022938
telemt_me_endpoint_quarantine_total 500
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 526
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
telemt_me_writers_active_current 43
telemt_desync_total 13967
telemt_desync_full_logged_total 4610
telemt_desync_suppressed_total 9357
telemt_desync_frames_bucket_total{bucket="1_2"} 3501
telemt_desync_frames_bucket_total{bucket="3_10"} 5252
telemt_desync_frames_bucket_total{bucket="gt_10"} 5214
telemt_pool_swap_total 75
telemt_pool_force_close_total 2131
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 246
telemt_me_draining_writers_reap_progress_total 24130
telemt_me_writer_removed_unexpected_total 577
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2039
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22706
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1947
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21999
telemt_me_writer_teardown_success_total{mode="normal"} 24745
telemt_me_writer_teardown_noop_total 24136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48881
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.824979
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48881
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 246
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 572
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 3026563
telemt_user_connections_current{user="hello"} 3851
telemt_user_octets_from_client{user="hello"} 70995949441 (66.12 GB)
telemt_user_octets_to_client{user="hello"} 1399152085576 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1567
telemt_user_unique_ips_recent_window{user="hello"} 572
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 70387.9 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13992019
telemt_connections_bad_total 904073
telemt_connections_current 5744
telemt_connections_me_current 5744
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 416736
telemt_upstream_connect_attempt_total 116769
telemt_upstream_connect_success_total 106847
telemt_upstream_connect_fail_total 8856
telemt_upstream_connect_attempts_per_request{bucket="1"} 115703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8856
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 3900
telemt_me_reconnect_success_total 1425
telemt_me_reader_eof_total 996
telemt_me_idle_close_by_peer_total 995
telemt_me_route_drop_no_conn_total 27667538
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11532442
telemt_me_endpoint_quarantine_total 538
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 551
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
telemt_me_writers_active_current 43
telemt_desync_total 20337
telemt_desync_full_logged_total 6345
telemt_desync_suppressed_total 13992
telemt_desync_frames_bucket_total{bucket="1_2"} 4441
telemt_desync_frames_bucket_total{bucket="3_10"} 8948
telemt_desync_frames_bucket_total{bucket="gt_10"} 6948
telemt_pool_swap_total 72
telemt_pool_force_close_total 2330
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 22434
telemt_me_writer_removed_unexpected_total 1356
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2938
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20630
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1953
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 377
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20104
telemt_me_writer_teardown_success_total{mode="normal"} 23568
telemt_me_writer_teardown_noop_total 22446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45962
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46014
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 174.414424
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46014
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 998
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 11607107
telemt_user_connections_current{user="hello"} 5744
telemt_user_octets_from_client{user="hello"} 80932711825 (75.37 GB)
telemt_user_octets_to_client{user="hello"} 826625319809 (769.85 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2052
telemt_user_unique_ips_recent_window{user="hello"} 1126
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 70355.4 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4051002
telemt_connections_bad_total 439643
telemt_connections_current 3991
telemt_connections_me_current 3991
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 86467
telemt_upstream_connect_attempt_total 29490
telemt_upstream_connect_success_total 29160
telemt_upstream_connect_fail_total 282
telemt_upstream_connect_attempts_per_request{bucket="1"} 29442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 282
telemt_me_reconnect_attempts_total 3001
telemt_me_reconnect_success_total 1055
telemt_me_reader_eof_total 1050
telemt_me_idle_close_by_peer_total 1050
telemt_me_route_drop_no_conn_total 1730128
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3137837
telemt_me_endpoint_quarantine_total 434
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 523
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
telemt_me_writers_active_current 45
telemt_desync_total 15200
telemt_desync_full_logged_total 5271
telemt_desync_suppressed_total 9929
telemt_desync_frames_bucket_total{bucket="1_2"} 2983
telemt_desync_frames_bucket_total{bucket="3_10"} 6015
telemt_desync_frames_bucket_total{bucket="gt_10"} 6202
telemt_pool_swap_total 70
telemt_pool_force_close_total 2043
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 208
telemt_me_draining_writers_reap_progress_total 24738
telemt_me_writer_removed_unexpected_total 1017
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2484
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23307
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1748
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22695
telemt_me_writer_teardown_success_total{mode="normal"} 25791
telemt_me_writer_teardown_noop_total 24739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50530
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.328057
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50530
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 208
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 912
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 3121096
telemt_user_connections_current{user="hello"} 3991
telemt_user_octets_from_client{user="hello"} 81730104144 (76.12 GB)
telemt_user_octets_to_client{user="hello"} 1287277173558 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1721
telemt_user_unique_ips_recent_window{user="hello"} 655
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 7191.0 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1121155
telemt_connections_bad_total 42063
telemt_connections_current 3766
telemt_connections_me_current 3766
telemt_handshake_timeouts_total 519363
telemt_upstream_connect_attempt_total 2510
telemt_upstream_connect_success_total 2467
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 2504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 301
telemt_me_reconnect_success_total 99
telemt_me_reader_eof_total 89
telemt_me_idle_close_by_peer_total 89
telemt_me_route_drop_no_conn_total 448671
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 513818
telemt_me_endpoint_quarantine_total 27
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 53
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
telemt_desync_total 2660
telemt_desync_full_logged_total 856
telemt_desync_suppressed_total 1804
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 976
telemt_desync_frames_bucket_total{bucket="gt_10"} 1174
telemt_pool_swap_total 6
telemt_pool_force_close_total 200
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 17
telemt_me_draining_writers_reap_progress_total 2114
telemt_me_writer_removed_unexpected_total 90
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 197
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2007
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1914
telemt_me_writer_teardown_success_total{mode="normal"} 2204
telemt_me_writer_teardown_noop_total 2114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4318
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.819038
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4318
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 17
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 84
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 513095
telemt_user_connections_current{user="hello"} 3766
telemt_user_octets_from_client{user="hello"} 13050043820 (12.15 GB)
telemt_user_octets_to_client{user="hello"} 191237143376 (178.10 GB)
telemt_user_unique_ips_current{user="hello"} 1478
telemt_user_unique_ips_recent_window{user="hello"} 651
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 68341.3 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1292135
telemt_connections_bad_total 144543
telemt_connections_current 863
telemt_connections_me_current 863
telemt_handshake_timeouts_total 461196
telemt_upstream_connect_attempt_total 31724
telemt_upstream_connect_success_total 31716
telemt_upstream_connect_attempts_per_request{bucket="1"} 31716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1360
telemt_me_reconnect_success_total 568
telemt_me_reader_eof_total 567
telemt_me_idle_close_by_peer_total 567
telemt_me_route_drop_no_conn_total 284316
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 609584
telemt_me_endpoint_quarantine_total 604
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 569
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
telemt_me_writers_active_current 44
telemt_desync_total 3668
telemt_desync_full_logged_total 1322
telemt_desync_suppressed_total 2346
telemt_desync_frames_bucket_total{bucket="1_2"} 684
telemt_desync_frames_bucket_total{bucket="3_10"} 1320
telemt_desync_frames_bucket_total{bucket="gt_10"} 1664
telemt_pool_swap_total 74
telemt_pool_force_close_total 1739
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 28426
telemt_me_writer_removed_unexpected_total 536
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2151
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26828
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1710
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26687
telemt_me_writer_teardown_success_total{mode="normal"} 28979
telemt_me_writer_teardown_noop_total 28426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57405
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.577789
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57405
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 473
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 609181
telemt_user_connections_current{user="hello"} 863
telemt_user_octets_from_client{user="hello"} 12652729071 (11.78 GB)
telemt_user_octets_to_client{user="hello"} 235851655421 (219.65 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 314
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 70359.9 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4515718
telemt_connections_bad_total 417911
telemt_connections_current 4788
telemt_connections_me_current 4788
telemt_handshake_timeouts_total 149180
telemt_upstream_connect_attempt_total 27835
telemt_upstream_connect_success_total 27721
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 27800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13970
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_reconnect_attempts_total 1195
telemt_me_reconnect_success_total 624
telemt_me_reader_eof_total 591
telemt_me_idle_close_by_peer_total 591
telemt_me_route_drop_no_conn_total 1372284
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3571927
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 537
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 13986
telemt_desync_full_logged_total 4616
telemt_desync_suppressed_total 9370
telemt_desync_frames_bucket_total{bucket="1_2"} 3309
telemt_desync_frames_bucket_total{bucket="3_10"} 5214
telemt_desync_frames_bucket_total{bucket="gt_10"} 5463
telemt_pool_swap_total 78
telemt_pool_force_close_total 2032
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 232
telemt_me_draining_writers_reap_progress_total 24936
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1996
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23521
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1984
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22904
telemt_me_writer_teardown_success_total{mode="normal"} 25517
telemt_me_writer_teardown_noop_total 24936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50453
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.107110
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50453
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 232
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 553
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3563359
telemt_user_connections_current{user="hello"} 4788
telemt_user_octets_from_client{user="hello"} 71651498840 (66.73 GB)
telemt_user_octets_to_client{user="hello"} 1671522010284 (1.52 TB)
telemt_user_unique_ips_current{user="hello"} 1797
telemt_user_unique_ips_recent_window{user="hello"} 612
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 70356.5 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4002040
telemt_connections_bad_total 363744
telemt_connections_current 3788
telemt_connections_me_current 3788
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 122623
telemt_upstream_connect_attempt_total 44314
telemt_upstream_connect_success_total 44002
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 44259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15819
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_reconnect_attempts_total 4037
telemt_me_reconnect_success_total 893
telemt_me_reader_eof_total 772
telemt_me_idle_close_by_peer_total 772
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1450681
telemt_me_route_drop_channel_closed_total 113
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3188440
telemt_me_endpoint_quarantine_total 588
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 533
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
telemt_me_writers_active_current 43
telemt_desync_total 12419
telemt_desync_full_logged_total 4216
telemt_desync_suppressed_total 8203
telemt_desync_frames_bucket_total{bucket="1_2"} 3099
telemt_desync_frames_bucket_total{bucket="3_10"} 4619
telemt_desync_frames_bucket_total{bucket="gt_10"} 4701
telemt_pool_swap_total 76
telemt_pool_force_close_total 1976
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 219
telemt_me_draining_writers_reap_progress_total 24307
telemt_me_writer_removed_unexpected_total 785
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2399
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22726
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1805
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 171
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22331
telemt_me_writer_teardown_success_total{mode="normal"} 25125
telemt_me_writer_teardown_noop_total 24308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49433
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.290343
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49433
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 219
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 685
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 3196604
telemt_user_connections_current{user="hello"} 3788
telemt_user_octets_from_client{user="hello"} 57990971837 (54.01 GB)
telemt_user_octets_to_client{user="hello"} 1361589952708 (1.24 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1518
telemt_user_unique_ips_recent_window{user="hello"} 583
```