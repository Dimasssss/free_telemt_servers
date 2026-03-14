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

# Server Metrics 2026-03-14 05:10:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 164240.5 (45h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635175
telemt_connections_bad_total 32287
telemt_handshake_timeouts_total 12972
telemt_upstream_connect_attempt_total 41966
telemt_upstream_connect_success_total 41751
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 41966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5562
telemt_me_reconnect_attempts_total 37863
telemt_me_reconnect_success_total 33177
telemt_me_reader_eof_total 35468
telemt_me_idle_close_by_peer_total 35467
telemt_me_route_drop_no_conn_total 206674
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 537786
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1893
telemt_desync_full_logged_total 638
telemt_desync_suppressed_total 1255
telemt_desync_frames_bucket_total{bucket="1_2"} 408
telemt_desync_frames_bucket_total{bucket="3_10"} 696
telemt_desync_frames_bucket_total{bucket="gt_10"} 789
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 33684
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33157
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 507
telemt_user_connections_total{user="hello"} 537670
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 15862852458 (14.77 GB)
telemt_user_octets_to_client{user="hello"} 260278496456 (242.40 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 164133.9 (45h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320857
telemt_connections_bad_total 2280
telemt_handshake_timeouts_total 2332
telemt_upstream_connect_attempt_total 147848
telemt_upstream_connect_success_total 146643
telemt_upstream_connect_fail_total 1205
telemt_upstream_connect_attempts_per_request{bucket="1"} 147848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1205
telemt_me_keepalive_timeout_total 3890
telemt_me_reconnect_attempts_total 171957
telemt_me_reconnect_success_total 35146
telemt_me_reader_eof_total 40361
telemt_me_idle_close_by_peer_total 40361
telemt_me_route_drop_no_conn_total 102155
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200803
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
telemt_me_writer_removed_unexpected_total 39751
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 35129
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4605
telemt_user_connections_total{user="hello"} 303912
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 3156169979 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 98535588839 (91.77 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 164097.6 (45h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372998
telemt_connections_bad_total 2956
telemt_handshake_timeouts_total 34895
telemt_upstream_connect_attempt_total 43483
telemt_upstream_connect_success_total 43474
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3403
telemt_me_reconnect_attempts_total 36528
telemt_me_reconnect_success_total 35246
telemt_me_reader_eof_total 37897
telemt_me_idle_close_by_peer_total 37897
telemt_me_route_drop_no_conn_total 133879
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322194
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
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 35675
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35225
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 321971
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 12718483760 (11.85 GB)
telemt_user_octets_to_client{user="hello"} 128558938952 (119.73 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 164073.1 (45h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474750
telemt_connections_bad_total 15600
telemt_handshake_timeouts_total 4413
telemt_upstream_connect_attempt_total 73439
telemt_upstream_connect_success_total 62904
telemt_upstream_connect_fail_total 10535
telemt_upstream_connect_attempts_per_request{bucket="1"} 73439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10535
telemt_me_keepalive_timeout_total 5295
telemt_me_reconnect_attempts_total 141736
telemt_me_reconnect_success_total 35685
telemt_me_reader_eof_total 40126
telemt_me_idle_close_by_peer_total 40118
telemt_me_route_drop_no_conn_total 170391
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403223
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1716
telemt_desync_full_logged_total 505
telemt_desync_suppressed_total 1211
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 39408
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 35675
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3723
telemt_user_connections_total{user="hello"} 422064
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 9219378735 (8.59 GB)
telemt_user_octets_to_client{user="hello"} 165649157740 (154.27 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 114244.6 (31h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186951
telemt_connections_bad_total 27061
telemt_handshake_timeouts_total 1658
telemt_upstream_connect_attempt_total 40968
telemt_upstream_connect_success_total 40589
telemt_upstream_connect_fail_total 379
telemt_upstream_connect_attempts_per_request{bucket="1"} 40968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 379
telemt_me_keepalive_timeout_total 2410
telemt_me_reconnect_attempts_total 43450
telemt_me_reconnect_success_total 30025
telemt_me_reader_eof_total 32132
telemt_me_idle_close_by_peer_total 32132
telemt_me_route_drop_no_conn_total 55408
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148208
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 30714
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30007
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 689
telemt_user_connections_total{user="hello"} 152961
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 2264836941 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 69663820843 (64.88 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 164029.2 (45h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 933764
telemt_connections_bad_total 32053
telemt_handshake_timeouts_total 25794
telemt_upstream_connect_attempt_total 34110
telemt_upstream_connect_success_total 33926
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 34110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 4592
telemt_me_reconnect_attempts_total 30470
telemt_me_reconnect_success_total 25798
telemt_me_reader_eof_total 27694
telemt_me_idle_close_by_peer_total 27691
telemt_me_route_drop_no_conn_total 442174
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 868445
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
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 26272
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25791
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 474
telemt_user_connections_total{user="hello"} 841105
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 14641830812 (13.64 GB)
telemt_user_octets_to_client{user="hello"} 427024614236 (397.70 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 62
```