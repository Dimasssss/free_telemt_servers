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

# Server Metrics 2026-03-18 18:17:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10317.7 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287357
telemt_connections_bad_total 17784
telemt_handshake_timeouts_total 7099
telemt_upstream_connect_attempt_total 1721
telemt_upstream_connect_success_total 1721
telemt_upstream_connect_attempts_per_request{bucket="1"} 1721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 1177
telemt_me_reconnect_success_total 1172
telemt_me_reader_eof_total 1213
telemt_me_idle_close_by_peer_total 1213
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 130337
telemt_me_route_drop_channel_closed_total 53
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245562
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1348
telemt_desync_full_logged_total 401
telemt_desync_suppressed_total 947
telemt_desync_frames_bucket_total{bucket="1_2"} 328
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1197
telemt_me_writer_restored_same_endpoint_total 1157
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 245457
telemt_user_connections_current{user="hello"} 1277
telemt_user_octets_from_client{user="hello"} 3460428540 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 83446679164 (77.72 GB)
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 15146.2 (4h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1509302
telemt_connections_bad_total 101444
telemt_connections_current 3786
telemt_connections_me_current 3786
telemt_handshake_timeouts_total 28418
telemt_upstream_connect_attempt_total 2540
telemt_upstream_connect_success_total 2527
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1764
telemt_me_reconnect_success_total 1749
telemt_me_reader_eof_total 1729
telemt_me_idle_close_by_peer_total 1728
telemt_me_route_drop_no_conn_total 1505667
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1305482
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4103
telemt_desync_full_logged_total 1291
telemt_desync_suppressed_total 2812
telemt_desync_frames_bucket_total{bucket="1_2"} 720
telemt_desync_frames_bucket_total{bucket="3_10"} 1610
telemt_desync_frames_bucket_total{bucket="gt_10"} 1773
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1692
telemt_me_writer_restored_same_endpoint_total 1747
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1300828
telemt_user_connections_current{user="hello"} 3786
telemt_user_octets_from_client{user="hello"} 17039958720 (15.87 GB)
telemt_user_octets_to_client{user="hello"} 392309173664 (365.37 GB)
telemt_user_unique_ips_current{user="hello"} 1213
telemt_user_unique_ips_recent_window{user="hello"} 498
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 15074.8 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1084035
telemt_connections_bad_total 88828
telemt_connections_current 3347
telemt_connections_me_current 3347
telemt_handshake_timeouts_total 23393
telemt_upstream_connect_attempt_total 2107
telemt_upstream_connect_success_total 2096
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1332
telemt_me_reconnect_success_total 1318
telemt_me_reader_eof_total 1398
telemt_me_idle_close_by_peer_total 1398
telemt_me_route_drop_no_conn_total 471946
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 886565
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4039
telemt_desync_full_logged_total 1247
telemt_desync_suppressed_total 2792
telemt_desync_frames_bucket_total{bucket="1_2"} 1005
telemt_desync_frames_bucket_total{bucket="3_10"} 1524
telemt_desync_frames_bucket_total{bucket="gt_10"} 1510
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1357
telemt_me_writer_restored_same_endpoint_total 1301
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 886186
telemt_user_connections_current{user="hello"} 3347
telemt_user_octets_from_client{user="hello"} 20687096184 (19.27 GB)
telemt_user_octets_to_client{user="hello"} 390720551680 (363.89 GB)
telemt_user_unique_ips_current{user="hello"} 1064
telemt_user_unique_ips_recent_window{user="hello"} 449
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 15789.1 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1601329
telemt_connections_bad_total 35940
telemt_connections_current 3087
telemt_connections_me_current 3087
telemt_handshake_timeouts_total 17352
telemt_upstream_connect_attempt_total 2400
telemt_upstream_connect_success_total 2382
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1571
telemt_me_reconnect_success_total 1550
telemt_me_reader_eof_total 1594
telemt_me_idle_close_by_peer_total 1593
telemt_me_route_drop_no_conn_total 2693111
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1434493
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5514
telemt_desync_full_logged_total 1360
telemt_desync_suppressed_total 4154
telemt_desync_frames_bucket_total{bucket="1_2"} 1234
telemt_desync_frames_bucket_total{bucket="3_10"} 2602
telemt_desync_frames_bucket_total{bucket="gt_10"} 1678
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1555
telemt_me_writer_restored_same_endpoint_total 1539
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1434435
telemt_user_connections_current{user="hello"} 3087
telemt_user_octets_from_client{user="hello"} 13577883004 (12.65 GB)
telemt_user_octets_to_client{user="hello"} 234768316904 (218.65 GB)
telemt_user_unique_ips_current{user="hello"} 933
telemt_user_unique_ips_recent_window{user="hello"} 481
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 10303.9 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 782367
telemt_connections_bad_total 144663
telemt_handshake_timeouts_total 7544
telemt_upstream_connect_attempt_total 1827
telemt_upstream_connect_success_total 1769
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 1827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 3307
telemt_me_reconnect_success_total 1216
telemt_me_reader_eof_total 1302
telemt_me_idle_close_by_peer_total 1302
telemt_me_route_drop_no_conn_total 329615
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 569660
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2048
telemt_desync_full_logged_total 708
telemt_desync_suppressed_total 1340
telemt_desync_frames_bucket_total{bucket="1_2"} 382
telemt_desync_frames_bucket_total{bucket="3_10"} 690
telemt_desync_frames_bucket_total{bucket="gt_10"} 976
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1298
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1190
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 569171
telemt_user_connections_current{user="hello"} 3540
telemt_user_octets_from_client{user="hello"} 9444232900 (8.80 GB)
telemt_user_octets_to_client{user="hello"} 242801306404 (226.13 GB)
telemt_user_unique_ips_current{user="hello"} 1119
telemt_user_unique_ips_recent_window{user="hello"} 476
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 15239.6 (4h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273953
telemt_connections_bad_total 10081
telemt_connections_current 808
telemt_connections_me_current 808
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2894
telemt_upstream_connect_attempt_total 6684
telemt_upstream_connect_success_total 6668
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 331531
telemt_me_reconnect_success_total 2064
telemt_me_reader_eof_total 2061
telemt_me_idle_close_by_peer_total 2061
telemt_me_route_drop_no_conn_total 179110
telemt_me_route_drop_channel_closed_total 81
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243111
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 460
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 288
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 12
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2010
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2053
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 246805
telemt_user_connections_current{user="hello"} 808
telemt_user_octets_from_client{user="hello"} 3553575269 (3.31 GB)
telemt_user_octets_to_client{user="hello"} 50896848849 (47.40 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 274
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 14308.3 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 852643
telemt_connections_bad_total 57027
telemt_connections_current 3127
telemt_connections_me_current 3127
telemt_handshake_timeouts_total 15085
telemt_upstream_connect_attempt_total 2440
telemt_upstream_connect_success_total 2439
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17217
telemt_me_reconnect_success_total 1702
telemt_me_reader_eof_total 1699
telemt_me_idle_close_by_peer_total 1699
telemt_me_route_drop_no_conn_total 442941
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 720651
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2938
telemt_desync_full_logged_total 1006
telemt_desync_suppressed_total 1932
telemt_desync_frames_bucket_total{bucket="1_2"} 692
telemt_desync_frames_bucket_total{bucket="3_10"} 1058
telemt_desync_frames_bucket_total{bucket="gt_10"} 1188
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1669
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1641
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 719655
telemt_user_connections_current{user="hello"} 3127
telemt_user_octets_from_client{user="hello"} 14161120540 (13.19 GB)
telemt_user_octets_to_client{user="hello"} 373332232304 (347.69 GB)
telemt_user_unique_ips_current{user="hello"} 913
telemt_user_unique_ips_recent_window{user="hello"} 420
```