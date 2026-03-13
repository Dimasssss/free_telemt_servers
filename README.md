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

# Server Metrics 2026-03-13 20:21:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 132460.5 (36h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 559456
telemt_connections_bad_total 14929
telemt_handshake_timeouts_total 12590
telemt_upstream_connect_attempt_total 33624
telemt_upstream_connect_success_total 33452
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 33623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5051
telemt_me_reconnect_attempts_total 31081
telemt_me_reconnect_success_total 26428
telemt_me_reader_eof_total 28210
telemt_me_idle_close_by_peer_total 28209
telemt_me_route_drop_no_conn_total 184982
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482289
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1535
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1012
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 638
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 26871
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26412
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 482184
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 8907869218 (8.30 GB)
telemt_user_octets_to_client{user="hello"} 232886451440 (216.89 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 132353.1 (36h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282203
telemt_connections_bad_total 2101
telemt_handshake_timeouts_total 1881
telemt_upstream_connect_attempt_total 132461
telemt_upstream_connect_success_total 131491
telemt_upstream_connect_fail_total 969
telemt_upstream_connect_attempts_per_request{bucket="1"} 132460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 969
telemt_me_keepalive_timeout_total 3634
telemt_me_reconnect_attempts_total 139385
telemt_me_reconnect_success_total 26410
telemt_me_reader_eof_total 30674
telemt_me_idle_close_by_peer_total 30674
telemt_me_route_drop_no_conn_total 83863
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169337
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 34
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
telemt_me_writer_removed_unexpected_total 30185
telemt_me_refill_failed_total 3525
telemt_me_writer_restored_same_endpoint_total 26393
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3775
telemt_user_connections_total{user="hello"} 267620
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 2791204871 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 80231222741 (74.72 GB)
telemt_user_msgs_from_client{user="hello"} 1596558
telemt_user_msgs_to_client{user="hello"} 8659367
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 132319.9 (36h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328484
telemt_connections_bad_total 2643
telemt_handshake_timeouts_total 23771
telemt_upstream_connect_attempt_total 35010
telemt_upstream_connect_success_total 35005
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 35010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18774
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2804
telemt_me_reconnect_attempts_total 29616
telemt_me_reconnect_success_total 28378
telemt_me_reader_eof_total 30447
telemt_me_idle_close_by_peer_total 30447
telemt_me_route_drop_no_conn_total 117622
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290605
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
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 28700
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28358
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 290515
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 11843957280 (11.03 GB)
telemt_user_octets_to_client{user="hello"} 121682794752 (113.33 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 132292.4 (36h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 434445
telemt_connections_bad_total 15235
telemt_handshake_timeouts_total 4175
telemt_upstream_connect_attempt_total 63230
telemt_upstream_connect_success_total 52923
telemt_upstream_connect_fail_total 10307
telemt_upstream_connect_attempts_per_request{bucket="1"} 63230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 297
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10307
telemt_me_keepalive_timeout_total 4758
telemt_me_reconnect_attempts_total 120429
telemt_me_reconnect_success_total 27308
telemt_me_reader_eof_total 30991
telemt_me_idle_close_by_peer_total 30984
telemt_me_route_drop_no_conn_total 150633
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365485
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1491
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1047
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 567
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 30562
telemt_me_refill_failed_total 2904
telemt_me_writer_restored_same_endpoint_total 27298
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3254
telemt_user_connections_total{user="hello"} 384342
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 8693529411 (8.10 GB)
telemt_user_octets_to_client{user="hello"} 139802112088 (130.20 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 82463.9 (22h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141019
telemt_connections_bad_total 18860
telemt_handshake_timeouts_total 1440
telemt_upstream_connect_attempt_total 31408
telemt_upstream_connect_success_total 31107
telemt_upstream_connect_fail_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 31408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 301
telemt_me_keepalive_timeout_total 1266
telemt_me_reconnect_attempts_total 35483
telemt_me_reconnect_success_total 22091
telemt_me_reader_eof_total 23666
telemt_me_idle_close_by_peer_total 23666
telemt_me_route_drop_no_conn_total 43719
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111342
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 604
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 22715
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22073
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 624
telemt_user_connections_total{user="hello"} 116236
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 1363022041 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 52061686099 (48.49 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 132248.5 (36h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 809736
telemt_connections_bad_total 24934
telemt_handshake_timeouts_total 24944
telemt_upstream_connect_attempt_total 27260
telemt_upstream_connect_success_total 27116
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 27260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 3091
telemt_me_reconnect_attempts_total 25219
telemt_me_reconnect_success_total 20572
telemt_me_reader_eof_total 22063
telemt_me_idle_close_by_peer_total 22060
telemt_me_route_drop_no_conn_total 385247
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 759339
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 20992
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20565
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 420
telemt_user_connections_total{user="hello"} 732197
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 12799079272 (11.92 GB)
telemt_user_octets_to_client{user="hello"} 359600938436 (334.90 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 45
```