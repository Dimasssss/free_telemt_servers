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

# Server Metrics 2026-03-13 22:07:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 138876.4 (38h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 575408
telemt_connections_bad_total 17236
telemt_handshake_timeouts_total 12804
telemt_upstream_connect_attempt_total 35249
telemt_upstream_connect_success_total 35072
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 35249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5112
telemt_me_reconnect_attempts_total 32397
telemt_me_reconnect_success_total 27738
telemt_me_reader_eof_total 29625
telemt_me_idle_close_by_peer_total 29624
telemt_me_route_drop_no_conn_total 189786
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 494929
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1585
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1048
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 591
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 28196
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27722
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 494824
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 14870100086 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 243976615716 (227.22 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 138769.7 (38h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293809
telemt_connections_bad_total 2139
telemt_handshake_timeouts_total 1919
telemt_upstream_connect_attempt_total 139063
telemt_upstream_connect_success_total 138043
telemt_upstream_connect_fail_total 1020
telemt_upstream_connect_attempts_per_request{bucket="1"} 139063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1020
telemt_me_keepalive_timeout_total 3700
telemt_me_reconnect_attempts_total 146398
telemt_me_reconnect_success_total 27782
telemt_me_reader_eof_total 32234
telemt_me_idle_close_by_peer_total 32234
telemt_me_route_drop_no_conn_total 87482
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175465
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 36
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
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 31750
telemt_me_refill_failed_total 3701
telemt_me_writer_restored_same_endpoint_total 27765
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3968
telemt_user_connections_total{user="hello"} 278578
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 2948772143 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 86126808455 (80.21 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 138733.3 (38h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341254
telemt_connections_bad_total 2658
telemt_handshake_timeouts_total 27900
telemt_upstream_connect_attempt_total 36905
telemt_upstream_connect_success_total 36900
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2851
telemt_me_reconnect_attempts_total 31166
telemt_me_reconnect_success_total 29920
telemt_me_reader_eof_total 32106
telemt_me_idle_close_by_peer_total 32106
telemt_me_route_drop_no_conn_total 121302
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 298716
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
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 30260
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29900
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 340
telemt_user_connections_total{user="hello"} 298617
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 12347086604 (11.50 GB)
telemt_user_octets_to_client{user="hello"} 123932722796 (115.42 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 138708.8 (38h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 446011
telemt_connections_bad_total 15276
telemt_handshake_timeouts_total 4234
telemt_upstream_connect_attempt_total 64225
telemt_upstream_connect_success_total 53855
telemt_upstream_connect_fail_total 10370
telemt_upstream_connect_attempts_per_request{bucket="1"} 64225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19962
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 304
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10370
telemt_me_keepalive_timeout_total 4770
telemt_me_reconnect_attempts_total 130354
telemt_me_reconnect_success_total 27887
telemt_me_reader_eof_total 31869
telemt_me_idle_close_by_peer_total 31862
telemt_me_route_drop_no_conn_total 155695
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376524
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1596
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 379
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 610
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31440
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 27877
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3553
telemt_user_connections_total{user="hello"} 395366
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 8970568687 (8.35 GB)
telemt_user_octets_to_client{user="hello"} 151105556952 (140.73 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 88880.4 (24h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149994
telemt_connections_bad_total 22200
telemt_handshake_timeouts_total 1536
telemt_upstream_connect_attempt_total 33053
telemt_upstream_connect_success_total 32742
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 33053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_keepalive_timeout_total 1304
telemt_me_reconnect_attempts_total 36817
telemt_me_reconnect_success_total 23420
telemt_me_reader_eof_total 25086
telemt_me_idle_close_by_peer_total 25086
telemt_me_route_drop_no_conn_total 46028
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116670
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 611
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 24061
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 23402
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 641
telemt_user_connections_total{user="hello"} 121564
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 1409625409 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 57465148555 (53.52 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 138664.9 (38h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 837949
telemt_connections_bad_total 27132
telemt_handshake_timeouts_total 25121
telemt_upstream_connect_attempt_total 28515
telemt_upstream_connect_success_total 28365
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 28515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 3124
telemt_me_reconnect_attempts_total 26136
telemt_me_reconnect_success_total 21484
telemt_me_reader_eof_total 23040
telemt_me_idle_close_by_peer_total 23037
telemt_me_route_drop_no_conn_total 399564
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 784171
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
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 21913
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21477
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 757026
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 13122491456 (12.22 GB)
telemt_user_octets_to_client{user="hello"} 376042230632 (350.22 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 35
```