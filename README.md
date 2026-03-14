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

# Server Metrics 2026-03-14 11:12:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 185921.1 (51h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 729501
telemt_connections_bad_total 34239
telemt_handshake_timeouts_total 14226
telemt_upstream_connect_attempt_total 47330
telemt_upstream_connect_success_total 47095
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 47330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6107
telemt_me_reconnect_attempts_total 43214
telemt_me_reconnect_success_total 37452
telemt_me_reader_eof_total 40049
telemt_me_idle_close_by_peer_total 40048
telemt_me_route_drop_no_conn_total 241199
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 625303
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2557
telemt_desync_full_logged_total 849
telemt_desync_suppressed_total 1708
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 952
telemt_desync_frames_bucket_total{bucket="gt_10"} 1067
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 38031
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37432
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 625193
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 17580098778 (16.37 GB)
telemt_user_octets_to_client{user="hello"} 301235062908 (280.55 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 185814.8 (51h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363236
telemt_connections_bad_total 2836
telemt_handshake_timeouts_total 3293
telemt_upstream_connect_attempt_total 155213
telemt_upstream_connect_success_total 153844
telemt_upstream_connect_fail_total 1369
telemt_upstream_connect_attempts_per_request{bucket="1"} 155213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2470
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1369
telemt_me_keepalive_timeout_total 5528
telemt_me_reconnect_attempts_total 191894
telemt_me_reconnect_success_total 41269
telemt_me_reader_eof_total 47051
telemt_me_idle_close_by_peer_total 47051
telemt_me_route_drop_no_conn_total 125180
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239763
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 46
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
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 46369
telemt_me_refill_failed_total 4699
telemt_me_writer_restored_same_endpoint_total 41251
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5100
telemt_user_connections_total{user="hello"} 342866
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 3505667855 (3.26 GB)
telemt_user_octets_to_client{user="hello"} 109788030263 (102.25 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 185778.3 (51h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419433
telemt_connections_bad_total 3283
telemt_handshake_timeouts_total 35911
telemt_upstream_connect_attempt_total 49505
telemt_upstream_connect_success_total 49496
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 49505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26731
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3928
telemt_me_reconnect_attempts_total 41492
telemt_me_reconnect_success_total 40180
telemt_me_reader_eof_total 43154
telemt_me_idle_close_by_peer_total 43154
telemt_me_route_drop_no_conn_total 152576
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365321
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 138
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 40660
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40159
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 480
telemt_user_connections_total{user="hello"} 365044
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 14594514012 (13.59 GB)
telemt_user_octets_to_client{user="hello"} 160691824764 (149.66 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 185753.8 (51h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 531394
telemt_connections_bad_total 16724
telemt_handshake_timeouts_total 5274
telemt_upstream_connect_attempt_total 79904
telemt_upstream_connect_success_total 69211
telemt_upstream_connect_fail_total 10693
telemt_upstream_connect_attempts_per_request{bucket="1"} 79904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28537
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10693
telemt_me_keepalive_timeout_total 5709
telemt_me_reconnect_attempts_total 155548
telemt_me_reconnect_success_total 40910
telemt_me_reader_eof_total 45792
telemt_me_idle_close_by_peer_total 45784
telemt_me_route_drop_no_conn_total 192652
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 455389
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2037
telemt_desync_full_logged_total 607
telemt_desync_suppressed_total 1430
telemt_desync_frames_bucket_total{bucket="1_2"} 483
telemt_desync_frames_bucket_total{bucket="3_10"} 778
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 44958
telemt_me_refill_failed_total 3574
telemt_me_writer_restored_same_endpoint_total 40900
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4048
telemt_user_connections_total{user="hello"} 474255
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 10095475119 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 194500685920 (181.14 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 135925.4 (37h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228823
telemt_connections_bad_total 35948
telemt_handshake_timeouts_total 2047
telemt_upstream_connect_attempt_total 47733
telemt_upstream_connect_success_total 47260
telemt_upstream_connect_fail_total 473
telemt_upstream_connect_attempts_per_request{bucket="1"} 47733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 473
telemt_me_keepalive_timeout_total 2901
telemt_me_reconnect_attempts_total 51505
telemt_me_reconnect_success_total 35621
telemt_me_reader_eof_total 38111
telemt_me_idle_close_by_peer_total 38111
telemt_me_route_drop_no_conn_total 69294
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179784
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 770
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 580
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 366
telemt_desync_frames_bucket_total{bucket="gt_10"} 277
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 36449
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35603
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 828
telemt_user_connections_total{user="hello"} 184540
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 2715959989 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 85260062823 (79.40 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 185710.2 (51h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1079928
telemt_connections_bad_total 37368
telemt_handshake_timeouts_total 27015
telemt_upstream_connect_attempt_total 38838
telemt_upstream_connect_success_total 38634
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 38838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 4937
telemt_me_reconnect_attempts_total 34128
telemt_me_reconnect_success_total 29437
telemt_me_reader_eof_total 31565
telemt_me_idle_close_by_peer_total 31562
telemt_me_route_drop_no_conn_total 506137
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1001406
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 29954
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29430
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 973991
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 18286769616 (17.03 GB)
telemt_user_octets_to_client{user="hello"} 489381022584 (455.77 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 61
```