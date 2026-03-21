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

# Server Metrics 2026-03-21 20:18:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 85350.9 (23h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3054628
telemt_connections_bad_total 178262
telemt_connections_current 981
telemt_connections_me_current 981
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 93947
telemt_upstream_connect_attempt_total 34869
telemt_upstream_connect_success_total 34725
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 34826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20633
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1887
telemt_me_reconnect_success_total 760
telemt_me_reader_eof_total 728
telemt_me_idle_close_by_peer_total 728
telemt_me_route_drop_no_conn_total 2617222
telemt_me_route_drop_channel_closed_total 843
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2471347
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 576
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 665
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
telemt_me_writers_active_current 46
telemt_desync_total 9872
telemt_desync_full_logged_total 3444
telemt_desync_suppressed_total 6428
telemt_desync_frames_bucket_total{bucket="1_2"} 2152
telemt_desync_frames_bucket_total{bucket="3_10"} 3720
telemt_desync_frames_bucket_total{bucket="gt_10"} 4000
telemt_pool_swap_total 92
telemt_pool_force_close_total 2788
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 640
telemt_me_draining_writers_reap_progress_total 28550
telemt_me_writer_removed_unexpected_total 710
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2399
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26601
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2649
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25762
telemt_me_writer_teardown_success_total{mode="normal"} 29000
telemt_me_writer_teardown_noop_total 28558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57558
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 297.949061
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57558
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 640
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 653
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 2470996
telemt_user_connections_current{user="hello"} 981
telemt_user_octets_from_client{user="hello"} 36561128493 (34.05 GB)
telemt_user_octets_to_client{user="hello"} 627419050870 (584.33 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 10488.9 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 427501
telemt_connections_bad_total 18973
telemt_connections_current 1568
telemt_connections_me_current 1568
telemt_handshake_timeouts_total 14876
telemt_upstream_connect_attempt_total 4191
telemt_upstream_connect_success_total 4103
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 4179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 220
telemt_me_reconnect_success_total 136
telemt_me_reader_eof_total 112
telemt_me_idle_close_by_peer_total 112
telemt_me_route_drop_no_conn_total 262827
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349789
telemt_me_endpoint_quarantine_total 79
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 84
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
telemt_desync_total 1491
telemt_desync_full_logged_total 842
telemt_desync_suppressed_total 649
telemt_desync_frames_bucket_total{bucket="1_2"} 301
telemt_desync_frames_bucket_total{bucket="3_10"} 561
telemt_desync_frames_bucket_total{bucket="gt_10"} 629
telemt_pool_swap_total 11
telemt_pool_force_close_total 335
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 3619
telemt_me_writer_removed_unexpected_total 106
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3405
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 328
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3284
telemt_me_writer_teardown_success_total{mode="normal"} 3718
telemt_me_writer_teardown_noop_total 3619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7337
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.037834
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7337
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 94
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 349393
telemt_user_connections_current{user="hello"} 1568
telemt_user_octets_from_client{user="hello"} 5549941260 (5.17 GB)
telemt_user_octets_to_client{user="hello"} 100604581432 (93.70 GB)
telemt_user_unique_ips_current{user="hello"} 850
telemt_user_unique_ips_recent_window{user="hello"} 411
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 85348.6 (23h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6791697
telemt_connections_bad_total 524140
telemt_connections_current 3938
telemt_connections_me_current 3938
telemt_handshake_timeouts_total 212863
telemt_upstream_connect_attempt_total 30654
telemt_upstream_connect_success_total 30592
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 30598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16685
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1282
telemt_me_reconnect_success_total 659
telemt_me_reader_eof_total 669
telemt_me_idle_close_by_peer_total 669
telemt_me_route_drop_no_conn_total 4325420
telemt_me_route_drop_channel_closed_total 63
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5568009
telemt_me_endpoint_quarantine_total 527
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 633
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
telemt_me_writers_active_current 44
telemt_desync_total 22799
telemt_desync_full_logged_total 7595
telemt_desync_suppressed_total 15204
telemt_desync_frames_bucket_total{bucket="1_2"} 4780
telemt_desync_frames_bucket_total{bucket="3_10"} 9077
telemt_desync_frames_bucket_total{bucket="gt_10"} 8942
telemt_pool_swap_total 91
telemt_pool_force_close_total 3043
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 495
telemt_me_draining_writers_reap_progress_total 27895
telemt_me_writer_removed_unexpected_total 643
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2399
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25790
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2813
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24852
telemt_me_writer_teardown_success_total{mode="normal"} 28189
telemt_me_writer_teardown_noop_total 27932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56121
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 135.169365
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56121
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 495
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 593
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 5561331
telemt_user_connections_current{user="hello"} 3938
telemt_user_octets_from_client{user="hello"} 92860703312 (86.48 GB)
telemt_user_octets_to_client{user="hello"} 1740143523772 (1.58 TB)
telemt_user_unique_ips_current{user="hello"} 1615
telemt_user_unique_ips_recent_window{user="hello"} 538
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 85350.0 (23h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5487290
telemt_connections_bad_total 526304
telemt_connections_current 3286
telemt_connections_me_current 3286
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 181376
telemt_upstream_connect_attempt_total 34789
telemt_upstream_connect_success_total 34473
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 34635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16449
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 541
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1649
telemt_me_reconnect_success_total 692
telemt_me_reader_eof_total 664
telemt_me_idle_close_by_peer_total 664
telemt_me_route_drop_no_conn_total 1900643
telemt_me_route_drop_channel_closed_total 219
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4110375
telemt_me_endpoint_quarantine_total 522
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 649
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
telemt_desync_total 19449
telemt_desync_full_logged_total 6436
telemt_desync_suppressed_total 13013
telemt_desync_frames_bucket_total{bucket="1_2"} 4740
telemt_desync_frames_bucket_total{bucket="3_10"} 7532
telemt_desync_frames_bucket_total{bucket="gt_10"} 7177
telemt_pool_swap_total 93
telemt_pool_force_close_total 2820
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 318
telemt_me_draining_writers_reap_progress_total 26713
telemt_me_writer_removed_unexpected_total 644
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2326
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24959
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2628
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23893
telemt_me_writer_teardown_success_total{mode="normal"} 27285
telemt_me_writer_teardown_noop_total 26718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54003
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.003246
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54003
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 318
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 4105762
telemt_user_connections_current{user="hello"} 3286
telemt_user_octets_from_client{user="hello"} 124029611177 (115.51 GB)
telemt_user_octets_to_client{user="hello"} 1871775733783 (1.70 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1341
telemt_user_unique_ips_recent_window{user="hello"} 400
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 85313.9 (23h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5418934
telemt_connections_bad_total 492654
telemt_connections_current 3304
telemt_connections_me_current 3304
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 164318
telemt_upstream_connect_attempt_total 41176
telemt_upstream_connect_success_total 40911
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 41045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17895
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1036
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1710
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 690
telemt_me_idle_close_by_peer_total 690
telemt_me_route_drop_no_conn_total 1956898
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4093752
telemt_me_endpoint_quarantine_total 574
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 635
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
telemt_desync_total 19206
telemt_desync_full_logged_total 6277
telemt_desync_suppressed_total 12929
telemt_desync_frames_bucket_total{bucket="1_2"} 4772
telemt_desync_frames_bucket_total{bucket="3_10"} 7279
telemt_desync_frames_bucket_total{bucket="gt_10"} 7155
telemt_pool_swap_total 91
telemt_pool_force_close_total 2682
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 332
telemt_me_draining_writers_reap_progress_total 28128
telemt_me_writer_removed_unexpected_total 660
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2400
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26409
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2472
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25446
telemt_me_writer_teardown_success_total{mode="normal"} 28809
telemt_me_writer_teardown_noop_total 28138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56947
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.103101
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56947
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 332
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 642
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4096029
telemt_user_connections_current{user="hello"} 3304
telemt_user_octets_from_client{user="hello"} 119824920939 (111.60 GB)
telemt_user_octets_to_client{user="hello"} 1869183602707 (1.70 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1307
telemt_user_unique_ips_recent_window{user="hello"} 412
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 85353.3 (23h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18827572
telemt_connections_bad_total 1205619
telemt_connections_current 4373
telemt_connections_me_current 4373
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 526700
telemt_upstream_connect_attempt_total 174243
telemt_upstream_connect_success_total 157372
telemt_upstream_connect_fail_total 15497
telemt_upstream_connect_attempts_per_request{bucket="1"} 172869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8822
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15497
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 4643
telemt_me_reconnect_success_total 1730
telemt_me_reader_eof_total 1187
telemt_me_idle_close_by_peer_total 1186
telemt_me_route_drop_no_conn_total 38522491
telemt_me_route_drop_channel_closed_total 111
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15499921
telemt_me_endpoint_quarantine_total 621
telemt_me_single_endpoint_outage_enter_total 98
telemt_me_single_endpoint_outage_exit_total 98
telemt_me_single_endpoint_outage_reconnect_attempt_total 216
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 216
telemt_me_single_endpoint_shadow_rotate_total 659
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 28852
telemt_desync_full_logged_total 8506
telemt_desync_suppressed_total 20346
telemt_desync_frames_bucket_total{bucket="1_2"} 6260
telemt_desync_frames_bucket_total{bucket="3_10"} 12798
telemt_desync_frames_bucket_total{bucket="gt_10"} 9794
telemt_pool_swap_total 87
telemt_pool_force_close_total 2906
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 655
telemt_me_draining_writers_reap_progress_total 26269
telemt_me_writer_removed_unexpected_total 1639
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3500
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24150
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2458
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 448
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23363
telemt_me_writer_teardown_success_total{mode="normal"} 27650
telemt_me_writer_teardown_noop_total 26286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53936
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 200.408238
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53936
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 655
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 1199
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 15618819
telemt_user_connections_current{user="hello"} 4373
telemt_user_octets_from_client{user="hello"} 145276266947 (135.30 GB)
telemt_user_octets_to_client{user="hello"} 954615002999 (889.05 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1652
telemt_user_unique_ips_recent_window{user="hello"} 784
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 85320.9 (23h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5332383
telemt_connections_bad_total 515946
telemt_connections_current 3286
telemt_connections_me_current 3286
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 110102
telemt_upstream_connect_attempt_total 44223
telemt_upstream_connect_success_total 43759
telemt_upstream_connect_fail_total 382
telemt_upstream_connect_attempts_per_request{bucket="1"} 44141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 382
telemt_me_reconnect_attempts_total 3495
telemt_me_reconnect_success_total 1212
telemt_me_reader_eof_total 1189
telemt_me_idle_close_by_peer_total 1189
telemt_me_route_drop_no_conn_total 2238953
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4135600
telemt_me_endpoint_quarantine_total 512
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 633
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
telemt_desync_total 20442
telemt_desync_full_logged_total 7102
telemt_desync_suppressed_total 13340
telemt_desync_frames_bucket_total{bucket="1_2"} 3930
telemt_desync_frames_bucket_total{bucket="3_10"} 7991
telemt_desync_frames_bucket_total{bucket="gt_10"} 8521
telemt_pool_swap_total 86
telemt_pool_force_close_total 2532
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 312
telemt_me_draining_writers_reap_progress_total 28905
telemt_me_writer_removed_unexpected_total 1151
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2930
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27139
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2185
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26373
telemt_me_writer_teardown_success_total{mode="normal"} 30069
telemt_me_writer_teardown_noop_total 28906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58975
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.896794
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58975
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 312
telemt_me_refill_failed_total 123
telemt_me_writer_restored_same_endpoint_total 1030
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 4125977
telemt_user_connections_current{user="hello"} 3286
telemt_user_octets_from_client{user="hello"} 109823255501 (102.28 GB)
telemt_user_octets_to_client{user="hello"} 1668353257083 (1.52 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1368
telemt_user_unique_ips_recent_window{user="hello"} 386
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 22156.6 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2982545
telemt_connections_bad_total 111567
telemt_connections_current 3002
telemt_connections_me_current 3002
telemt_handshake_timeouts_total 1281644
telemt_upstream_connect_attempt_total 7119
telemt_upstream_connect_success_total 7018
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 7113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3884
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_reconnect_attempts_total 705
telemt_me_reconnect_success_total 205
telemt_me_reader_eof_total 193
telemt_me_idle_close_by_peer_total 193
telemt_me_route_drop_no_conn_total 885338
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1414037
telemt_me_endpoint_quarantine_total 108
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 165
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
telemt_desync_total 7814
telemt_desync_full_logged_total 2571
telemt_desync_suppressed_total 5243
telemt_desync_frames_bucket_total{bucket="1_2"} 1396
telemt_desync_frames_bucket_total{bucket="3_10"} 2931
telemt_desync_frames_bucket_total{bucket="gt_10"} 3487
telemt_pool_swap_total 23
telemt_pool_force_close_total 738
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 70
telemt_me_draining_writers_reap_progress_total 6192
telemt_me_writer_removed_unexpected_total 189
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 577
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5810
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 649
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 89
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5454
telemt_me_writer_teardown_success_total{mode="normal"} 6387
telemt_me_writer_teardown_noop_total 6192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12579
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.959003
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12579
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 70
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 170
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 1410317
telemt_user_connections_current{user="hello"} 3002
telemt_user_octets_from_client{user="hello"} 43116568624 (40.16 GB)
telemt_user_octets_to_client{user="hello"} 578452983388 (538.73 GB)
telemt_user_unique_ips_current{user="hello"} 1245
telemt_user_unique_ips_recent_window{user="hello"} 375
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 3127.8 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33687
telemt_connections_bad_total 122
telemt_connections_current 686
telemt_connections_me_current 686
telemt_handshake_timeouts_total 679
telemt_upstream_connect_attempt_total 1362
telemt_upstream_connect_success_total 1358
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 15
telemt_me_reader_eof_total 15
telemt_me_idle_close_by_peer_total 15
telemt_me_route_drop_no_conn_total 9622
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31416
telemt_me_endpoint_quarantine_total 17
telemt_me_single_endpoint_shadow_rotate_total 30
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
telemt_desync_total 194
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 134
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 3
telemt_pool_force_close_total 87
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 1162
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 75
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1102
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1075
telemt_me_writer_teardown_success_total{mode="normal"} 1177
telemt_me_writer_teardown_noop_total 1162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2339
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.192426
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2339
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 31364
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 905519140 (863.57 MB)
telemt_user_octets_to_client{user="hello"} 25604439848 (23.85 GB)
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 85325.2 (23h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6325755
telemt_connections_bad_total 651240
telemt_connections_current 4075
telemt_connections_me_current 4075
telemt_handshake_timeouts_total 184156
telemt_upstream_connect_attempt_total 32442
telemt_upstream_connect_success_total 32312
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 32405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16297
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_reconnect_attempts_total 1359
telemt_me_reconnect_success_total 697
telemt_me_reader_eof_total 670
telemt_me_idle_close_by_peer_total 670
telemt_me_route_drop_no_conn_total 1959526
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 21
telemt_me_route_drop_queue_full_profile_total{profile="high"} 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4852435
telemt_me_endpoint_quarantine_total 567
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 648
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
telemt_me_writers_active_current 44
telemt_desync_total 18280
telemt_desync_full_logged_total 6062
telemt_desync_suppressed_total 12218
telemt_desync_frames_bucket_total{bucket="1_2"} 4463
telemt_desync_frames_bucket_total{bucket="3_10"} 6683
telemt_desync_frames_bucket_total{bucket="gt_10"} 7134
telemt_pool_swap_total 94
telemt_pool_force_close_total 2560
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 321
telemt_me_draining_writers_reap_progress_total 29121
telemt_me_writer_removed_unexpected_total 654
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2362
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27419
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2485
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 75
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26561
telemt_me_writer_teardown_success_total{mode="normal"} 29781
telemt_me_writer_teardown_noop_total 29123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58904
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.494934
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58904
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 321
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 4828558
telemt_user_connections_current{user="hello"} 4075
telemt_user_octets_from_client{user="hello"} 96234385512 (89.63 GB)
telemt_user_octets_to_client{user="hello"} 2239837444800 (2.04 TB)
telemt_user_unique_ips_current{user="hello"} 1465
telemt_user_unique_ips_recent_window{user="hello"} 433
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 85321.8 (23h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5349020
telemt_connections_bad_total 500993
telemt_connections_current 3251
telemt_connections_me_current 3251
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 153758
telemt_upstream_connect_attempt_total 48812
telemt_upstream_connect_success_total 48453
telemt_upstream_connect_fail_total 300
telemt_upstream_connect_attempts_per_request{bucket="1"} 48753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 300
telemt_me_reconnect_attempts_total 4473
telemt_me_reconnect_success_total 982
telemt_me_reader_eof_total 871
telemt_me_idle_close_by_peer_total 871
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 2011166
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4222732
telemt_me_endpoint_quarantine_total 678
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 648
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
telemt_me_writers_active_current 44
telemt_desync_total 17049
telemt_desync_full_logged_total 5758
telemt_desync_suppressed_total 11291
telemt_desync_frames_bucket_total{bucket="1_2"} 4214
telemt_desync_frames_bucket_total{bucket="3_10"} 6265
telemt_desync_frames_bucket_total{bucket="gt_10"} 6570
telemt_pool_swap_total 92
telemt_pool_force_close_total 2490
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 320
telemt_me_draining_writers_reap_progress_total 28331
telemt_me_writer_removed_unexpected_total 882
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2839
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26413
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2298
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25841
telemt_me_writer_teardown_success_total{mode="normal"} 29252
telemt_me_writer_teardown_noop_total 28333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57585
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.359141
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57585
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 320
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 758
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 4227535
telemt_user_connections_current{user="hello"} 3251
telemt_user_octets_from_client{user="hello"} 80538515501 (75.01 GB)
telemt_user_octets_to_client{user="hello"} 1766296209724 (1.61 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1300
telemt_user_unique_ips_recent_window{user="hello"} 395
```