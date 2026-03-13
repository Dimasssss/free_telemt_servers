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

# Server Metrics 2026-03-13 17:53:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 123600.3 (34h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521926
telemt_connections_bad_total 8321
telemt_handshake_timeouts_total 12028
telemt_upstream_connect_attempt_total 31038
telemt_upstream_connect_success_total 30887
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 31038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3443
telemt_me_reconnect_attempts_total 29331
telemt_me_reconnect_success_total 24691
telemt_me_reader_eof_total 26384
telemt_me_idle_close_by_peer_total 26383
telemt_me_route_drop_no_conn_total 170160
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 453616
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1463
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 957
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 534
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 25108
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 24675
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 417
telemt_user_connections_total{user="hello"} 453184
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 8364559484 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 213385750468 (198.73 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 123494.0 (34h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257425
telemt_connections_bad_total 1951
telemt_handshake_timeouts_total 1824
telemt_upstream_connect_attempt_total 110869
telemt_upstream_connect_success_total 110024
telemt_upstream_connect_fail_total 845
telemt_upstream_connect_attempts_per_request{bucket="1"} 110869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1576
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 845
telemt_me_keepalive_timeout_total 1516
telemt_me_reconnect_attempts_total 126816
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29936
telemt_me_idle_close_by_peer_total 29936
telemt_me_route_drop_no_conn_total 82517
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166175
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 30
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
telemt_me_writer_removed_unexpected_total 29406
telemt_me_refill_failed_total 3145
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3373
telemt_user_connections_total{user="hello"} 243771
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 2549590371 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 74961965865 (69.81 GB)
telemt_user_msgs_from_client{user="hello"} 1219267
telemt_user_msgs_to_client{user="hello"} 7104675
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 123457.4 (34h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303876
telemt_connections_bad_total 2515
telemt_handshake_timeouts_total 17456
telemt_upstream_connect_attempt_total 32956
telemt_upstream_connect_success_total 32952
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32956
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2636
telemt_me_reconnect_attempts_total 27952
telemt_me_reconnect_success_total 26723
telemt_me_reader_eof_total 28653
telemt_me_idle_close_by_peer_total 28653
telemt_me_route_drop_no_conn_total 108554
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273215
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 27021
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26703
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 273126
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 10172390372 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 112433468132 (104.71 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 123433.0 (34h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410223
telemt_connections_bad_total 15106
telemt_handshake_timeouts_total 3866
telemt_upstream_connect_attempt_total 60200
telemt_upstream_connect_success_total 49948
telemt_upstream_connect_fail_total 10252
telemt_upstream_connect_attempts_per_request{bucket="1"} 60200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17884
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 281
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10252
telemt_me_keepalive_timeout_total 4656
telemt_me_reconnect_attempts_total 114396
telemt_me_reconnect_success_total 24741
telemt_me_reader_eof_total 28242
telemt_me_idle_close_by_peer_total 28235
telemt_me_route_drop_no_conn_total 141395
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342331
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1353
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 950
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 27853
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 24731
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3112
telemt_user_connections_total{user="hello"} 361221
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 8369037711 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 129214775164 (120.34 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 73604.6 (20h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120780
telemt_connections_bad_total 15258
telemt_handshake_timeouts_total 1396
telemt_upstream_connect_attempt_total 29040
telemt_upstream_connect_success_total 28772
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 29040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 1177
telemt_me_reconnect_attempts_total 33581
telemt_me_reconnect_success_total 20193
telemt_me_reader_eof_total 21648
telemt_me_idle_close_by_peer_total 21648
telemt_me_route_drop_no_conn_total 37833
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95347
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 451
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 20795
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20175
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 602
telemt_user_connections_total{user="hello"} 100244
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 1194479269 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 32922977987 (30.66 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 123389.8 (34h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 754264
telemt_connections_bad_total 24760
telemt_handshake_timeouts_total 24460
telemt_upstream_connect_attempt_total 25683
telemt_upstream_connect_success_total 25546
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 25683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 2983
telemt_me_reconnect_attempts_total 24043
telemt_me_reconnect_success_total 19400
telemt_me_reader_eof_total 20819
telemt_me_idle_close_by_peer_total 20816
telemt_me_route_drop_no_conn_total 357435
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 707599
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 680
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 19799
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19393
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 680485
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 11960195912 (11.14 GB)
telemt_user_octets_to_client{user="hello"} 339640235152 (316.31 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 46
```