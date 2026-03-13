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

# Server Metrics 2026-03-13 21:06:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 135210.9 (37h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 567108
telemt_connections_bad_total 16075
telemt_handshake_timeouts_total 12692
telemt_upstream_connect_attempt_total 34329
telemt_upstream_connect_success_total 34156
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 34329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5081
telemt_me_reconnect_attempts_total 31653
telemt_me_reconnect_success_total 26997
telemt_me_reader_eof_total 28823
telemt_me_idle_close_by_peer_total 28822
telemt_me_route_drop_no_conn_total 187385
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 488504
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1551
telemt_desync_full_logged_total 527
telemt_desync_suppressed_total 1024
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 574
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 27446
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26981
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 449
telemt_user_connections_total{user="hello"} 488399
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 14707338450 (13.70 GB)
telemt_user_octets_to_client{user="hello"} 235788824100 (219.60 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 135103.8 (37h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287734
telemt_connections_bad_total 2135
telemt_handshake_timeouts_total 1901
telemt_upstream_connect_attempt_total 137566
telemt_upstream_connect_success_total 136572
telemt_upstream_connect_fail_total 994
telemt_upstream_connect_attempts_per_request{bucket="1"} 137566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2408
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 994
telemt_me_keepalive_timeout_total 3663
telemt_me_reconnect_attempts_total 143566
telemt_me_reconnect_success_total 26492
telemt_me_reader_eof_total 30882
telemt_me_idle_close_by_peer_total 30882
telemt_me_route_drop_no_conn_total 84105
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169834
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 30396
telemt_me_refill_failed_total 3653
telemt_me_writer_restored_same_endpoint_total 26475
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3904
telemt_user_connections_total{user="hello"} 272947
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 2829705059 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 82816501079 (77.13 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 135067.7 (37h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334376
telemt_connections_bad_total 2657
telemt_handshake_timeouts_total 25555
telemt_upstream_connect_attempt_total 35951
telemt_upstream_connect_success_total 35946
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 35951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19291
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2836
telemt_me_reconnect_attempts_total 30395
telemt_me_reconnect_success_total 29154
telemt_me_reader_eof_total 31255
telemt_me_idle_close_by_peer_total 31255
telemt_me_route_drop_no_conn_total 119613
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294416
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
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
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 29484
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29134
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 294318
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 12276845172 (11.43 GB)
telemt_user_octets_to_client{user="hello"} 122808121256 (114.37 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 135043.0 (37h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439990
telemt_connections_bad_total 15253
telemt_handshake_timeouts_total 4199
telemt_upstream_connect_attempt_total 63733
telemt_upstream_connect_success_total 53407
telemt_upstream_connect_fail_total 10326
telemt_upstream_connect_attempts_per_request{bucket="1"} 63733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 300
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10326
telemt_me_keepalive_timeout_total 4768
telemt_me_reconnect_attempts_total 124741
telemt_me_reconnect_success_total 27650
telemt_me_reader_eof_total 31461
telemt_me_idle_close_by_peer_total 31454
telemt_me_route_drop_no_conn_total 152981
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370779
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1547
telemt_desync_full_logged_total 456
telemt_desync_suppressed_total 1091
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 587
telemt_desync_frames_bucket_total{bucket="gt_10"} 595
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31032
telemt_me_refill_failed_total 3028
telemt_me_writer_restored_same_endpoint_total 27640
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3382
telemt_user_connections_total{user="hello"} 389636
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 8789474475 (8.19 GB)
telemt_user_octets_to_client{user="hello"} 143434690720 (133.58 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 85214.6 (23h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145845
telemt_connections_bad_total 20659
telemt_handshake_timeouts_total 1524
telemt_upstream_connect_attempt_total 32064
telemt_upstream_connect_success_total 31757
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 32064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 1286
telemt_me_reconnect_attempts_total 36004
telemt_me_reconnect_success_total 22610
telemt_me_reader_eof_total 24216
telemt_me_idle_close_by_peer_total 24216
telemt_me_route_drop_no_conn_total 44981
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114178
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 608
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 23242
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22592
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 119072
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 1378037429 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 54496504115 (50.75 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 134999.0 (37h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 821895
telemt_connections_bad_total 25369
telemt_handshake_timeouts_total 25053
telemt_upstream_connect_attempt_total 27782
telemt_upstream_connect_success_total 27636
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 27782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 3115
telemt_me_reconnect_attempts_total 25608
telemt_me_reconnect_success_total 20958
telemt_me_reader_eof_total 22474
telemt_me_idle_close_by_peer_total 22471
telemt_me_route_drop_no_conn_total 391774
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 770479
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 21383
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20951
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 743344
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 12978813404 (12.09 GB)
telemt_user_octets_to_client{user="hello"} 369494371380 (344.12 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 40
```