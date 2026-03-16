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

# Server Metrics 2026-03-16 07:38:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 120266.5 (33h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 552491
telemt_connections_bad_total 5753
telemt_handshake_timeouts_total 19439
telemt_upstream_connect_attempt_total 28197
telemt_upstream_connect_success_total 28065
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 28197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15559
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25553
telemt_me_reconnect_success_total 22119
telemt_me_reader_eof_total 23666
telemt_me_idle_close_by_peer_total 23666
telemt_me_route_drop_no_conn_total 523639
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549542
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2678
telemt_desync_full_logged_total 1058
telemt_desync_suppressed_total 1620
telemt_desync_frames_bucket_total{bucket="1_2"} 569
telemt_desync_frames_bucket_total{bucket="3_10"} 1034
telemt_desync_frames_bucket_total{bucket="gt_10"} 1075
telemt_pool_swap_total 117
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22470
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22085
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 351
telemt_user_connections_total{user="hello"} 488364
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 9444063048 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 317270996988 (295.48 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 120273.2 (33h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220288
telemt_connections_bad_total 3155
telemt_handshake_timeouts_total 15074
telemt_upstream_connect_attempt_total 32307
telemt_upstream_connect_success_total 32232
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 32307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 623
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 32782
telemt_me_reconnect_success_total 25863
telemt_me_reader_eof_total 27701
telemt_me_idle_close_by_peer_total 27700
telemt_me_route_drop_no_conn_total 108150
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194250
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 26429
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 25847
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 566
telemt_user_connections_total{user="hello"} 193797
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 4497718917 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 108571483636 (101.12 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 120265.7 (33h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238436
telemt_connections_bad_total 5731
telemt_handshake_timeouts_total 4596
telemt_upstream_connect_attempt_total 33450
telemt_upstream_connect_success_total 33442
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 33450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34829
telemt_me_reconnect_success_total 27427
telemt_me_reader_eof_total 29529
telemt_me_idle_close_by_peer_total 29528
telemt_me_route_drop_no_conn_total 83331
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190330
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 27924
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 27419
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 190042
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 17468479405 (16.27 GB)
telemt_user_octets_to_client{user="hello"} 111767577124 (104.09 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 120265.6 (33h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325904
telemt_connections_bad_total 1335
telemt_handshake_timeouts_total 2928
telemt_upstream_connect_attempt_total 27858
telemt_upstream_connect_success_total 27827
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 27858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 21995
telemt_me_reconnect_success_total 21859
telemt_me_reader_eof_total 23345
telemt_me_idle_close_by_peer_total 23344
telemt_me_route_drop_no_conn_total 115492
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299900
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1065
telemt_desync_full_logged_total 367
telemt_desync_suppressed_total 698
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 453
telemt_desync_frames_bucket_total{bucket="gt_10"} 391
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 22142
telemt_me_writer_restored_same_endpoint_total 21848
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 299781
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 4846274834 (4.51 GB)
telemt_user_octets_to_client{user="hello"} 129217794888 (120.34 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 95336.8 (26h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215104
telemt_connections_bad_total 35857
telemt_handshake_timeouts_total 3612
telemt_upstream_connect_attempt_total 27204
telemt_upstream_connect_success_total 27055
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 27204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 116659
telemt_me_reconnect_success_total 22169
telemt_me_reader_eof_total 23552
telemt_me_idle_close_by_peer_total 23552
telemt_me_route_drop_no_conn_total 67543
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170138
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 491
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 369
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 212
telemt_desync_frames_bucket_total{bucket="gt_10"} 213
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 22351
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 22065
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 169766
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 2319355517 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 72587617859 (67.60 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 120264.9 (33h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 787215
telemt_connections_bad_total 68396
telemt_handshake_timeouts_total 6659
telemt_upstream_connect_attempt_total 25297
telemt_upstream_connect_success_total 25164
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 25297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13099
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20528
telemt_me_reconnect_success_total 19181
telemt_me_reader_eof_total 20488
telemt_me_idle_close_by_peer_total 20488
telemt_me_route_drop_no_conn_total 636372
telemt_me_route_drop_channel_closed_total 104
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 788873
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 19450
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19154
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 647509
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 14314246908 (13.33 GB)
telemt_user_octets_to_client{user="hello"} 390422891416 (363.61 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 69
```