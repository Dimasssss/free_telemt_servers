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

# Server Metrics 2026-03-18 03:59:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 119673.2 (33h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1365947
telemt_connections_bad_total 10476
telemt_handshake_timeouts_total 33569
telemt_upstream_connect_attempt_total 26377
telemt_upstream_connect_success_total 25867
telemt_upstream_connect_fail_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 26377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 510
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34781
telemt_me_reconnect_success_total 17636
telemt_me_reader_eof_total 19135
telemt_me_idle_close_by_peer_total 19134
telemt_me_route_drop_no_conn_total 585526
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1258350
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7915
telemt_desync_full_logged_total 2360
telemt_desync_suppressed_total 5555
telemt_desync_frames_bucket_total{bucket="1_2"} 2091
telemt_desync_frames_bucket_total{bucket="3_10"} 3028
telemt_desync_frames_bucket_total{bucket="gt_10"} 2796
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 18435
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17614
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 799
telemt_user_connections_total{user="hello"} 1252560
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 25357038207 (23.62 GB)
telemt_user_octets_to_client{user="hello"} 443393818999 (412.94 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 119923.9 (33h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1460764
telemt_connections_bad_total 70297
telemt_handshake_timeouts_total 48111
telemt_upstream_connect_attempt_total 469651
telemt_upstream_connect_success_total 468039
telemt_upstream_connect_fail_total 1612
telemt_upstream_connect_attempts_per_request{bucket="1"} 469651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34122
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1612
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 125857
telemt_me_reconnect_success_total 19132
telemt_me_reader_eof_total 21374
telemt_me_idle_close_by_peer_total 21361
telemt_me_route_drop_no_conn_total 378103
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 827393
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3776
telemt_desync_full_logged_total 1301
telemt_desync_suppressed_total 2475
telemt_desync_frames_bucket_total{bucket="1_2"} 735
telemt_desync_frames_bucket_total{bucket="3_10"} 1556
telemt_desync_frames_bucket_total{bucket="gt_10"} 1485
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 20750
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19114
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1618
telemt_user_connections_total{user="hello"} 1269713
telemt_user_connections_current{user="hello"} 943
telemt_user_octets_from_client{user="hello"} 17123367309 (15.95 GB)
telemt_user_octets_to_client{user="hello"} 459406123514 (427.86 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 119699.9 (33h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 891931
telemt_connections_bad_total 62497
telemt_handshake_timeouts_total 25617
telemt_upstream_connect_attempt_total 27717
telemt_upstream_connect_success_total 27558
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 27717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42271
telemt_me_reconnect_success_total 21575
telemt_me_reader_eof_total 23457
telemt_me_idle_close_by_peer_total 23450
telemt_me_route_drop_no_conn_total 346545
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 750951
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2353
telemt_desync_full_logged_total 766
telemt_desync_suppressed_total 1587
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 905
telemt_desync_frames_bucket_total{bucket="gt_10"} 773
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 22508
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21563
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 933
telemt_user_connections_total{user="hello"} 749065
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 44678767172 (41.61 GB)
telemt_user_octets_to_client{user="hello"} 341746768292 (318.28 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 119759.4 (33h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1367397
telemt_connections_bad_total 65190
telemt_handshake_timeouts_total 24074
telemt_upstream_connect_attempt_total 90680
telemt_upstream_connect_success_total 88247
telemt_upstream_connect_fail_total 2432
telemt_upstream_connect_attempts_per_request{bucket="1"} 90679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2432
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 37928
telemt_me_reconnect_success_total 17520
telemt_me_reader_eof_total 19248
telemt_me_idle_close_by_peer_total 19245
telemt_me_route_drop_no_conn_total 557001
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1110574
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4136
telemt_desync_full_logged_total 1364
telemt_desync_suppressed_total 2772
telemt_desync_frames_bucket_total{bucket="1_2"} 1018
telemt_desync_frames_bucket_total{bucket="3_10"} 1730
telemt_desync_frames_bucket_total{bucket="gt_10"} 1388
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 18482
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17500
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 962
telemt_user_connections_total{user="hello"} 1173939
telemt_user_connections_current{user="hello"} 859
telemt_user_octets_from_client{user="hello"} 18346435942 (17.09 GB)
telemt_user_octets_to_client{user="hello"} 565157092930 (526.34 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 119731.2 (33h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 928713
telemt_connections_bad_total 101892
telemt_handshake_timeouts_total 7641
telemt_upstream_connect_attempt_total 47435
telemt_upstream_connect_success_total 46788
telemt_upstream_connect_fail_total 647
telemt_upstream_connect_attempts_per_request{bucket="1"} 47435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 647
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59326
telemt_me_reconnect_success_total 24362
telemt_me_reader_eof_total 26385
telemt_me_idle_close_by_peer_total 26382
telemt_me_route_drop_no_conn_total 296497
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 754535
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3381
telemt_desync_full_logged_total 1021
telemt_desync_suppressed_total 2360
telemt_desync_frames_bucket_total{bucket="1_2"} 1036
telemt_desync_frames_bucket_total{bucket="3_10"} 1339
telemt_desync_frames_bucket_total{bucket="gt_10"} 1006
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25834
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24354
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1472
telemt_user_connections_total{user="hello"} 771049
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 14730234376 (13.72 GB)
telemt_user_octets_to_client{user="hello"} 386026913224 (359.52 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 119892.1 (33h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1160690
telemt_connections_bad_total 126862
telemt_handshake_timeouts_total 10293
telemt_upstream_connect_attempt_total 23903
telemt_upstream_connect_success_total 23764
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 23903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29079
telemt_me_reconnect_success_total 17785
telemt_me_reader_eof_total 19284
telemt_me_idle_close_by_peer_total 19282
telemt_me_route_drop_no_conn_total 801920
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1139011
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2136
telemt_desync_full_logged_total 748
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 470
telemt_desync_frames_bucket_total{bucket="3_10"} 810
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 108
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18413
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17771
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 951691
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 15188450516 (14.15 GB)
telemt_user_octets_to_client{user="hello"} 417951615976 (389.25 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 67659.3 (18h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474048
telemt_connections_bad_total 47321
telemt_handshake_timeouts_total 12173
telemt_upstream_connect_attempt_total 24434
telemt_upstream_connect_success_total 24186
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 24434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32259
telemt_me_reconnect_success_total 20648
telemt_me_reader_eof_total 21826
telemt_me_idle_close_by_peer_total 21826
telemt_me_seq_mismatch_total 32
telemt_me_route_drop_no_conn_total 114938
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341885
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1508
telemt_desync_full_logged_total 490
telemt_desync_suppressed_total 1018
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 678
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21231
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20606
telemt_me_writer_restored_fallback_total 42
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 341678
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 23260125017 (21.66 GB)
telemt_user_octets_to_client{user="hello"} 281283031530 (261.97 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 76
```