# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
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

## rdp-onedash.ru
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

## 4vps.su
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

# Server Metrics 2026-03-20 06:19:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 46918.0 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 931141
telemt_connections_bad_total 58310
telemt_connections_current 1496
telemt_connections_me_current 1496
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 24364
telemt_upstream_connect_attempt_total 9130
telemt_upstream_connect_success_total 9025
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 9130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5604
telemt_me_reconnect_success_total 5560
telemt_me_reader_eof_total 5887
telemt_me_idle_close_by_peer_total 5886
telemt_me_route_drop_no_conn_total 261609
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 753636
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4001
telemt_desync_full_logged_total 1441
telemt_desync_suppressed_total 2560
telemt_desync_frames_bucket_total{bucket="1_2"} 779
telemt_desync_frames_bucket_total{bucket="3_10"} 1559
telemt_desync_frames_bucket_total{bucket="gt_10"} 1663
telemt_pool_swap_total 51
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 5619
telemt_me_writer_restored_same_endpoint_total 5547
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 755166
telemt_user_connections_current{user="hello"} 1496
telemt_user_octets_from_client{user="hello"} 33734221572 (31.42 GB)
telemt_user_octets_to_client{user="hello"} 262100325089 (244.10 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 524
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 63374.0 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4091413
telemt_connections_bad_total 374635
telemt_connections_current 4944
telemt_connections_me_current 4944
telemt_handshake_timeouts_total 96646
telemt_upstream_connect_attempt_total 11921
telemt_upstream_connect_success_total 11700
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 11921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 48
telemt_me_reconnect_attempts_total 11575
telemt_me_reconnect_success_total 7320
telemt_me_reader_eof_total 7824
telemt_me_idle_close_by_peer_total 7823
telemt_me_route_drop_no_conn_total 1838290
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3344216
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13448
telemt_desync_full_logged_total 4481
telemt_desync_suppressed_total 8967
telemt_desync_frames_bucket_total{bucket="1_2"} 2618
telemt_desync_frames_bucket_total{bucket="3_10"} 5232
telemt_desync_frames_bucket_total{bucket="gt_10"} 5598
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 63
telemt_me_writer_removed_unexpected_total 7545
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7265
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 3343841
telemt_user_connections_current{user="hello"} 4944
telemt_user_octets_from_client{user="hello"} 49559959610 (46.16 GB)
telemt_user_octets_to_client{user="hello"} 1261753349274 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1680
telemt_user_unique_ips_recent_window{user="hello"} 632
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 63357.0 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3643429
telemt_connections_bad_total 508060
telemt_connections_current 3904
telemt_connections_me_current 3904
telemt_handshake_timeouts_total 55595
telemt_upstream_connect_attempt_total 10211
telemt_upstream_connect_success_total 10141
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 10211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7935
telemt_me_reconnect_success_total 6990
telemt_me_reader_eof_total 7370
telemt_me_idle_close_by_peer_total 7369
telemt_me_route_drop_no_conn_total 2134736
telemt_me_route_drop_channel_closed_total 209
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2571881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9394
telemt_desync_full_logged_total 2946
telemt_desync_suppressed_total 6448
telemt_desync_frames_bucket_total{bucket="1_2"} 2354
telemt_desync_frames_bucket_total{bucket="3_10"} 3582
telemt_desync_frames_bucket_total{bucket="gt_10"} 3458
telemt_pool_swap_total 64
telemt_me_writer_close_signal_drop_total 84
telemt_me_writer_removed_unexpected_total 7069
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6989
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 2566930
telemt_user_connections_current{user="hello"} 3904
telemt_user_octets_from_client{user="hello"} 38793725476 (36.13 GB)
telemt_user_octets_to_client{user="hello"} 1049848434140 (977.75 GB)
telemt_user_unique_ips_current{user="hello"} 1275
telemt_user_unique_ips_recent_window{user="hello"} 672
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 63339.8 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3632613
telemt_connections_bad_total 259458
telemt_connections_current 4127
telemt_connections_me_current 4127
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 53636
telemt_upstream_connect_attempt_total 67609
telemt_upstream_connect_success_total 62886
telemt_upstream_connect_fail_total 4723
telemt_upstream_connect_attempts_per_request{bucket="1"} 67609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9668
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4723
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10306
telemt_me_reconnect_success_total 7328
telemt_me_reader_eof_total 7649
telemt_me_idle_close_by_peer_total 7648
telemt_me_route_drop_no_conn_total 3085758
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2978346
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10819
telemt_desync_full_logged_total 3325
telemt_desync_suppressed_total 7494
telemt_desync_frames_bucket_total{bucket="1_2"} 2538
telemt_desync_frames_bucket_total{bucket="3_10"} 4088
telemt_desync_frames_bucket_total{bucket="gt_10"} 4193
telemt_pool_swap_total 51
telemt_me_writer_close_signal_drop_total 675
telemt_me_writer_removed_unexpected_total 8048
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7324
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 720
telemt_user_connections_total{user="hello"} 3029034
telemt_user_connections_current{user="hello"} 4127
telemt_user_octets_from_client{user="hello"} 43072567332 (40.11 GB)
telemt_user_octets_to_client{user="hello"} 812936684155 (757.11 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1259
telemt_user_unique_ips_recent_window{user="hello"} 675
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 922.7 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128070
telemt_connections_bad_total 20144
telemt_connections_current 4376
telemt_connections_me_current 4376
telemt_handshake_timeouts_total 2258
telemt_upstream_connect_attempt_total 156
telemt_upstream_connect_success_total 155
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 85
telemt_me_reconnect_success_total 84
telemt_me_reader_eof_total 46
telemt_me_idle_close_by_peer_total 46
telemt_me_route_drop_no_conn_total 85391
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97063
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 268
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 68
telemt_me_writer_restored_same_endpoint_total 54
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 96921
telemt_user_connections_current{user="hello"} 4376
telemt_user_octets_from_client{user="hello"} 963472500 (918.84 MB)
telemt_user_octets_to_client{user="hello"} 24161029468 (22.50 GB)
telemt_user_unique_ips_current{user="hello"} 1396
telemt_user_unique_ips_recent_window{user="hello"} 590
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 857.7 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12375
telemt_connections_bad_total 114
telemt_connections_current 477
telemt_connections_me_current 477
telemt_handshake_timeouts_total 208
telemt_upstream_connect_attempt_total 89
telemt_upstream_connect_success_total 88
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 89
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 22
telemt_me_route_drop_no_conn_total 5678
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13356
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_user_connections_total{user="hello"} 11206
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 69424132 (66.21 MB)
telemt_user_octets_to_client{user="hello"} 3055450708 (2.85 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 63304.1 (17h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2667266
telemt_connections_bad_total 167502
telemt_connections_current 3714
telemt_connections_me_current 3714
telemt_handshake_timeouts_total 47455
telemt_upstream_connect_attempt_total 11270
telemt_upstream_connect_success_total 11200
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 11269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 8097
telemt_me_reconnect_success_total 8045
telemt_me_reader_eof_total 8506
telemt_me_idle_close_by_peer_total 8506
telemt_me_route_drop_no_conn_total 918578
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2233677
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11118
telemt_desync_full_logged_total 3655
telemt_desync_suppressed_total 7463
telemt_desync_frames_bucket_total{bucket="1_2"} 2180
telemt_desync_frames_bucket_total{bucket="3_10"} 3924
telemt_desync_frames_bucket_total{bucket="gt_10"} 5014
telemt_pool_swap_total 65
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 8157
telemt_me_writer_restored_same_endpoint_total 8028
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 2232510
telemt_user_connections_current{user="hello"} 3714
telemt_user_octets_from_client{user="hello"} 49047898028 (45.68 GB)
telemt_user_octets_to_client{user="hello"} 1175747463556 (1.07 TB)
telemt_user_unique_ips_current{user="hello"} 1241
telemt_user_unique_ips_recent_window{user="hello"} 487
```