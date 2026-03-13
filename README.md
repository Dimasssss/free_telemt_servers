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

# Server Metrics 2026-03-13 21:32:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 136736.7 (37h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571064
telemt_connections_bad_total 16527
telemt_handshake_timeouts_total 12764
telemt_upstream_connect_attempt_total 34664
telemt_upstream_connect_success_total 34490
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 34664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5107
telemt_me_reconnect_attempts_total 31944
telemt_me_reconnect_success_total 27288
telemt_me_reader_eof_total 29127
telemt_me_idle_close_by_peer_total 29126
telemt_me_route_drop_no_conn_total 188383
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 491495
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1574
telemt_desync_full_logged_total 535
telemt_desync_suppressed_total 1039
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 583
telemt_desync_frames_bucket_total{bucket="gt_10"} 651
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 27740
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27272
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 491390
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 14751287578 (13.74 GB)
telemt_user_octets_to_client{user="hello"} 240469583652 (223.95 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 136629.8 (37h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289854
telemt_connections_bad_total 2136
telemt_handshake_timeouts_total 1902
telemt_upstream_connect_attempt_total 138035
telemt_upstream_connect_success_total 137036
telemt_upstream_connect_fail_total 999
telemt_upstream_connect_attempts_per_request{bucket="1"} 138035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2409
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 999
telemt_me_keepalive_timeout_total 3666
telemt_me_reconnect_attempts_total 143983
telemt_me_reconnect_success_total 26908
telemt_me_reader_eof_total 31303
telemt_me_idle_close_by_peer_total 31303
telemt_me_route_drop_no_conn_total 85176
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171893
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
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 30815
telemt_me_refill_failed_total 3653
telemt_me_writer_restored_same_endpoint_total 26891
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3907
telemt_user_connections_total{user="hello"} 275006
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 2845290399 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 83535837531 (77.80 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 136595.8 (37h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337536
telemt_connections_bad_total 2658
telemt_handshake_timeouts_total 26534
telemt_upstream_connect_attempt_total 36328
telemt_upstream_connect_success_total 36323
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19520
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2845
telemt_me_reconnect_attempts_total 30718
telemt_me_reconnect_success_total 29473
telemt_me_reader_eof_total 31611
telemt_me_idle_close_by_peer_total 31611
telemt_me_route_drop_no_conn_total 120357
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 296447
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
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 29807
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29453
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 334
telemt_user_connections_total{user="hello"} 296348
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 12317228156 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 123215172996 (114.75 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 136569.2 (37h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 442760
telemt_connections_bad_total 15257
telemt_handshake_timeouts_total 4215
telemt_upstream_connect_attempt_total 63949
telemt_upstream_connect_success_total 53606
telemt_upstream_connect_fail_total 10343
telemt_upstream_connect_attempts_per_request{bucket="1"} 63949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19859
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 301
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10343
telemt_me_keepalive_timeout_total 4769
telemt_me_reconnect_attempts_total 127545
telemt_me_reconnect_success_total 27766
telemt_me_reader_eof_total 31662
telemt_me_idle_close_by_peer_total 31655
telemt_me_route_drop_no_conn_total 153954
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 373420
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1588
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1119
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 604
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31233
telemt_me_refill_failed_total 3112
telemt_me_writer_restored_same_endpoint_total 27756
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3467
telemt_user_connections_total{user="hello"} 392277
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 8862309727 (8.25 GB)
telemt_user_octets_to_client{user="hello"} 147369655900 (137.25 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 86740.5 (24h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147934
telemt_connections_bad_total 21664
telemt_handshake_timeouts_total 1524
telemt_upstream_connect_attempt_total 32483
telemt_upstream_connect_success_total 32174
telemt_upstream_connect_fail_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 32483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 309
telemt_me_keepalive_timeout_total 1291
telemt_me_reconnect_attempts_total 36335
telemt_me_reconnect_success_total 22940
telemt_me_reader_eof_total 24574
telemt_me_idle_close_by_peer_total 24574
telemt_me_route_drop_no_conn_total 45484
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115228
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
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 23574
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22922
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 634
telemt_user_connections_total{user="hello"} 120122
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 1384922625 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 55905325931 (52.07 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 136525.0 (37h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 829947
telemt_connections_bad_total 27126
telemt_handshake_timeouts_total 25077
telemt_upstream_connect_attempt_total 28102
telemt_upstream_connect_success_total 27954
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 28102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 3117
telemt_me_reconnect_attempts_total 25839
telemt_me_reconnect_success_total 21188
telemt_me_reader_eof_total 22723
telemt_me_idle_close_by_peer_total 22720
telemt_me_route_drop_no_conn_total 394720
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 776540
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
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 21616
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21181
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 749402
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 13054840340 (12.16 GB)
telemt_user_octets_to_client{user="hello"} 371397337504 (345.89 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 46
```