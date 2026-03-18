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

# Server Metrics 2026-03-18 04:50:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 122727.8 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1403235
telemt_connections_bad_total 10543
telemt_handshake_timeouts_total 34317
telemt_upstream_connect_attempt_total 26923
telemt_upstream_connect_success_total 26409
telemt_upstream_connect_fail_total 514
telemt_upstream_connect_attempts_per_request{bucket="1"} 26923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12672
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 514
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 35151
telemt_me_reconnect_success_total 18003
telemt_me_reader_eof_total 19529
telemt_me_idle_close_by_peer_total 19528
telemt_me_route_drop_no_conn_total 598148
telemt_me_route_drop_channel_closed_total 164
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1290685
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8012
telemt_desync_full_logged_total 2395
telemt_desync_suppressed_total 5617
telemt_desync_frames_bucket_total{bucket="1_2"} 2109
telemt_desync_frames_bucket_total{bucket="3_10"} 3072
telemt_desync_frames_bucket_total{bucket="gt_10"} 2831
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 18805
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17981
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 802
telemt_user_connections_total{user="hello"} 1284914
telemt_user_connections_current{user="hello"} 889
telemt_user_octets_from_client{user="hello"} 28503321007 (26.55 GB)
telemt_user_octets_to_client{user="hello"} 454882585531 (423.64 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 122979.6 (34h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1523153
telemt_connections_bad_total 73835
telemt_handshake_timeouts_total 50414
telemt_upstream_connect_attempt_total 470346
telemt_upstream_connect_success_total 468723
telemt_upstream_connect_fail_total 1623
telemt_upstream_connect_attempts_per_request{bucket="1"} 470346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1623
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126412
telemt_me_reconnect_success_total 19684
telemt_me_reader_eof_total 21955
telemt_me_idle_close_by_peer_total 21942
telemt_me_route_drop_no_conn_total 396568
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 882788
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3958
telemt_desync_full_logged_total 1377
telemt_desync_suppressed_total 2581
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 1620
telemt_desync_frames_bucket_total{bucket="gt_10"} 1558
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 21305
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19666
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1621
telemt_user_connections_total{user="hello"} 1325105
telemt_user_connections_current{user="hello"} 1373
telemt_user_octets_from_client{user="hello"} 17937722981 (16.71 GB)
telemt_user_octets_to_client{user="hello"} 493647562470 (459.75 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 122755.6 (34h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 961000
telemt_connections_bad_total 67861
telemt_handshake_timeouts_total 27742
telemt_upstream_connect_attempt_total 28297
telemt_upstream_connect_success_total 28136
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 28297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15130
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42675
telemt_me_reconnect_success_total 21975
telemt_me_reader_eof_total 23886
telemt_me_idle_close_by_peer_total 23879
telemt_me_route_drop_no_conn_total 360710
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 791565
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2562
telemt_desync_full_logged_total 844
telemt_desync_suppressed_total 1718
telemt_desync_frames_bucket_total{bucket="1_2"} 710
telemt_desync_frames_bucket_total{bucket="3_10"} 985
telemt_desync_frames_bucket_total{bucket="gt_10"} 867
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 22913
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21963
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 938
telemt_user_connections_total{user="hello"} 789669
telemt_user_connections_current{user="hello"} 955
telemt_user_octets_from_client{user="hello"} 45188868784 (42.09 GB)
telemt_user_octets_to_client{user="hello"} 368635961600 (343.32 GB)
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 122814.9 (34h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1416359
telemt_connections_bad_total 69437
telemt_handshake_timeouts_total 24470
telemt_upstream_connect_attempt_total 91305
telemt_upstream_connect_success_total 88866
telemt_upstream_connect_fail_total 2439
telemt_upstream_connect_attempts_per_request{bucket="1"} 91305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2439
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38395
telemt_me_reconnect_success_total 17984
telemt_me_reader_eof_total 19738
telemt_me_idle_close_by_peer_total 19735
telemt_me_route_drop_no_conn_total 574393
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1152977
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4344
telemt_desync_full_logged_total 1427
telemt_desync_suppressed_total 2917
telemt_desync_frames_bucket_total{bucket="1_2"} 1058
telemt_desync_frames_bucket_total{bucket="3_10"} 1827
telemt_desync_frames_bucket_total{bucket="gt_10"} 1459
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 18951
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17964
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 967
telemt_user_connections_total{user="hello"} 1216277
telemt_user_connections_current{user="hello"} 1173
telemt_user_octets_from_client{user="hello"} 18983750690 (17.68 GB)
telemt_user_octets_to_client{user="hello"} 589933218358 (549.42 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 122786.8 (34h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 981407
telemt_connections_bad_total 102789
telemt_handshake_timeouts_total 9337
telemt_upstream_connect_attempt_total 48242
telemt_upstream_connect_success_total 47578
telemt_upstream_connect_fail_total 664
telemt_upstream_connect_attempts_per_request{bucket="1"} 48242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 664
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59948
telemt_me_reconnect_success_total 24982
telemt_me_reader_eof_total 27028
telemt_me_idle_close_by_peer_total 27025
telemt_me_route_drop_no_conn_total 313994
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 799823
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3564
telemt_desync_full_logged_total 1081
telemt_desync_suppressed_total 2483
telemt_desync_frames_bucket_total{bucket="1_2"} 1063
telemt_desync_frames_bucket_total{bucket="3_10"} 1391
telemt_desync_frames_bucket_total{bucket="gt_10"} 1110
telemt_pool_swap_total 64
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26461
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24974
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1479
telemt_user_connections_total{user="hello"} 816301
telemt_user_connections_current{user="hello"} 1080
telemt_user_octets_from_client{user="hello"} 15615666100 (14.54 GB)
telemt_user_octets_to_client{user="hello"} 414159102428 (385.72 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 122947.8 (34h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1183266
telemt_connections_bad_total 127240
telemt_handshake_timeouts_total 10376
telemt_upstream_connect_attempt_total 24489
telemt_upstream_connect_success_total 24348
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 24489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12544
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29534
telemt_me_reconnect_success_total 18239
telemt_me_reader_eof_total 19768
telemt_me_idle_close_by_peer_total 19766
telemt_me_route_drop_no_conn_total 815398
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1164120
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2178
telemt_desync_full_logged_total 765
telemt_desync_suppressed_total 1413
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 874
telemt_pool_swap_total 111
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18876
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18225
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 972808
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 15448729932 (14.39 GB)
telemt_user_octets_to_client{user="hello"} 428780358132 (399.33 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 70715.0 (19h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518523
telemt_connections_bad_total 52956
telemt_handshake_timeouts_total 12967
telemt_upstream_connect_attempt_total 25091
telemt_upstream_connect_success_total 24835
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 25091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32779
telemt_me_reconnect_success_total 21168
telemt_me_reader_eof_total 22372
telemt_me_idle_close_by_peer_total 22372
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 126119
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 371924
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 538
telemt_desync_suppressed_total 1100
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 635
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21756
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21125
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 371676
telemt_user_connections_current{user="hello"} 800
telemt_user_octets_from_client{user="hello"} 23665110881 (22.04 GB)
telemt_user_octets_to_client{user="hello"} 298737107490 (278.22 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 115
```