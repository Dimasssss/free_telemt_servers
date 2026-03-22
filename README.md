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

# Server Metrics 2026-03-22 19:54:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 82097.4 (22h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3048106
telemt_connections_bad_total 207714
telemt_connections_current 1103
telemt_connections_me_current 1103
telemt_handshake_timeouts_total 98217
telemt_upstream_connect_attempt_total 30147
telemt_upstream_connect_success_total 30146
telemt_upstream_connect_attempts_per_request{bucket="1"} 30146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19603
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 76
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1194
telemt_me_reconnect_success_total 508
telemt_me_reader_eof_total 513
telemt_me_idle_close_by_peer_total 513
telemt_me_route_drop_no_conn_total 2711105
telemt_me_route_drop_channel_closed_total 1079
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2579538
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 636
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
telemt_me_writers_active_current 43
telemt_desync_total 11065
telemt_desync_full_logged_total 3512
telemt_desync_suppressed_total 7553
telemt_desync_frames_bucket_total{bucket="1_2"} 2957
telemt_desync_frames_bucket_total{bucket="3_10"} 4108
telemt_desync_frames_bucket_total{bucket="gt_10"} 4000
telemt_pool_swap_total 91
telemt_pool_force_close_total 2818
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 583
telemt_me_draining_writers_reap_progress_total 27565
telemt_me_writer_removed_unexpected_total 497
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2014
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25779
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24747
telemt_me_writer_teardown_success_total{mode="normal"} 27793
telemt_me_writer_teardown_noop_total 27575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55368
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 306.598500
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55368
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 583
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 450
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 2571370
telemt_user_connections_current{user="hello"} 1103
telemt_user_octets_from_client{user="hello"} 37703660676 (35.11 GB)
telemt_user_octets_to_client{user="hello"} 676184852324 (629.75 GB)
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 410
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 95463.7 (26h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3830618
telemt_connections_bad_total 340084
telemt_connections_current 1365
telemt_connections_me_current 1365
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 97598
telemt_upstream_connect_attempt_total 58031
telemt_upstream_connect_success_total 57317
telemt_upstream_connect_fail_total 631
telemt_upstream_connect_attempts_per_request{bucket="1"} 57948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 631
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6786
telemt_me_reconnect_success_total 2627
telemt_me_reader_eof_total 2575
telemt_me_idle_close_by_peer_total 2575
telemt_me_route_drop_no_conn_total 3604741
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3049841
telemt_me_endpoint_quarantine_total 729
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 735
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_me_writers_active_current 128
telemt_me_writers_warm_current 18
telemt_desync_total 12197
telemt_desync_full_logged_total 6821
telemt_desync_suppressed_total 5376
telemt_desync_frames_bucket_total{bucket="1_2"} 2790
telemt_desync_frames_bucket_total{bucket="3_10"} 4782
telemt_desync_frames_bucket_total{bucket="gt_10"} 4625
telemt_pool_swap_total 88
telemt_pool_force_close_total 2657
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 225
telemt_me_draining_writers_reap_progress_total 37937
telemt_me_writer_removed_unexpected_total 2522
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4679
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35796
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 389
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35280
telemt_me_writer_teardown_success_total{mode="normal"} 40475
telemt_me_writer_teardown_noop_total 37937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78412
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.983238
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78412
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 225
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2314
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 3060642
telemt_user_connections_current{user="hello"} 1365
telemt_user_octets_from_client{user="hello"} 39984934895 (37.24 GB)
telemt_user_octets_to_client{user="hello"} 729205698058 (679.13 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 764
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 170323.6 (47h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15936200
telemt_connections_bad_total 1544611
telemt_connections_current 1429
telemt_connections_me_current 1429
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 392582
telemt_upstream_connect_attempt_total 75774
telemt_upstream_connect_success_total 75677
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 75694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1687
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2806
telemt_me_reconnect_success_total 1444
telemt_me_reader_eof_total 1386
telemt_me_idle_close_by_peer_total 1384
telemt_me_route_drop_no_conn_total 13970757
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12696100
telemt_me_endpoint_quarantine_total 1076
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1271
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 52360
telemt_desync_full_logged_total 16484
telemt_desync_suppressed_total 35876
telemt_desync_frames_bucket_total{bucket="1_2"} 11672
telemt_desync_frames_bucket_total{bucket="3_10"} 20405
telemt_desync_frames_bucket_total{bucket="gt_10"} 20283
telemt_pool_swap_total 184
telemt_pool_force_close_total 6219
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1013
telemt_me_draining_writers_reap_progress_total 55966
telemt_me_writer_removed_unexpected_total 1338
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4915
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51666
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5751
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 468
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49747
telemt_me_writer_teardown_success_total{mode="normal"} 56581
telemt_me_writer_teardown_noop_total 56017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112598
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.687571
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112598
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1013
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1246
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 12696597
telemt_user_connections_current{user="hello"} 1429
telemt_user_octets_from_client{user="hello"} 185614129809 (172.87 GB)
telemt_user_octets_to_client{user="hello"} 3374204631043 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 602
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 170325.2 (47h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11523189
telemt_connections_bad_total 1151563
telemt_connections_current 1212
telemt_connections_me_current 1212
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 342768
telemt_upstream_connect_attempt_total 88246
telemt_upstream_connect_success_total 87015
telemt_upstream_connect_fail_total 845
telemt_upstream_connect_attempts_per_request{bucket="1"} 87860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3708
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 845
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4140
telemt_me_reconnect_success_total 1721
telemt_me_reader_eof_total 1590
telemt_me_idle_close_by_peer_total 1590
telemt_me_route_drop_no_conn_total 4489595
telemt_me_route_drop_channel_closed_total 492
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8583906
telemt_me_endpoint_quarantine_total 1076
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1291
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_active_current 45
telemt_desync_total 38031
telemt_desync_full_logged_total 12806
telemt_desync_suppressed_total 25225
telemt_desync_frames_bucket_total{bucket="1_2"} 9372
telemt_desync_frames_bucket_total{bucket="3_10"} 14646
telemt_desync_frames_bucket_total{bucket="gt_10"} 14013
telemt_pool_swap_total 181
telemt_pool_force_close_total 5608
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 702
telemt_me_draining_writers_reap_progress_total 54387
telemt_me_writer_removed_unexpected_total 1627
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5021
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50840
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5105
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 503
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48779
telemt_me_writer_teardown_success_total{mode="normal"} 55861
telemt_me_writer_teardown_noop_total 54412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110273
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.657199
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110273
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 702
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1471
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 8522071
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 214115910033 (199.41 GB)
telemt_user_octets_to_client{user="hello"} 3849657632634 (3.50 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 436
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 170290.4 (47h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10809265
telemt_connections_bad_total 934648
telemt_connections_current 1416
telemt_connections_me_current 1416
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 343771
telemt_upstream_connect_attempt_total 73398
telemt_upstream_connect_success_total 72273
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 72458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 1385
telemt_me_reconnect_attempts_total 5006
telemt_me_reconnect_success_total 2015
telemt_me_reader_eof_total 1762
telemt_me_idle_close_by_peer_total 1761
telemt_me_route_drop_no_conn_total 5259240
telemt_me_route_drop_channel_closed_total 375
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8173465
telemt_me_endpoint_quarantine_total 1158
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1248
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
telemt_me_writers_active_current 42
telemt_desync_total 37486
telemt_desync_full_logged_total 12411
telemt_desync_suppressed_total 25075
telemt_desync_frames_bucket_total{bucket="1_2"} 9477
telemt_desync_frames_bucket_total{bucket="3_10"} 14337
telemt_desync_frames_bucket_total{bucket="gt_10"} 13672
telemt_pool_swap_total 179
telemt_pool_force_close_total 5526
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 710
telemt_me_draining_writers_reap_progress_total 54472
telemt_me_writer_removed_unexpected_total 1904
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5476
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50819
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4975
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48946
telemt_me_writer_teardown_success_total{mode="normal"} 56295
telemt_me_writer_teardown_noop_total 54543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110838
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3173.797875
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110838
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 710
telemt_me_refill_failed_total 159
telemt_me_writer_restored_same_endpoint_total 1735
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8165766
telemt_user_connections_current{user="hello"} 1416
telemt_user_octets_from_client{user="hello"} 190195994045 (177.13 GB)
telemt_user_octets_to_client{user="hello"} 3397949165457 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 513
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 40569.3 (11h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10799117
telemt_connections_bad_total 657599
telemt_connections_current 2075
telemt_connections_me_current 2075
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 232492
telemt_upstream_connect_attempt_total 45066
telemt_upstream_connect_success_total 42808
telemt_upstream_connect_fail_total 1548
telemt_upstream_connect_attempts_per_request{bucket="1"} 44356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13529
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5961
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1548
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6494
telemt_me_reconnect_success_total 896
telemt_me_reader_eof_total 558
telemt_me_idle_close_by_peer_total 558
telemt_me_route_drop_no_conn_total 25190627
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8968535
telemt_me_endpoint_quarantine_total 248
telemt_me_single_endpoint_outage_enter_total 64
telemt_me_single_endpoint_outage_exit_total 64
telemt_me_single_endpoint_outage_reconnect_attempt_total 116
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 116
telemt_me_single_endpoint_shadow_rotate_total 313
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
telemt_me_writers_active_current 53
telemt_me_writers_warm_current 21
telemt_desync_total 14568
telemt_desync_full_logged_total 3843
telemt_desync_suppressed_total 10725
telemt_desync_frames_bucket_total{bucket="1_2"} 2695
telemt_desync_frames_bucket_total{bucket="3_10"} 5923
telemt_desync_frames_bucket_total{bucket="gt_10"} 5950
telemt_pool_swap_total 40
telemt_pool_force_close_total 1475
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 430
telemt_me_draining_writers_reap_progress_total 11513
telemt_me_writer_removed_unexpected_total 802
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1721
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10547
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10038
telemt_me_writer_teardown_success_total{mode="normal"} 12268
telemt_me_writer_teardown_noop_total 11532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23800
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.843388
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23800
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 430
telemt_me_refill_failed_total 310
telemt_me_writer_restored_same_endpoint_total 603
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8990695
telemt_user_connections_current{user="hello"} 2075
telemt_user_octets_from_client{user="hello"} 82145473971 (76.50 GB)
telemt_user_octets_to_client{user="hello"} 485352783203 (452.02 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 753
telemt_user_unique_ips_recent_window{user="hello"} 264
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 170295.6 (47h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10689311
telemt_connections_bad_total 901507
telemt_connections_current 1231
telemt_connections_me_current 1231
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 234959
telemt_upstream_connect_attempt_total 102771
telemt_upstream_connect_success_total 101686
telemt_upstream_connect_fail_total 926
telemt_upstream_connect_attempts_per_request{bucket="1"} 102612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38215
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1337
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 926
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72382
telemt_me_reconnect_success_total 2824
telemt_me_reader_eof_total 2514
telemt_me_idle_close_by_peer_total 2512
telemt_me_route_drop_no_conn_total 5193205
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8443518
telemt_me_endpoint_quarantine_total 1126
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1272
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 44941
telemt_desync_full_logged_total 15295
telemt_desync_suppressed_total 29646
telemt_desync_frames_bucket_total{bucket="1_2"} 9120
telemt_desync_frames_bucket_total{bucket="3_10"} 17211
telemt_desync_frames_bucket_total{bucket="gt_10"} 18610
telemt_pool_swap_total 174
telemt_pool_force_close_total 5169
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 634
telemt_me_draining_writers_reap_progress_total 58302
telemt_me_writer_removed_unexpected_total 2552
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6217
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54663
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4442
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 727
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53133
telemt_me_writer_teardown_success_total{mode="normal"} 60880
telemt_me_writer_teardown_noop_total 58303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119183
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.015749
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119183
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 634
telemt_me_refill_failed_total 4285
telemt_me_writer_restored_same_endpoint_total 2373
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 8446793
telemt_user_connections_current{user="hello"} 1231
telemt_user_octets_from_client{user="hello"} 191570350713 (178.41 GB)
telemt_user_octets_to_client{user="hello"} 3208831724264 (2.92 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 503
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 107131.8 (29h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11272413
telemt_connections_bad_total 450277
telemt_connections_current 1662
telemt_connections_me_current 1662
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4644302
telemt_upstream_connect_attempt_total 50830
telemt_upstream_connect_success_total 50452
telemt_upstream_connect_fail_total 369
telemt_upstream_connect_attempts_per_request{bucket="1"} 50821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 369
telemt_me_reconnect_attempts_total 48471
telemt_me_reconnect_success_total 1670
telemt_me_reader_eof_total 1326
telemt_me_idle_close_by_peer_total 1325
telemt_me_route_drop_no_conn_total 4032961
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5425247
telemt_me_endpoint_quarantine_total 690
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 806
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
telemt_me_writers_warm_current 4
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30454
telemt_desync_full_logged_total 10308
telemt_desync_suppressed_total 20146
telemt_desync_frames_bucket_total{bucket="1_2"} 6077
telemt_desync_frames_bucket_total{bucket="3_10"} 12039
telemt_desync_frames_bucket_total{bucket="gt_10"} 12338
telemt_pool_swap_total 112
telemt_pool_force_close_total 3429
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 349
telemt_me_draining_writers_reap_progress_total 37254
telemt_me_writer_removed_unexpected_total 1386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3307
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35367
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2989
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33825
telemt_me_writer_teardown_success_total{mode="normal"} 38674
telemt_me_writer_teardown_noop_total 37261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75935
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.467960
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75935
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 349
telemt_me_refill_failed_total 2720
telemt_me_writer_restored_same_endpoint_total 1486
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5418148
telemt_user_connections_current{user="hello"} 1662
telemt_user_octets_from_client{user="hello"} 116910282404 (108.88 GB)
telemt_user_octets_to_client{user="hello"} 2075107100214 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 660
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 88102.7 (24h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1322714
telemt_connections_bad_total 29246
telemt_connections_current 1144
telemt_connections_me_current 1144
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24889
telemt_upstream_connect_attempt_total 41799
telemt_upstream_connect_success_total 41673
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 41772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 710
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 1921
telemt_me_reconnect_success_total 807
telemt_me_reader_eof_total 784
telemt_me_idle_close_by_peer_total 784
telemt_me_route_drop_no_conn_total 462369
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1174124
telemt_me_endpoint_quarantine_total 732
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 724
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
telemt_me_writers_active_current 46
telemt_desync_total 6962
telemt_desync_full_logged_total 2157
telemt_desync_suppressed_total 4805
telemt_desync_frames_bucket_total{bucket="1_2"} 1547
telemt_desync_frames_bucket_total{bucket="3_10"} 2755
telemt_desync_frames_bucket_total{bucket="gt_10"} 2660
telemt_pool_swap_total 94
telemt_pool_force_close_total 2432
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 34787
telemt_me_writer_removed_unexpected_total 756
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2744
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32830
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32355
telemt_me_writer_teardown_success_total{mode="normal"} 35574
telemt_me_writer_teardown_noop_total 34791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70365
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.350743
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70365
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 1170247
telemt_user_connections_current{user="hello"} 1144
telemt_user_octets_from_client{user="hello"} 22628159429 (21.07 GB)
telemt_user_octets_to_client{user="hello"} 496180274263 (462.10 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 170300.1 (47h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13003481
telemt_connections_bad_total 1515936
telemt_connections_current 1306
telemt_connections_me_current 1306
telemt_handshake_timeouts_total 372796
telemt_upstream_connect_attempt_total 64266
telemt_upstream_connect_success_total 63934
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 64131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2521
telemt_me_reconnect_success_total 1314
telemt_me_reader_eof_total 1278
telemt_me_idle_close_by_peer_total 1278
telemt_me_route_drop_no_conn_total 4415350
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9842364
telemt_me_endpoint_quarantine_total 1141
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1273
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
telemt_me_writers_active_current 45
telemt_desync_total 40720
telemt_desync_full_logged_total 13273
telemt_desync_suppressed_total 27447
telemt_desync_frames_bucket_total{bucket="1_2"} 9720
telemt_desync_frames_bucket_total{bucket="3_10"} 15030
telemt_desync_frames_bucket_total{bucket="gt_10"} 15970
telemt_pool_swap_total 189
telemt_pool_force_close_total 5201
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 57915
telemt_me_writer_removed_unexpected_total 1230
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4731
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54452
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5027
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52714
telemt_me_writer_teardown_success_total{mode="normal"} 59183
telemt_me_writer_teardown_noop_total 57917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 116967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117100
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.441187
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117100
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1148
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 9810051
telemt_user_connections_current{user="hello"} 1306
telemt_user_octets_from_client{user="hello"} 191916292564 (178.74 GB)
telemt_user_octets_to_client{user="hello"} 4333935685932 (3.94 TB)
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 397
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 170296.8 (47h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11308483
telemt_connections_bad_total 1282038
telemt_connections_current 1678
telemt_connections_me_current 1678
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 297375
telemt_upstream_connect_attempt_total 90754
telemt_upstream_connect_success_total 89934
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 90548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9759
telemt_me_reconnect_success_total 2340
telemt_me_reader_eof_total 2186
telemt_me_idle_close_by_peer_total 2185
telemt_me_seq_mismatch_total 78
telemt_me_route_drop_no_conn_total 5589635
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8740692
telemt_me_endpoint_quarantine_total 1304
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 46
telemt_me_single_endpoint_outage_exit_total 46
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1275
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 39904
telemt_desync_full_logged_total 12897
telemt_desync_suppressed_total 27007
telemt_desync_frames_bucket_total{bucket="1_2"} 9957
telemt_desync_frames_bucket_total{bucket="3_10"} 14841
telemt_desync_frames_bucket_total{bucket="gt_10"} 15106
telemt_pool_swap_total 179
telemt_pool_force_close_total 4970
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 635
telemt_me_draining_writers_reap_progress_total 57704
telemt_me_writer_removed_unexpected_total 2219
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53926
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4499
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52734
telemt_me_writer_teardown_success_total{mode="normal"} 59997
telemt_me_writer_teardown_noop_total 57709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 117706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117706
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.162808
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117706
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 635
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 1909
telemt_me_writer_restored_fallback_total 108
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 8746282
telemt_user_connections_current{user="hello"} 1678
telemt_user_octets_from_client{user="hello"} 154602739785 (143.99 GB)
telemt_user_octets_to_client{user="hello"} 3379172258835 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 632
telemt_user_unique_ips_recent_window{user="hello"} 277
```