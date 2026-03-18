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

# Server Metrics 2026-03-18 02:07:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 112952.2 (31h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1309081
telemt_connections_bad_total 9735
telemt_handshake_timeouts_total 32788
telemt_upstream_connect_attempt_total 25157
telemt_upstream_connect_success_total 24653
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 25157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33868
telemt_me_reconnect_success_total 16729
telemt_me_reader_eof_total 18161
telemt_me_idle_close_by_peer_total 18160
telemt_me_route_drop_no_conn_total 567751
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1205203
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7672
telemt_desync_full_logged_total 2269
telemt_desync_suppressed_total 5403
telemt_desync_frames_bucket_total{bucket="1_2"} 2056
telemt_desync_frames_bucket_total{bucket="3_10"} 2912
telemt_desync_frames_bucket_total{bucket="gt_10"} 2704
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 17512
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16707
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 783
telemt_user_connections_total{user="hello"} 1199415
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 23242719415 (21.65 GB)
telemt_user_octets_to_client{user="hello"} 423662448495 (394.57 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 113203.4 (31h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1382589
telemt_connections_bad_total 64215
telemt_handshake_timeouts_total 46950
telemt_upstream_connect_attempt_total 467914
telemt_upstream_connect_success_total 466340
telemt_upstream_connect_fail_total 1574
telemt_upstream_connect_attempts_per_request{bucket="1"} 467914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1574
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123225
telemt_me_reconnect_success_total 17785
telemt_me_reader_eof_total 19943
telemt_me_idle_close_by_peer_total 19930
telemt_me_route_drop_no_conn_total 356126
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 759026
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3544
telemt_desync_full_logged_total 1200
telemt_desync_suppressed_total 2344
telemt_desync_frames_bucket_total{bucket="1_2"} 694
telemt_desync_frames_bucket_total{bucket="3_10"} 1476
telemt_desync_frames_bucket_total{bucket="gt_10"} 1374
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 19350
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17767
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1565
telemt_user_connections_total{user="hello"} 1201377
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 16261389933 (15.14 GB)
telemt_user_octets_to_client{user="hello"} 421313795170 (392.38 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 262
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 112979.4 (31h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 828722
telemt_connections_bad_total 57572
telemt_handshake_timeouts_total 24457
telemt_upstream_connect_attempt_total 26432
telemt_upstream_connect_success_total 26280
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41294
telemt_me_reconnect_success_total 20603
telemt_me_reader_eof_total 22423
telemt_me_idle_close_by_peer_total 22416
telemt_me_route_drop_no_conn_total 330338
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 700730
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2217
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1498
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 860
telemt_desync_frames_bucket_total{bucket="gt_10"} 725
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 21526
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20591
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 923
telemt_user_connections_total{user="hello"} 698848
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 43025206536 (40.07 GB)
telemt_user_octets_to_client{user="hello"} 309892396352 (288.61 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 113039.0 (31h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1311681
telemt_connections_bad_total 58052
telemt_handshake_timeouts_total 22067
telemt_upstream_connect_attempt_total 89223
telemt_upstream_connect_success_total 86812
telemt_upstream_connect_fail_total 2411
telemt_upstream_connect_attempts_per_request{bucket="1"} 89223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2411
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 36806
telemt_me_reconnect_success_total 16411
telemt_me_reader_eof_total 18083
telemt_me_idle_close_by_peer_total 18081
telemt_me_route_drop_no_conn_total 539889
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1065789
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3961
telemt_desync_full_logged_total 1314
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1664
telemt_desync_frames_bucket_total{bucket="gt_10"} 1329
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 17357
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16400
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 946
telemt_user_connections_total{user="hello"} 1129128
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 17681042214 (16.47 GB)
telemt_user_octets_to_client{user="hello"} 531931714458 (495.40 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 113010.8 (31h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 868957
telemt_connections_bad_total 100308
telemt_handshake_timeouts_total 6873
telemt_upstream_connect_attempt_total 45991
telemt_upstream_connect_success_total 45363
telemt_upstream_connect_fail_total 628
telemt_upstream_connect_attempts_per_request{bucket="1"} 45991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 628
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58206
telemt_me_reconnect_success_total 23244
telemt_me_reader_eof_total 25204
telemt_me_idle_close_by_peer_total 25201
telemt_me_route_drop_no_conn_total 277400
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 702387
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3224
telemt_desync_full_logged_total 964
telemt_desync_suppressed_total 2260
telemt_desync_frames_bucket_total{bucket="1_2"} 1008
telemt_desync_frames_bucket_total{bucket="3_10"} 1288
telemt_desync_frames_bucket_total{bucket="gt_10"} 928
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24708
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23236
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1464
telemt_user_connections_total{user="hello"} 718948
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 13812516552 (12.86 GB)
telemt_user_octets_to_client{user="hello"} 356043693920 (331.59 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 113171.7 (31h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1117377
telemt_connections_bad_total 118331
telemt_handshake_timeouts_total 9827
telemt_upstream_connect_attempt_total 22520
telemt_upstream_connect_success_total 22392
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 22520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11545
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28051
telemt_me_reconnect_success_total 16763
telemt_me_reader_eof_total 18178
telemt_me_idle_close_by_peer_total 18176
telemt_me_route_drop_no_conn_total 768761
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1091851
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 100
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17381
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16749
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 918502
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 14872711192 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 399463462092 (372.03 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 60939.0 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421827
telemt_connections_bad_total 44719
telemt_handshake_timeouts_total 11108
telemt_upstream_connect_attempt_total 22575
telemt_upstream_connect_success_total 22358
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 22575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30775
telemt_me_reconnect_success_total 19168
telemt_me_reader_eof_total 20259
telemt_me_idle_close_by_peer_total 20259
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 104406
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305834
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1334
telemt_desync_full_logged_total 415
telemt_desync_suppressed_total 919
telemt_desync_frames_bucket_total{bucket="1_2"} 225
telemt_desync_frames_bucket_total{bucket="3_10"} 594
telemt_desync_frames_bucket_total{bucket="gt_10"} 515
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19744
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19131
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 576
telemt_user_connections_total{user="hello"} 305770
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 22562513349 (21.01 GB)
telemt_user_octets_to_client{user="hello"} 258877925538 (241.10 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 40
```