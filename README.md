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

# Server Metrics 2026-03-17 20:21:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 92153.4 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1142370
telemt_connections_bad_total 8386
telemt_handshake_timeouts_total 30393
telemt_upstream_connect_attempt_total 21135
telemt_upstream_connect_success_total 20646
telemt_upstream_connect_fail_total 489
telemt_upstream_connect_attempts_per_request{bucket="1"} 21135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 489
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30854
telemt_me_reconnect_success_total 13725
telemt_me_reader_eof_total 14927
telemt_me_idle_close_by_peer_total 14926
telemt_me_route_drop_no_conn_total 512006
telemt_me_route_drop_channel_closed_total 153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1046787
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6980
telemt_desync_full_logged_total 2000
telemt_desync_suppressed_total 4980
telemt_desync_frames_bucket_total{bucket="1_2"} 1879
telemt_desync_frames_bucket_total{bucket="3_10"} 2649
telemt_desync_frames_bucket_total{bucket="gt_10"} 2452
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 14462
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13703
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 1041026
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 16065161971 (14.96 GB)
telemt_user_octets_to_client{user="hello"} 364016445819 (339.02 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 92404.7 (25h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1155721
telemt_connections_bad_total 58749
telemt_handshake_timeouts_total 41271
telemt_upstream_connect_attempt_total 456655
telemt_upstream_connect_success_total 455778
telemt_upstream_connect_fail_total 877
telemt_upstream_connect_attempts_per_request{bucket="1"} 456655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 877
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57307
telemt_me_reconnect_success_total 14155
telemt_me_reader_eof_total 16095
telemt_me_idle_close_by_peer_total 16095
telemt_me_route_drop_no_conn_total 289413
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 557434
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2393
telemt_desync_full_logged_total 771
telemt_desync_suppressed_total 1622
telemt_desync_frames_bucket_total{bucket="1_2"} 466
telemt_desync_frames_bucket_total{bucket="3_10"} 1008
telemt_desync_frames_bucket_total{bucket="gt_10"} 919
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 15679
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14139
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1524
telemt_user_connections_total{user="hello"} 993866
telemt_user_connections_current{user="hello"} 1540
telemt_user_octets_from_client{user="hello"} 13773290082 (12.83 GB)
telemt_user_octets_to_client{user="hello"} 318052832082 (296.21 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 92180.9 (25h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 631308
telemt_connections_bad_total 34129
telemt_handshake_timeouts_total 22252
telemt_upstream_connect_attempt_total 22308
telemt_upstream_connect_success_total 22179
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 22308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38182
telemt_me_reconnect_success_total 17508
telemt_me_reader_eof_total 19118
telemt_me_idle_close_by_peer_total 19111
telemt_me_route_drop_no_conn_total 273623
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545159
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1652
telemt_desync_full_logged_total 492
telemt_desync_suppressed_total 1160
telemt_desync_frames_bucket_total{bucket="1_2"} 472
telemt_desync_frames_bucket_total{bucket="3_10"} 653
telemt_desync_frames_bucket_total{bucket="gt_10"} 527
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 18393
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17496
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 885
telemt_user_connections_total{user="hello"} 543434
telemt_user_connections_current{user="hello"} 1178
telemt_user_octets_from_client{user="hello"} 28141923292 (26.21 GB)
telemt_user_octets_to_client{user="hello"} 222317786208 (207.05 GB)
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 92240.1 (25h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1132649
telemt_connections_bad_total 32535
telemt_handshake_timeouts_total 21046
telemt_upstream_connect_attempt_total 81871
telemt_upstream_connect_success_total 81463
telemt_upstream_connect_fail_total 408
telemt_upstream_connect_attempts_per_request{bucket="1"} 81871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11622
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 408
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33775
telemt_me_reconnect_success_total 13466
telemt_me_reader_eof_total 14850
telemt_me_idle_close_by_peer_total 14849
telemt_me_route_drop_no_conn_total 473501
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 921761
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3135
telemt_desync_full_logged_total 1001
telemt_desync_suppressed_total 2134
telemt_desync_frames_bucket_total{bucket="1_2"} 760
telemt_desync_frames_bucket_total{bucket="3_10"} 1342
telemt_desync_frames_bucket_total{bucket="gt_10"} 1033
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14350
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13457
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 884
telemt_user_connections_total{user="hello"} 984283
telemt_user_connections_current{user="hello"} 1375
telemt_user_octets_from_client{user="hello"} 14499462575 (13.50 GB)
telemt_user_octets_to_client{user="hello"} 394058284525 (367.00 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 92212.2 (25h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 686761
telemt_connections_bad_total 84433
telemt_handshake_timeouts_total 5768
telemt_upstream_connect_attempt_total 40586
telemt_upstream_connect_success_total 40045
telemt_upstream_connect_fail_total 541
telemt_upstream_connect_attempts_per_request{bucket="1"} 40586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 391
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 541
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51416
telemt_me_reconnect_success_total 18931
telemt_me_reader_eof_total 20634
telemt_me_idle_close_by_peer_total 20632
telemt_me_route_drop_no_conn_total 213999
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 542735
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2444
telemt_desync_full_logged_total 689
telemt_desync_suppressed_total 1755
telemt_desync_frames_bucket_total{bucket="1_2"} 844
telemt_desync_frames_bucket_total{bucket="3_10"} 979
telemt_desync_frames_bucket_total{bucket="gt_10"} 621
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20270
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 18923
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1339
telemt_user_connections_total{user="hello"} 559362
telemt_user_connections_current{user="hello"} 1264
telemt_user_octets_from_client{user="hello"} 11086955440 (10.33 GB)
telemt_user_octets_to_client{user="hello"} 261497051224 (243.54 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 92373.0 (25h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 952632
telemt_connections_bad_total 68160
telemt_handshake_timeouts_total 9087
telemt_upstream_connect_attempt_total 18291
telemt_upstream_connect_success_total 18187
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 18291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9429
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24838
telemt_me_reconnect_success_total 13563
telemt_me_reader_eof_total 14739
telemt_me_idle_close_by_peer_total 14737
telemt_me_route_drop_no_conn_total 670412
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 956473
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1904
telemt_desync_full_logged_total 666
telemt_desync_suppressed_total 1238
telemt_desync_frames_bucket_total{bucket="1_2"} 444
telemt_desync_frames_bucket_total{bucket="3_10"} 728
telemt_desync_frames_bucket_total{bucket="gt_10"} 732
telemt_pool_swap_total 77
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14142
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 819508
telemt_user_connections_current{user="hello"} 705
telemt_user_octets_from_client{user="hello"} 12621910280 (11.76 GB)
telemt_user_octets_to_client{user="hello"} 353612787788 (329.33 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 40140.1 (11h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279876
telemt_connections_bad_total 37253
telemt_handshake_timeouts_total 7624
telemt_upstream_connect_attempt_total 16929
telemt_upstream_connect_success_total 16773
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 16929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26178
telemt_me_reconnect_success_total 14589
telemt_me_reader_eof_total 15417
telemt_me_idle_close_by_peer_total 15417
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 68198
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215312
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 642
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 469
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 18
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15125
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14561
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 536
telemt_user_connections_total{user="hello"} 215259
telemt_user_connections_current{user="hello"} 769
telemt_user_octets_from_client{user="hello"} 20123674969 (18.74 GB)
telemt_user_octets_to_client{user="hello"} 177083697006 (164.92 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 79
```