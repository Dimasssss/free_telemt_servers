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

# Server Metrics 2026-03-22 22:12:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 90390.1 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3296179
telemt_connections_bad_total 247672
telemt_connections_current 854
telemt_connections_me_current 854
telemt_handshake_timeouts_total 104711
telemt_upstream_connect_attempt_total 33228
telemt_upstream_connect_success_total 33227
telemt_upstream_connect_attempts_per_request{bucket="1"} 33227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1319
telemt_me_reconnect_success_total 548
telemt_me_reader_eof_total 563
telemt_me_idle_close_by_peer_total 563
telemt_me_route_drop_no_conn_total 2958310
telemt_me_route_drop_channel_closed_total 1226
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2770927
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 705
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
telemt_desync_total 11887
telemt_desync_full_logged_total 3727
telemt_desync_suppressed_total 8160
telemt_desync_frames_bucket_total{bucket="1_2"} 3221
telemt_desync_frames_bucket_total{bucket="3_10"} 4344
telemt_desync_frames_bucket_total{bucket="gt_10"} 4322
telemt_pool_swap_total 100
telemt_pool_force_close_total 3120
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 628
telemt_me_draining_writers_reap_progress_total 30414
telemt_me_writer_removed_unexpected_total 544
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2200
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28425
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3065
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27294
telemt_me_writer_teardown_success_total{mode="normal"} 30625
telemt_me_writer_teardown_noop_total 30425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61050
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.479228
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61050
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 628
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 488
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2760313
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 39628387876 (36.91 GB)
telemt_user_octets_to_client{user="hello"} 745495370748 (694.30 GB)
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 103754.3 (28h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3934783
telemt_connections_bad_total 354633
telemt_connections_current 886
telemt_connections_me_current 886
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99618
telemt_upstream_connect_attempt_total 62571
telemt_upstream_connect_success_total 61806
telemt_upstream_connect_fail_total 679
telemt_upstream_connect_attempts_per_request{bucket="1"} 62485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 679
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9021
telemt_me_reconnect_success_total 3140
telemt_me_reader_eof_total 3148
telemt_me_idle_close_by_peer_total 3148
telemt_me_route_drop_no_conn_total 3632110
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3131986
telemt_me_endpoint_quarantine_total 771
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 800
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
telemt_me_writers_active_current 126
telemt_desync_total 12745
telemt_desync_full_logged_total 7138
telemt_desync_suppressed_total 5607
telemt_desync_frames_bucket_total{bucket="1_2"} 2877
telemt_desync_frames_bucket_total{bucket="3_10"} 5001
telemt_desync_frames_bucket_total{bucket="gt_10"} 4867
telemt_pool_swap_total 95
telemt_pool_force_close_total 2879
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 41650
telemt_me_writer_removed_unexpected_total 3087
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5436
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39325
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38771
telemt_me_writer_teardown_success_total{mode="normal"} 44761
telemt_me_writer_teardown_noop_total 41651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86412
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.419748
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86412
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 223
telemt_me_writer_restored_same_endpoint_total 2814
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 3142648
telemt_user_connections_current{user="hello"} 886
telemt_user_octets_from_client{user="hello"} 42211742635 (39.31 GB)
telemt_user_octets_to_client{user="hello"} 774224346294 (721.05 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 505
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 178614.5 (49h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16168863
telemt_connections_bad_total 1592252
telemt_connections_current 955
telemt_connections_me_current 955
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 395906
telemt_upstream_connect_attempt_total 79282
telemt_upstream_connect_success_total 79182
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 79199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1700
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2882
telemt_me_reconnect_success_total 1495
telemt_me_reader_eof_total 1441
telemt_me_idle_close_by_peer_total 1439
telemt_me_route_drop_no_conn_total 14024967
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12869634
telemt_me_endpoint_quarantine_total 1154
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1337
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 53191
telemt_desync_full_logged_total 16845
telemt_desync_suppressed_total 36346
telemt_desync_frames_bucket_total{bucket="1_2"} 11818
telemt_desync_frames_bucket_total{bucket="3_10"} 20717
telemt_desync_frames_bucket_total{bucket="gt_10"} 20656
telemt_pool_swap_total 193
telemt_pool_force_close_total 6464
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1043
telemt_me_draining_writers_reap_progress_total 59154
telemt_me_writer_removed_unexpected_total 1390
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5154
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54660
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5994
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52690
telemt_me_writer_teardown_success_total{mode="normal"} 59814
telemt_me_writer_teardown_noop_total 59207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119021
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 316.839586
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119021
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1043
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 1292
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 12869894
telemt_user_connections_current{user="hello"} 955
telemt_user_octets_from_client{user="hello"} 189739556689 (176.71 GB)
telemt_user_octets_to_client{user="hello"} 3455313457687 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 178615.6 (49h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11732373
telemt_connections_bad_total 1200461
telemt_connections_current 771
telemt_connections_me_current 771
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343679
telemt_upstream_connect_attempt_total 93748
telemt_upstream_connect_success_total 92439
telemt_upstream_connect_fail_total 862
telemt_upstream_connect_attempts_per_request{bucket="1"} 93301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38217
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 862
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4316
telemt_me_reconnect_success_total 1807
telemt_me_reader_eof_total 1668
telemt_me_idle_close_by_peer_total 1668
telemt_me_route_drop_no_conn_total 4539589
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8728919
telemt_me_endpoint_quarantine_total 1149
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1358
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 38566
telemt_desync_full_logged_total 12971
telemt_desync_suppressed_total 25595
telemt_desync_frames_bucket_total{bucket="1_2"} 9528
telemt_desync_frames_bucket_total{bucket="3_10"} 14826
telemt_desync_frames_bucket_total{bucket="gt_10"} 14212
telemt_pool_swap_total 190
telemt_pool_force_close_total 5833
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 57487
telemt_me_writer_removed_unexpected_total 1703
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5288
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53753
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5321
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51654
telemt_me_writer_teardown_success_total{mode="normal"} 59041
telemt_me_writer_teardown_noop_total 57512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 114178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 115369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 116128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 116543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 116545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 116551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 116553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 116553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 116553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116553
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.244792
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116553
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1539
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8666765
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 216974158928 (202.07 GB)
telemt_user_octets_to_client{user="hello"} 3926754770527 (3.57 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 178584.3 (49h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10949409
telemt_connections_bad_total 952578
telemt_connections_current 602
telemt_connections_me_current 602
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344862
telemt_upstream_connect_attempt_total 77801
telemt_upstream_connect_success_total 76303
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 76507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2321
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5532
telemt_me_reconnect_success_total 2283
telemt_me_reader_eof_total 2019
telemt_me_idle_close_by_peer_total 2018
telemt_me_route_drop_no_conn_total 5321500
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8286658
telemt_me_endpoint_quarantine_total 1232
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1313
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_me_writers_active_current 44
telemt_desync_total 37860
telemt_desync_full_logged_total 12548
telemt_desync_suppressed_total 25312
telemt_desync_frames_bucket_total{bucket="1_2"} 9565
telemt_desync_frames_bucket_total{bucket="3_10"} 14480
telemt_desync_frames_bucket_total{bucket="gt_10"} 13815
telemt_pool_swap_total 186
telemt_pool_force_close_total 5755
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 728
telemt_me_draining_writers_reap_progress_total 57791
telemt_me_writer_removed_unexpected_total 2174
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53902
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52036
telemt_me_writer_teardown_success_total{mode="normal"} 59892
telemt_me_writer_teardown_noop_total 57862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117754
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.510547
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117754
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 728
telemt_me_refill_failed_total 172
telemt_me_writer_restored_same_endpoint_total 1977
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 8278650
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 191995907085 (178.81 GB)
telemt_user_octets_to_client{user="hello"} 3443219375249 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 48859.1 (13h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11059032
telemt_connections_bad_total 666966
telemt_connections_current 1215
telemt_connections_me_current 1215
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 250781
telemt_upstream_connect_attempt_total 51312
telemt_upstream_connect_success_total 48748
telemt_upstream_connect_fail_total 1740
telemt_upstream_connect_attempts_per_request{bucket="1"} 50488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5987
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1740
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7056
telemt_me_reconnect_success_total 1045
telemt_me_reader_eof_total 658
telemt_me_idle_close_by_peer_total 657
telemt_me_route_drop_no_conn_total 25259223
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9185554
telemt_me_endpoint_quarantine_total 339
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 387
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
telemt_desync_total 15754
telemt_desync_full_logged_total 4181
telemt_desync_suppressed_total 11573
telemt_desync_frames_bucket_total{bucket="1_2"} 3009
telemt_desync_frames_bucket_total{bucket="3_10"} 6366
telemt_desync_frames_bucket_total{bucket="gt_10"} 6379
telemt_pool_swap_total 50
telemt_pool_force_close_total 1749
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 456
telemt_me_draining_writers_reap_progress_total 14403
telemt_me_writer_removed_unexpected_total 934
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2070
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13218
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1442
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12654
telemt_me_writer_teardown_success_total{mode="normal"} 15288
telemt_me_writer_teardown_noop_total 14422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29710
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.614525
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29710
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 456
telemt_me_refill_failed_total 327
telemt_me_writer_restored_same_endpoint_total 685
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 9210237
telemt_user_connections_current{user="hello"} 1215
telemt_user_octets_from_client{user="hello"} 85702922660 (79.82 GB)
telemt_user_octets_to_client{user="hello"} 562549422494 (523.91 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 178585.8 (49h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10868930
telemt_connections_bad_total 918852
telemt_connections_current 991
telemt_connections_me_current 991
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 239038
telemt_upstream_connect_attempt_total 106616
telemt_upstream_connect_success_total 105505
telemt_upstream_connect_fail_total 942
telemt_upstream_connect_attempts_per_request{bucket="1"} 106447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 942
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72640
telemt_me_reconnect_success_total 2952
telemt_me_reader_eof_total 2649
telemt_me_idle_close_by_peer_total 2647
telemt_me_route_drop_no_conn_total 5240371
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8588415
telemt_me_endpoint_quarantine_total 1177
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1341
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 45813
telemt_desync_full_logged_total 15670
telemt_desync_suppressed_total 30143
telemt_desync_frames_bucket_total{bucket="1_2"} 9293
telemt_desync_frames_bucket_total{bucket="3_10"} 17530
telemt_desync_frames_bucket_total{bucket="gt_10"} 18990
telemt_pool_swap_total 182
telemt_pool_force_close_total 5437
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 61763
telemt_me_writer_removed_unexpected_total 2682
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6508
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57968
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4688
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56326
telemt_me_writer_teardown_success_total{mode="normal"} 64476
telemt_me_writer_teardown_noop_total 61764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 125504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126240
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.174512
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126240
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 4292
telemt_me_writer_restored_same_endpoint_total 2495
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 8591493
telemt_user_connections_current{user="hello"} 991
telemt_user_octets_from_client{user="hello"} 193727110249 (180.42 GB)
telemt_user_octets_to_client{user="hello"} 3280049419588 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 403
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 115422.0 (32h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11529051
telemt_connections_bad_total 459905
telemt_connections_current 628
telemt_connections_me_current 628
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4728867
telemt_upstream_connect_attempt_total 54655
telemt_upstream_connect_success_total 54249
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 54644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_reconnect_attempts_total 48681
telemt_me_reconnect_success_total 1720
telemt_me_reader_eof_total 1384
telemt_me_idle_close_by_peer_total 1383
telemt_me_route_drop_no_conn_total 4071121
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5548140
telemt_me_endpoint_quarantine_total 751
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 876
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31180
telemt_desync_full_logged_total 10625
telemt_desync_suppressed_total 20555
telemt_desync_frames_bucket_total{bucket="1_2"} 6189
telemt_desync_frames_bucket_total{bucket="3_10"} 12309
telemt_desync_frames_bucket_total{bucket="gt_10"} 12682
telemt_pool_swap_total 122
telemt_pool_force_close_total 3684
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 40716
telemt_me_writer_removed_unexpected_total 1438
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3503
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38691
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3243
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37032
telemt_me_writer_teardown_success_total{mode="normal"} 42194
telemt_me_writer_teardown_noop_total 40723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82917
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.630591
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82917
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1525
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5540767
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 118395907216 (110.26 GB)
telemt_user_octets_to_client{user="hello"} 2130591534630 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 96392.8 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1451052
telemt_connections_bad_total 36377
telemt_connections_current 636
telemt_connections_me_current 636
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 28869
telemt_upstream_connect_attempt_total 45113
telemt_upstream_connect_success_total 44972
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 45085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 763
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2066
telemt_me_reconnect_success_total 851
telemt_me_reader_eof_total 832
telemt_me_idle_close_by_peer_total 832
telemt_me_route_drop_no_conn_total 501746
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1287026
telemt_me_endpoint_quarantine_total 773
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 790
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
telemt_me_writers_warm_current 38
telemt_desync_total 8078
telemt_desync_full_logged_total 2447
telemt_desync_suppressed_total 5631
telemt_desync_frames_bucket_total{bucket="1_2"} 1989
telemt_desync_frames_bucket_total{bucket="3_10"} 3118
telemt_desync_frames_bucket_total{bucket="gt_10"} 2971
telemt_pool_swap_total 103
telemt_pool_force_close_total 2685
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 149
telemt_me_draining_writers_reap_progress_total 37739
telemt_me_writer_removed_unexpected_total 801
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2963
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35611
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2597
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35054
telemt_me_writer_teardown_success_total{mode="normal"} 38574
telemt_me_writer_teardown_noop_total 37743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76317
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.961572
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76317
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 149
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 721
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1282959
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 25227001037 (23.49 GB)
telemt_user_octets_to_client{user="hello"} 545277247831 (507.83 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 241
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 178590.6 (49h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13200841
telemt_connections_bad_total 1566144
telemt_connections_current 1056
telemt_connections_me_current 1056
telemt_handshake_timeouts_total 379135
telemt_upstream_connect_attempt_total 68268
telemt_upstream_connect_success_total 67930
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 68132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2669
telemt_me_reconnect_success_total 1392
telemt_me_reader_eof_total 1361
telemt_me_idle_close_by_peer_total 1361
telemt_me_route_drop_no_conn_total 4468719
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9977526
telemt_me_endpoint_quarantine_total 1222
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1341
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 41686
telemt_desync_full_logged_total 13602
telemt_desync_suppressed_total 28084
telemt_desync_frames_bucket_total{bucket="1_2"} 10014
telemt_desync_frames_bucket_total{bucket="3_10"} 15342
telemt_desync_frames_bucket_total{bucket="gt_10"} 16330
telemt_pool_swap_total 198
telemt_pool_force_close_total 5402
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 661
telemt_me_draining_writers_reap_progress_total 61579
telemt_me_writer_removed_unexpected_total 1309
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4981
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57949
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5228
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56177
telemt_me_writer_teardown_success_total{mode="normal"} 62930
telemt_me_writer_teardown_noop_total 61581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124511
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.585518
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124511
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 661
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 1218
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 9944325
telemt_user_connections_current{user="hello"} 1056
telemt_user_octets_from_client{user="hello"} 194045782968 (180.72 GB)
telemt_user_octets_to_client{user="hello"} 4405359658336 (4.01 TB)
telemt_user_unique_ips_current{user="hello"} 375
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 178587.1 (49h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11489801
telemt_connections_bad_total 1308884
telemt_connections_current 734
telemt_connections_me_current 734
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 304087
telemt_upstream_connect_attempt_total 94787
telemt_upstream_connect_success_total 93939
telemt_upstream_connect_fail_total 641
telemt_upstream_connect_attempts_per_request{bucket="1"} 94580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39730
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2066
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 641
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10095
telemt_me_reconnect_success_total 2446
telemt_me_reader_eof_total 2283
telemt_me_idle_close_by_peer_total 2282
telemt_me_seq_mismatch_total 85
telemt_me_route_drop_no_conn_total 5628240
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8877706
telemt_me_endpoint_quarantine_total 1384
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1344
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 44
telemt_desync_total 41287
telemt_desync_full_logged_total 13248
telemt_desync_suppressed_total 28039
telemt_desync_frames_bucket_total{bucket="1_2"} 10603
telemt_desync_frames_bucket_total{bucket="3_10"} 15197
telemt_desync_frames_bucket_total{bucket="gt_10"} 15487
telemt_pool_swap_total 188
telemt_pool_force_close_total 5197
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 650
telemt_me_draining_writers_reap_progress_total 61372
telemt_me_writer_removed_unexpected_total 2317
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6323
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57446
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4726
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56175
telemt_me_writer_teardown_success_total{mode="normal"} 63769
telemt_me_writer_teardown_noop_total 61377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125146
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.313900
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125146
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 650
telemt_me_refill_failed_total 395
telemt_me_writer_restored_same_endpoint_total 1984
telemt_me_writer_restored_fallback_total 117
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 8883124
telemt_user_connections_current{user="hello"} 734
telemt_user_octets_from_client{user="hello"} 156720213801 (145.96 GB)
telemt_user_octets_to_client{user="hello"} 3457677399231 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 80
```