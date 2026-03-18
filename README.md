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

# Server Metrics 2026-03-18 03:49:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 119061.4 (33h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1358993
telemt_connections_bad_total 10404
telemt_handshake_timeouts_total 33496
telemt_upstream_connect_attempt_total 26312
telemt_upstream_connect_success_total 25802
telemt_upstream_connect_fail_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 26312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 510
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34716
telemt_me_reconnect_success_total 17572
telemt_me_reader_eof_total 19070
telemt_me_idle_close_by_peer_total 19069
telemt_me_route_drop_no_conn_total 583549
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1251767
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7893
telemt_desync_full_logged_total 2351
telemt_desync_suppressed_total 5542
telemt_desync_frames_bucket_total{bucket="1_2"} 2085
telemt_desync_frames_bucket_total{bucket="3_10"} 3020
telemt_desync_frames_bucket_total{bucket="gt_10"} 2788
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 18370
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17550
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 798
telemt_user_connections_total{user="hello"} 1245974
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 25219111791 (23.49 GB)
telemt_user_octets_to_client{user="hello"} 442003029887 (411.65 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 119312.8 (33h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1449089
telemt_connections_bad_total 67874
telemt_handshake_timeouts_total 48000
telemt_upstream_connect_attempt_total 469479
telemt_upstream_connect_success_total 467873
telemt_upstream_connect_fail_total 1606
telemt_upstream_connect_attempts_per_request{bucket="1"} 469479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1606
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125734
telemt_me_reconnect_success_total 19010
telemt_me_reader_eof_total 21249
telemt_me_idle_close_by_peer_total 21236
telemt_me_route_drop_no_conn_total 375365
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 818578
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3748
telemt_desync_full_logged_total 1288
telemt_desync_suppressed_total 2460
telemt_desync_frames_bucket_total{bucket="1_2"} 733
telemt_desync_frames_bucket_total{bucket="3_10"} 1547
telemt_desync_frames_bucket_total{bucket="gt_10"} 1468
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 20625
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 18992
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1615
telemt_user_connections_total{user="hello"} 1260907
telemt_user_connections_current{user="hello"} 1005
telemt_user_octets_from_client{user="hello"} 16959415341 (15.79 GB)
telemt_user_octets_to_client{user="hello"} 453107069550 (421.99 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 119088.8 (33h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 884614
telemt_connections_bad_total 61835
telemt_handshake_timeouts_total 25350
telemt_upstream_connect_attempt_total 27651
telemt_upstream_connect_success_total 27492
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 27651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42205
telemt_me_reconnect_success_total 21509
telemt_me_reader_eof_total 23390
telemt_me_idle_close_by_peer_total 23383
telemt_me_route_drop_no_conn_total 344677
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 744884
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2347
telemt_desync_full_logged_total 764
telemt_desync_suppressed_total 1583
telemt_desync_frames_bucket_total{bucket="1_2"} 672
telemt_desync_frames_bucket_total{bucket="3_10"} 902
telemt_desync_frames_bucket_total{bucket="gt_10"} 773
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 22441
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21497
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 932
telemt_user_connections_total{user="hello"} 742999
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 44575272804 (41.51 GB)
telemt_user_octets_to_client{user="hello"} 337108308240 (313.96 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 119148.1 (33h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1360679
telemt_connections_bad_total 64583
telemt_handshake_timeouts_total 23793
telemt_upstream_connect_attempt_total 90591
telemt_upstream_connect_success_total 88159
telemt_upstream_connect_fail_total 2432
telemt_upstream_connect_attempts_per_request{bucket="1"} 90591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2432
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37860
telemt_me_reconnect_success_total 17453
telemt_me_reader_eof_total 19180
telemt_me_idle_close_by_peer_total 19177
telemt_me_route_drop_no_conn_total 555119
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1104959
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4124
telemt_desync_full_logged_total 1359
telemt_desync_suppressed_total 2765
telemt_desync_frames_bucket_total{bucket="1_2"} 1016
telemt_desync_frames_bucket_total{bucket="3_10"} 1725
telemt_desync_frames_bucket_total{bucket="gt_10"} 1383
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 18414
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17433
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 961
telemt_user_connections_total{user="hello"} 1168324
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 18226863850 (16.98 GB)
telemt_user_octets_to_client{user="hello"} 560153441338 (521.68 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 119120.1 (33h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 921348
telemt_connections_bad_total 101763
telemt_handshake_timeouts_total 7551
telemt_upstream_connect_attempt_total 47362
telemt_upstream_connect_success_total 46715
telemt_upstream_connect_fail_total 647
telemt_upstream_connect_attempts_per_request{bucket="1"} 47362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17302
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 647
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59257
telemt_me_reconnect_success_total 24293
telemt_me_reader_eof_total 26316
telemt_me_idle_close_by_peer_total 26313
telemt_me_route_drop_no_conn_total 294295
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 747594
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3363
telemt_desync_full_logged_total 1015
telemt_desync_suppressed_total 2348
telemt_desync_frames_bucket_total{bucket="1_2"} 1036
telemt_desync_frames_bucket_total{bucket="3_10"} 1338
telemt_desync_frames_bucket_total{bucket="gt_10"} 989
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25765
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24285
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1472
telemt_user_connections_total{user="hello"} 764110
telemt_user_connections_current{user="hello"} 784
telemt_user_octets_from_client{user="hello"} 14612543180 (13.61 GB)
telemt_user_octets_to_client{user="hello"} 381044508760 (354.88 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 119281.1 (33h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1156556
telemt_connections_bad_total 126855
telemt_handshake_timeouts_total 10239
telemt_upstream_connect_attempt_total 23780
telemt_upstream_connect_success_total 23642
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 23780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29000
telemt_me_reconnect_success_total 17707
telemt_me_reader_eof_total 19196
telemt_me_idle_close_by_peer_total 19194
telemt_me_route_drop_no_conn_total 796399
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1132088
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2135
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 107
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18334
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17693
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 947703
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 15138161888 (14.10 GB)
telemt_user_octets_to_client{user="hello"} 415774106052 (387.22 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 67048.3 (18h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467007
telemt_connections_bad_total 46965
telemt_handshake_timeouts_total 12010
telemt_upstream_connect_attempt_total 24270
telemt_upstream_connect_success_total 24026
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 24270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32142
telemt_me_reconnect_success_total 20531
telemt_me_reader_eof_total 21705
telemt_me_idle_close_by_peer_total 21705
telemt_me_seq_mismatch_total 32
telemt_me_route_drop_no_conn_total 113685
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337514
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1477
telemt_desync_full_logged_total 482
telemt_desync_suppressed_total 995
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 666
telemt_desync_frames_bucket_total{bucket="gt_10"} 566
telemt_pool_swap_total 45
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21114
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20489
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 337307
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 23174200037 (21.58 GB)
telemt_user_octets_to_client{user="hello"} 278160896102 (259.06 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 63
```