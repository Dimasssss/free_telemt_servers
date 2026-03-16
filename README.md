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

# Server Metrics 2026-03-16 03:54:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 106784.7 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456460
telemt_connections_bad_total 5376
telemt_handshake_timeouts_total 15545
telemt_upstream_connect_attempt_total 25532
telemt_upstream_connect_success_total 25414
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 25532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 23549
telemt_me_reconnect_success_total 20126
telemt_me_reader_eof_total 21523
telemt_me_idle_close_by_peer_total 21523
telemt_me_route_drop_no_conn_total 501834
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 478597
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2321
telemt_desync_full_logged_total 934
telemt_desync_suppressed_total 1387
telemt_desync_frames_bucket_total{bucket="1_2"} 465
telemt_desync_frames_bucket_total{bucket="3_10"} 909
telemt_desync_frames_bucket_total{bucket="gt_10"} 947
telemt_pool_swap_total 102
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20450
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 20092
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 417454
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 8532730060 (7.95 GB)
telemt_user_octets_to_client{user="hello"} 295037128532 (274.77 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 106791.0 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184942
telemt_connections_bad_total 2974
telemt_handshake_timeouts_total 14664
telemt_upstream_connect_attempt_total 29088
telemt_upstream_connect_success_total 29013
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 29088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 30219
telemt_me_reconnect_success_total 23311
telemt_me_reader_eof_total 24974
telemt_me_idle_close_by_peer_total 24973
telemt_me_route_drop_no_conn_total 93739
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160596
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 23852
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 23295
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 541
telemt_user_connections_total{user="hello"} 160142
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 3483161757 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 83333576916 (77.61 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 106783.7 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204741
telemt_connections_bad_total 3133
telemt_handshake_timeouts_total 4027
telemt_upstream_connect_attempt_total 30158
telemt_upstream_connect_success_total 30150
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 30158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 32187
telemt_me_reconnect_success_total 24797
telemt_me_reader_eof_total 26708
telemt_me_idle_close_by_peer_total 26707
telemt_me_route_drop_no_conn_total 72945
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163298
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 25273
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 24789
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 163031
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 16437719661 (15.31 GB)
telemt_user_octets_to_client{user="hello"} 101914298284 (94.92 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 106783.3 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269986
telemt_connections_bad_total 1229
telemt_handshake_timeouts_total 1705
telemt_upstream_connect_attempt_total 25024
telemt_upstream_connect_success_total 25003
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 25024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12903
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 19828
telemt_me_reconnect_success_total 19711
telemt_me_reader_eof_total 21045
telemt_me_idle_close_by_peer_total 21044
telemt_me_route_drop_no_conn_total 99456
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249632
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 885
telemt_desync_full_logged_total 315
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 385
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 19953
telemt_me_writer_restored_same_endpoint_total 19700
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 249514
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 4272494900 (3.98 GB)
telemt_user_octets_to_client{user="hello"} 112759873212 (105.02 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 81854.8 (22h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179124
telemt_connections_bad_total 31577
telemt_handshake_timeouts_total 3161
telemt_upstream_connect_attempt_total 23297
telemt_upstream_connect_success_total 23168
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 23297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 113424
telemt_me_reconnect_success_total 18952
telemt_me_reader_eof_total 20126
telemt_me_idle_close_by_peer_total 20126
telemt_me_route_drop_no_conn_total 56788
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140017
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 19102
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 18848
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 139653
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 1952934345 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 60714143639 (56.54 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 106782.6 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 683875
telemt_connections_bad_total 58745
telemt_handshake_timeouts_total 5082
telemt_upstream_connect_attempt_total 22723
telemt_upstream_connect_success_total 22603
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 22723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 18618
telemt_me_reconnect_success_total 17285
telemt_me_reader_eof_total 18447
telemt_me_idle_close_by_peer_total 18447
telemt_me_route_drop_no_conn_total 597784
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 707594
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
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 17525
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 17258
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 566279
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 13057313152 (12.16 GB)
telemt_user_octets_to_client{user="hello"} 350306808436 (326.25 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 39
```