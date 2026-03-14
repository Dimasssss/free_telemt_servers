# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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

# Server Metrics 2026-03-14 05:51:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 166682.4 (46h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 642098
telemt_connections_bad_total 32303
telemt_handshake_timeouts_total 12991
telemt_upstream_connect_attempt_total 42528
telemt_upstream_connect_success_total 42312
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 42528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5575
telemt_me_reconnect_attempts_total 38293
telemt_me_reconnect_success_total 33605
telemt_me_reader_eof_total 35936
telemt_me_idle_close_by_peer_total 35935
telemt_me_route_drop_no_conn_total 209874
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 544415
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1939
telemt_desync_full_logged_total 663
telemt_desync_suppressed_total 1276
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 708
telemt_desync_frames_bucket_total{bucket="gt_10"} 811
telemt_pool_swap_total 154
telemt_me_writer_removed_unexpected_total 34116
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33585
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 511
telemt_user_connections_total{user="hello"} 544300
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 15976094690 (14.88 GB)
telemt_user_octets_to_client{user="hello"} 264081325432 (245.94 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 166575.2 (46h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324066
telemt_connections_bad_total 2288
telemt_handshake_timeouts_total 2350
telemt_upstream_connect_attempt_total 148880
telemt_upstream_connect_success_total 147657
telemt_upstream_connect_fail_total 1223
telemt_upstream_connect_attempts_per_request{bucket="1"} 148880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2420
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1223
telemt_me_keepalive_timeout_total 3906
telemt_me_reconnect_attempts_total 172868
telemt_me_reconnect_success_total 36056
telemt_me_reader_eof_total 41278
telemt_me_idle_close_by_peer_total 41278
telemt_me_route_drop_no_conn_total 104586
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203892
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 40668
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 36039
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4612
telemt_user_connections_total{user="hello"} 306999
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 3183972815 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 99944165059 (93.08 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 166539.8 (46h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377016
telemt_connections_bad_total 2964
telemt_handshake_timeouts_total 34925
telemt_upstream_connect_attempt_total 44073
telemt_upstream_connect_success_total 44064
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3417
telemt_me_reconnect_attempts_total 37017
telemt_me_reconnect_success_total 35733
telemt_me_reader_eof_total 38418
telemt_me_idle_close_by_peer_total 38418
telemt_me_route_drop_no_conn_total 135666
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326067
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 36166
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35712
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 325844
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 13342042528 (12.43 GB)
telemt_user_octets_to_client{user="hello"} 129673080076 (120.77 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 166514.3 (46h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478506
telemt_connections_bad_total 15653
telemt_handshake_timeouts_total 4478
telemt_upstream_connect_attempt_total 74094
telemt_upstream_connect_success_total 63547
telemt_upstream_connect_fail_total 10547
telemt_upstream_connect_attempts_per_request{bucket="1"} 74094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10547
telemt_me_keepalive_timeout_total 5316
telemt_me_reconnect_attempts_total 142293
telemt_me_reconnect_success_total 36238
telemt_me_reader_eof_total 40705
telemt_me_idle_close_by_peer_total 40697
telemt_me_route_drop_no_conn_total 172057
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 406690
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1728
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 1217
telemt_desync_frames_bucket_total{bucket="1_2"} 408
telemt_desync_frames_bucket_total{bucket="3_10"} 654
telemt_desync_frames_bucket_total{bucket="gt_10"} 666
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 39965
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 36228
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3727
telemt_user_connections_total{user="hello"} 425531
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 9246067335 (8.61 GB)
telemt_user_octets_to_client{user="hello"} 168101180388 (156.56 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 116686.0 (32h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191142
telemt_connections_bad_total 28327
telemt_handshake_timeouts_total 1660
telemt_upstream_connect_attempt_total 41601
telemt_upstream_connect_success_total 41212
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 41601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_keepalive_timeout_total 2417
telemt_me_reconnect_attempts_total 43944
telemt_me_reconnect_success_total 30519
telemt_me_reader_eof_total 32675
telemt_me_idle_close_by_peer_total 32675
telemt_me_route_drop_no_conn_total 56520
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151058
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 623
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 31215
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30501
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 696
telemt_user_connections_total{user="hello"} 155807
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 2320736873 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 70707003923 (65.85 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 166470.4 (46h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 949810
telemt_connections_bad_total 35165
telemt_handshake_timeouts_total 25875
telemt_upstream_connect_attempt_total 34547
telemt_upstream_connect_success_total 34362
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 34547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 4612
telemt_me_reconnect_attempts_total 30819
telemt_me_reconnect_success_total 26143
telemt_me_reader_eof_total 28060
telemt_me_idle_close_by_peer_total 28057
telemt_me_route_drop_no_conn_total 448146
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 880861
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 26622
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26136
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 479
telemt_user_connections_total{user="hello"} 853521
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 14807133048 (13.79 GB)
telemt_user_octets_to_client{user="hello"} 435903997892 (405.97 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 53
```