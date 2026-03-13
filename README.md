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

# Server Metrics 2026-03-13 08:40:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 90399.7 (25h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352166
telemt_connections_bad_total 3176
telemt_handshake_timeouts_total 7725
telemt_upstream_connect_attempt_total 22645
telemt_upstream_connect_success_total 22538
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 22645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1672
telemt_me_reconnect_attempts_total 21504
telemt_me_reconnect_success_total 17997
telemt_me_reader_eof_total 19238
telemt_me_idle_close_by_peer_total 19237
telemt_me_route_drop_no_conn_total 109840
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300735
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 976
telemt_desync_full_logged_total 361
telemt_desync_suppressed_total 615
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 18295
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17981
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 300426
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 4917872144 (4.58 GB)
telemt_user_octets_to_client{user="hello"} 136765031056 (127.37 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 90292.1 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160152
telemt_connections_bad_total 1501
telemt_handshake_timeouts_total 1206
telemt_upstream_connect_attempt_total 45508
telemt_upstream_connect_success_total 44889
telemt_upstream_connect_fail_total 619
telemt_upstream_connect_attempts_per_request{bucket="1"} 45508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 512
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 619
telemt_me_keepalive_timeout_total 695
telemt_me_reconnect_attempts_total 79244
telemt_me_reconnect_success_total 23873
telemt_me_reader_eof_total 26308
telemt_me_idle_close_by_peer_total 26308
telemt_me_route_drop_no_conn_total 60721
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134527
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
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
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 25796
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 23858
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1923
telemt_user_connections_total{user="hello"} 151021
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 1564509744 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 48569416895 (45.23 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 90255.6 (25h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193490
telemt_connections_bad_total 1993
telemt_handshake_timeouts_total 3412
telemt_upstream_connect_attempt_total 24533
telemt_upstream_connect_success_total 24530
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 582
telemt_me_reconnect_attempts_total 21151
telemt_me_reconnect_success_total 19968
telemt_me_reader_eof_total 21418
telemt_me_idle_close_by_peer_total 21418
telemt_me_route_drop_no_conn_total 74033
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180956
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 20188
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19948
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 180882
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 6720997236 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 75807937672 (70.60 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 90231.3 (25h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280076
telemt_connections_bad_total 13654
telemt_handshake_timeouts_total 2112
telemt_upstream_connect_attempt_total 37446
telemt_upstream_connect_success_total 27468
telemt_upstream_connect_fail_total 9978
telemt_upstream_connect_attempts_per_request{bucket="1"} 37446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13571
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9978
telemt_me_keepalive_timeout_total 3382
telemt_me_reconnect_attempts_total 72465
telemt_me_reconnect_success_total 20086
telemt_me_reader_eof_total 22358
telemt_me_idle_close_by_peer_total 22351
telemt_me_route_drop_no_conn_total 101001
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238270
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 878
telemt_desync_full_logged_total 260
telemt_desync_suppressed_total 618
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 21980
telemt_me_refill_failed_total 1632
telemt_me_writer_restored_same_endpoint_total 20076
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1894
telemt_user_connections_total{user="hello"} 240996
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 5369473266 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 91941996469 (85.63 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 40402.8 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51228
telemt_connections_bad_total 8199
telemt_handshake_timeouts_total 428
telemt_upstream_connect_attempt_total 14025
telemt_upstream_connect_success_total 13885
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 14025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 327
telemt_me_reconnect_attempts_total 14091
telemt_me_reconnect_success_total 11872
telemt_me_reader_eof_total 12631
telemt_me_idle_close_by_peer_total 12631
telemt_me_route_drop_no_conn_total 15471
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41186
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 12042
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 11854
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 41185
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 295990320 (282.28 MB)
telemt_user_octets_to_client{user="hello"} 11566544720 (10.77 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 90187.8 (25h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480924
telemt_connections_bad_total 13355
telemt_handshake_timeouts_total 4456
telemt_upstream_connect_attempt_total 19068
telemt_upstream_connect_success_total 18965
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 19068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 1536
telemt_me_reconnect_attempts_total 18113
telemt_me_reconnect_success_total 14471
telemt_me_reader_eof_total 15547
telemt_me_idle_close_by_peer_total 15544
telemt_me_route_drop_no_conn_total 250855
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 472591
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 392
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 14771
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14464
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 300
telemt_user_connections_total{user="hello"} 446056
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 8218109820 (7.65 GB)
telemt_user_octets_to_client{user="hello"} 254396607780 (236.93 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 68
```