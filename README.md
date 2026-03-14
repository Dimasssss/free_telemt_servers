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

# Server Metrics 2026-03-14 01:26:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 150795.5 (41h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 596198
telemt_connections_bad_total 21713
telemt_handshake_timeouts_total 12872
telemt_upstream_connect_attempt_total 38457
telemt_upstream_connect_success_total 38267
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 38457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5495
telemt_me_reconnect_attempts_total 35025
telemt_me_reconnect_success_total 30351
telemt_me_reader_eof_total 32417
telemt_me_idle_close_by_peer_total 32416
telemt_me_route_drop_no_conn_total 195677
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 510629
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1651
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 1084
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 675
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 30830
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 30335
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 479
telemt_user_connections_total{user="hello"} 510524
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 15552058614 (14.48 GB)
telemt_user_octets_to_client{user="hello"} 251865589780 (234.57 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 150688.4 (41h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305571
telemt_connections_bad_total 2236
telemt_handshake_timeouts_total 1939
telemt_upstream_connect_attempt_total 142978
telemt_upstream_connect_success_total 141868
telemt_upstream_connect_fail_total 1109
telemt_upstream_connect_attempts_per_request{bucket="1"} 142977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1109
telemt_me_keepalive_timeout_total 3790
telemt_me_reconnect_attempts_total 161975
telemt_me_reconnect_success_total 31027
telemt_me_reader_eof_total 35922
telemt_me_idle_close_by_peer_total 35922
telemt_me_route_drop_no_conn_total 96177
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186582
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 39
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
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 35410
telemt_me_refill_failed_total 4086
telemt_me_writer_restored_same_endpoint_total 31010
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4383
telemt_user_connections_total{user="hello"} 289694
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 3031468551 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 90440612215 (84.23 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 150652.2 (41h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357970
telemt_connections_bad_total 2823
telemt_handshake_timeouts_total 33211
telemt_upstream_connect_attempt_total 39985
telemt_upstream_connect_success_total 39979
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 39985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3282
telemt_me_reconnect_attempts_total 33679
telemt_me_reconnect_success_total 32416
telemt_me_reader_eof_total 34831
telemt_me_idle_close_by_peer_total 34831
telemt_me_route_drop_no_conn_total 127047
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309451
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
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 32799
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 32396
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 309346
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 12610800592 (11.74 GB)
telemt_user_octets_to_client{user="hello"} 126889782372 (118.18 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 150627.8 (41h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459121
telemt_connections_bad_total 15368
telemt_handshake_timeouts_total 4321
telemt_upstream_connect_attempt_total 68405
telemt_upstream_connect_success_total 57955
telemt_upstream_connect_fail_total 10449
telemt_upstream_connect_attempts_per_request{bucket="1"} 68404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 319
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10449
telemt_me_keepalive_timeout_total 5076
telemt_me_reconnect_attempts_total 136382
telemt_me_reconnect_success_total 31403
telemt_me_reader_eof_total 35592
telemt_me_idle_close_by_peer_total 35584
telemt_me_route_drop_no_conn_total 162111
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 389074
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 35062
telemt_me_refill_failed_total 3274
telemt_me_writer_restored_same_endpoint_total 31393
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3659
telemt_user_connections_total{user="hello"} 407916
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 9061364763 (8.44 GB)
telemt_user_octets_to_client{user="hello"} 155436323760 (144.76 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 100799.3 (27h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168250
telemt_connections_bad_total 24574
telemt_handshake_timeouts_total 1556
telemt_upstream_connect_attempt_total 36978
telemt_upstream_connect_success_total 36641
telemt_upstream_connect_fail_total 337
telemt_upstream_connect_attempts_per_request{bucket="1"} 36978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18658
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 337
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 40151
telemt_me_reconnect_success_total 26739
telemt_me_reader_eof_total 28591
telemt_me_idle_close_by_peer_total 28591
telemt_me_route_drop_no_conn_total 50159
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132347
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 27400
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 26721
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 661
telemt_user_connections_total{user="hello"} 137156
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 1855431673 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 64214371627 (59.80 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 150583.8 (41h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 879050
telemt_connections_bad_total 27477
telemt_handshake_timeouts_total 25322
telemt_upstream_connect_attempt_total 31100
telemt_upstream_connect_success_total 30933
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 31100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 3476
telemt_me_reconnect_attempts_total 28124
telemt_me_reconnect_success_total 23459
telemt_me_reader_eof_total 25133
telemt_me_idle_close_by_peer_total 25130
telemt_me_route_drop_no_conn_total 418482
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 821449
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 23910
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23452
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 451
telemt_user_connections_total{user="hello"} 794205
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 14123886956 (13.15 GB)
telemt_user_octets_to_client{user="hello"} 405442820480 (377.60 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 32
```