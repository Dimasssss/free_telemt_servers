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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 04:04:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 119978.9 (33h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1369310
telemt_connections_bad_total 10476
telemt_handshake_timeouts_total 33638
telemt_upstream_connect_attempt_total 26473
telemt_upstream_connect_success_total 25961
telemt_upstream_connect_fail_total 512
telemt_upstream_connect_attempts_per_request{bucket="1"} 26473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 512
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34832
telemt_me_reconnect_success_total 17687
telemt_me_reader_eof_total 19192
telemt_me_idle_close_by_peer_total 19191
telemt_me_route_drop_no_conn_total 586964
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1261471
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7931
telemt_desync_full_logged_total 2365
telemt_desync_suppressed_total 5566
telemt_desync_frames_bucket_total{bucket="1_2"} 2097
telemt_desync_frames_bucket_total{bucket="3_10"} 3035
telemt_desync_frames_bucket_total{bucket="gt_10"} 2799
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 18486
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17665
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 799
telemt_user_connections_total{user="hello"} 1255680
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 25393822939 (23.65 GB)
telemt_user_octets_to_client{user="hello"} 444103882575 (413.60 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 120230.2 (33h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1466617
telemt_connections_bad_total 70327
telemt_handshake_timeouts_total 48181
telemt_upstream_connect_attempt_total 469745
telemt_upstream_connect_success_total 468133
telemt_upstream_connect_fail_total 1612
telemt_upstream_connect_attempts_per_request{bucket="1"} 469745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34178
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1612
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125951
telemt_me_reconnect_success_total 19226
telemt_me_reader_eof_total 21468
telemt_me_idle_close_by_peer_total 21455
telemt_me_route_drop_no_conn_total 380213
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 832991
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3784
telemt_desync_full_logged_total 1306
telemt_desync_suppressed_total 2478
telemt_desync_frames_bucket_total{bucket="1_2"} 737
telemt_desync_frames_bucket_total{bucket="3_10"} 1557
telemt_desync_frames_bucket_total{bucket="gt_10"} 1490
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 20844
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19208
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1618
telemt_user_connections_total{user="hello"} 1275311
telemt_user_connections_current{user="hello"} 1178
telemt_user_octets_from_client{user="hello"} 17281200257 (16.09 GB)
telemt_user_octets_to_client{user="hello"} 462753835954 (430.97 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 410
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 120006.1 (33h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 899234
telemt_connections_bad_total 63348
telemt_handshake_timeouts_total 25762
telemt_upstream_connect_attempt_total 27815
telemt_upstream_connect_success_total 27655
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 27815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42325
telemt_me_reconnect_success_total 21628
telemt_me_reader_eof_total 23520
telemt_me_idle_close_by_peer_total 23513
telemt_me_route_drop_no_conn_total 348091
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 754506
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2366
telemt_desync_full_logged_total 770
telemt_desync_suppressed_total 1596
telemt_desync_frames_bucket_total{bucket="1_2"} 680
telemt_desync_frames_bucket_total{bucket="3_10"} 910
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 22563
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21616
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 935
telemt_user_connections_total{user="hello"} 752620
telemt_user_connections_current{user="hello"} 873
telemt_user_octets_from_client{user="hello"} 44726493800 (41.65 GB)
telemt_user_octets_to_client{user="hello"} 343271591292 (319.70 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 120065.8 (33h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1371740
telemt_connections_bad_total 65481
telemt_handshake_timeouts_total 24090
telemt_upstream_connect_attempt_total 90803
telemt_upstream_connect_success_total 88368
telemt_upstream_connect_fail_total 2435
telemt_upstream_connect_attempts_per_request{bucket="1"} 90803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2435
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38024
telemt_me_reconnect_success_total 17616
telemt_me_reader_eof_total 19344
telemt_me_idle_close_by_peer_total 19341
telemt_me_route_drop_no_conn_total 558755
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1114470
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4152
telemt_desync_full_logged_total 1370
telemt_desync_suppressed_total 2782
telemt_desync_frames_bucket_total{bucket="1_2"} 1024
telemt_desync_frames_bucket_total{bucket="3_10"} 1734
telemt_desync_frames_bucket_total{bucket="gt_10"} 1394
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 18578
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17596
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 962
telemt_user_connections_total{user="hello"} 1177833
telemt_user_connections_current{user="hello"} 928
telemt_user_octets_from_client{user="hello"} 18389962486 (17.13 GB)
telemt_user_octets_to_client{user="hello"} 567637689466 (528.65 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 120037.7 (33h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 933412
telemt_connections_bad_total 101948
telemt_handshake_timeouts_total 7666
telemt_upstream_connect_attempt_total 47582
telemt_upstream_connect_success_total 46929
telemt_upstream_connect_fail_total 653
telemt_upstream_connect_attempts_per_request{bucket="1"} 47582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 419
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 653
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59428
telemt_me_reconnect_success_total 24463
telemt_me_reader_eof_total 26486
telemt_me_idle_close_by_peer_total 26483
telemt_me_route_drop_no_conn_total 298157
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 759018
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3399
telemt_desync_full_logged_total 1027
telemt_desync_suppressed_total 2372
telemt_desync_frames_bucket_total{bucket="1_2"} 1038
telemt_desync_frames_bucket_total{bucket="3_10"} 1343
telemt_desync_frames_bucket_total{bucket="gt_10"} 1018
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25935
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24455
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1472
telemt_user_connections_total{user="hello"} 775531
telemt_user_connections_current{user="hello"} 1028
telemt_user_octets_from_client{user="hello"} 14800611952 (13.78 GB)
telemt_user_octets_to_client{user="hello"} 388929055880 (362.22 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 120198.5 (33h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1162907
telemt_connections_bad_total 126864
telemt_handshake_timeouts_total 10308
telemt_upstream_connect_attempt_total 23944
telemt_upstream_connect_success_total 23805
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 23944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29120
telemt_me_reconnect_success_total 17826
telemt_me_reader_eof_total 19325
telemt_me_idle_close_by_peer_total 19323
telemt_me_route_drop_no_conn_total 803435
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1141725
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2142
telemt_desync_full_logged_total 752
telemt_desync_suppressed_total 1390
telemt_desync_frames_bucket_total{bucket="1_2"} 472
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 858
telemt_pool_swap_total 108
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18454
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17812
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 953847
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 15213046672 (14.17 GB)
telemt_user_octets_to_client{user="hello"} 419174928540 (390.39 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 67965.7 (18h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478125
telemt_connections_bad_total 47451
telemt_handshake_timeouts_total 12361
telemt_upstream_connect_attempt_total 24494
telemt_upstream_connect_success_total 24246
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 24494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32319
telemt_me_reconnect_success_total 20708
telemt_me_reader_eof_total 21894
telemt_me_idle_close_by_peer_total 21894
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 115948
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344803
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1514
telemt_desync_full_logged_total 493
telemt_desync_suppressed_total 1021
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 681
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21293
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20665
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 344596
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 23297153145 (21.70 GB)
telemt_user_octets_to_client{user="hello"} 283094973222 (263.65 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 84
```