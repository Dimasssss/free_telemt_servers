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

# Server Metrics 2026-03-17 16:36:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 78696.9 (21h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 915963
telemt_connections_bad_total 6479
telemt_handshake_timeouts_total 25578
telemt_upstream_connect_attempt_total 18758
telemt_upstream_connect_success_total 18286
telemt_upstream_connect_fail_total 472
telemt_upstream_connect_attempts_per_request{bucket="1"} 18758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 472
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 29142
telemt_me_reconnect_success_total 12028
telemt_me_reader_eof_total 13134
telemt_me_idle_close_by_peer_total 13133
telemt_me_route_drop_no_conn_total 425726
telemt_me_route_drop_channel_closed_total 110
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 842174
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5631
telemt_desync_full_logged_total 1572
telemt_desync_suppressed_total 4059
telemt_desync_frames_bucket_total{bucket="1_2"} 1601
telemt_desync_frames_bucket_total{bucket="3_10"} 2184
telemt_desync_frames_bucket_total{bucket="gt_10"} 1846
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 12728
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12006
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 700
telemt_user_connections_total{user="hello"} 836466
telemt_user_connections_current{user="hello"} 1303
telemt_user_octets_from_client{user="hello"} 13062931775 (12.17 GB)
telemt_user_octets_to_client{user="hello"} 278239660815 (259.13 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 78949.2 (21h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 648502
telemt_connections_bad_total 38856
telemt_handshake_timeouts_total 29126
telemt_upstream_connect_attempt_total 186005
telemt_upstream_connect_success_total 185380
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 185994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 153147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 45684
telemt_me_reconnect_success_total 13545
telemt_me_reader_eof_total 15101
telemt_me_idle_close_by_peer_total 15101
telemt_me_route_drop_no_conn_total 204263
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383948
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1502
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 1031
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 652
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14712
telemt_me_refill_failed_total 1000
telemt_me_writer_restored_same_endpoint_total 13529
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1167
telemt_user_connections_total{user="hello"} 551729
telemt_user_connections_current{user="hello"} 1946
telemt_user_octets_from_client{user="hello"} 6412302406 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 149711811200 (139.43 GB)
telemt_user_msgs_from_client{user="hello"} 2516431
telemt_user_msgs_to_client{user="hello"} 9901679
telemt_user_unique_ips_current{user="hello"} 388
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 78783.3 (21h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 747801
telemt_connections_bad_total 11628
telemt_handshake_timeouts_total 15112
telemt_upstream_connect_attempt_total 79885
telemt_upstream_connect_success_total 79494
telemt_upstream_connect_fail_total 391
telemt_upstream_connect_attempts_per_request{bucket="1"} 79885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10677
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 391
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 32448
telemt_me_reconnect_success_total 12155
telemt_me_reader_eof_total 13436
telemt_me_idle_close_by_peer_total 13435
telemt_me_route_drop_no_conn_total 275350
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 586292
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1977
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 1315
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 887
telemt_desync_frames_bucket_total{bucket="gt_10"} 606
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12998
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12146
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 843
telemt_user_connections_total{user="hello"} 649434
telemt_user_connections_current{user="hello"} 1929
telemt_user_octets_from_client{user="hello"} 7949634043 (7.40 GB)
telemt_user_octets_to_client{user="hello"} 196940678309 (183.42 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 78755.3 (21h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348927
telemt_connections_bad_total 63546
telemt_handshake_timeouts_total 3939
telemt_upstream_connect_attempt_total 38096
telemt_upstream_connect_success_total 37604
telemt_upstream_connect_fail_total 492
telemt_upstream_connect_attempts_per_request{bucket="1"} 38096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12547
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 492
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 48439
telemt_me_reconnect_success_total 17149
telemt_me_reader_eof_total 18718
telemt_me_idle_close_by_peer_total 18716
telemt_me_route_drop_no_conn_total 94076
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250244
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1203
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 939
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 472
telemt_desync_frames_bucket_total{bucket="gt_10"} 153
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18408
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 17141
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1259
telemt_user_connections_total{user="hello"} 266927
telemt_user_connections_current{user="hello"} 1495
telemt_user_octets_from_client{user="hello"} 3408980848 (3.17 GB)
telemt_user_octets_to_client{user="hello"} 102843839348 (95.78 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 78917.5 (21h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 784495
telemt_connections_bad_total 60207
telemt_handshake_timeouts_total 7327
telemt_upstream_connect_attempt_total 15925
telemt_upstream_connect_success_total 15838
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 15925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 23136
telemt_me_reconnect_success_total 11871
telemt_me_reader_eof_total 12927
telemt_me_idle_close_by_peer_total 12925
telemt_me_route_drop_no_conn_total 589976
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 808998
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1320
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 857
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 498
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12418
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 11857
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 547
telemt_user_connections_total{user="hello"} 677326
telemt_user_connections_current{user="hello"} 914
telemt_user_octets_from_client{user="hello"} 9763817468 (9.09 GB)
telemt_user_octets_to_client{user="hello"} 303572980988 (282.72 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 26683.5 (7h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36963
telemt_connections_bad_total 744
telemt_handshake_timeouts_total 378
telemt_upstream_connect_attempt_total 13839
telemt_upstream_connect_success_total 13722
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 13839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23774
telemt_me_reconnect_success_total 12201
telemt_me_reader_eof_total 12917
telemt_me_idle_close_by_peer_total 12917
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 13008
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34065
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 12702
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12181
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 501
telemt_user_connections_total{user="hello"} 34097
telemt_user_connections_current{user="hello"} 966
telemt_user_octets_from_client{user="hello"} 1595450253 (1.49 GB)
telemt_user_octets_to_client{user="hello"} 42683320794 (39.75 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 108
```