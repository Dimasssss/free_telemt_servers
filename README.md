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

# Server Metrics 2026-03-18 01:27:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 110507.7 (30h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1287310
telemt_connections_bad_total 9620
telemt_handshake_timeouts_total 32517
telemt_upstream_connect_attempt_total 24671
telemt_upstream_connect_success_total 24170
telemt_upstream_connect_fail_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 24671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 501
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33518
telemt_me_reconnect_success_total 16380
telemt_me_reader_eof_total 17784
telemt_me_idle_close_by_peer_total 17783
telemt_me_route_drop_no_conn_total 562881
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1184511
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7597
telemt_desync_full_logged_total 2235
telemt_desync_suppressed_total 5362
telemt_desync_frames_bucket_total{bucket="1_2"} 2032
telemt_desync_frames_bucket_total{bucket="3_10"} 2882
telemt_desync_frames_bucket_total{bucket="gt_10"} 2683
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 17158
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16358
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 778
telemt_user_connections_total{user="hello"} 1178723
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 22878636015 (21.31 GB)
telemt_user_octets_to_client{user="hello"} 420160247647 (391.30 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 110759.2 (30h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1363999
telemt_connections_bad_total 64105
telemt_handshake_timeouts_total 46563
telemt_upstream_connect_attempt_total 467253
telemt_upstream_connect_success_total 465701
telemt_upstream_connect_fail_total 1552
telemt_upstream_connect_attempts_per_request{bucket="1"} 467253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1552
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122693
telemt_me_reconnect_success_total 17261
telemt_me_reader_eof_total 19405
telemt_me_idle_close_by_peer_total 19395
telemt_me_route_drop_no_conn_total 351679
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 741658
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3448
telemt_desync_full_logged_total 1159
telemt_desync_suppressed_total 2289
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 1426
telemt_desync_frames_bucket_total{bucket="gt_10"} 1347
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 18813
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17243
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1552
telemt_user_connections_total{user="hello"} 1184008
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 16092419125 (14.99 GB)
telemt_user_octets_to_client{user="hello"} 411569508602 (383.30 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 110535.2 (30h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 812309
telemt_connections_bad_total 54561
telemt_handshake_timeouts_total 24273
telemt_upstream_connect_attempt_total 25886
telemt_upstream_connect_success_total 25739
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 25886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11807
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13835
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40879
telemt_me_reconnect_success_total 20193
telemt_me_reader_eof_total 21984
telemt_me_idle_close_by_peer_total 21977
telemt_me_route_drop_no_conn_total 326013
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 689241
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2191
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1479
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 722
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 21112
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20181
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 919
telemt_user_connections_total{user="hello"} 687361
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 39962953212 (37.22 GB)
telemt_user_octets_to_client{user="hello"} 303665494444 (282.81 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 110594.7 (30h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1295674
telemt_connections_bad_total 55706
telemt_handshake_timeouts_total 21954
telemt_upstream_connect_attempt_total 88103
telemt_upstream_connect_success_total 85986
telemt_upstream_connect_fail_total 2027
telemt_upstream_connect_attempts_per_request{bucket="1"} 88013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2027
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 36409
telemt_me_reconnect_success_total 16035
telemt_me_reader_eof_total 17684
telemt_me_idle_close_by_peer_total 17682
telemt_me_route_drop_no_conn_total 532184
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1053428
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3954
telemt_desync_full_logged_total 1307
telemt_desync_suppressed_total 2647
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1660
telemt_desync_frames_bucket_total{bucket="gt_10"} 1328
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 16975
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16025
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 940
telemt_user_connections_total{user="hello"} 1116675
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 17525220085 (16.32 GB)
telemt_user_octets_to_client{user="hello"} 527597333612 (491.36 GB)
telemt_user_msgs_from_client{user="hello"} 740905
telemt_user_msgs_to_client{user="hello"} 5209962
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 110566.5 (30h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 854693
telemt_connections_bad_total 99790
telemt_handshake_timeouts_total 6842
telemt_upstream_connect_attempt_total 45430
telemt_upstream_connect_success_total 44807
telemt_upstream_connect_fail_total 623
telemt_upstream_connect_attempts_per_request{bucket="1"} 45430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 623
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57779
telemt_me_reconnect_success_total 22818
telemt_me_reader_eof_total 24739
telemt_me_idle_close_by_peer_total 24737
telemt_me_route_drop_no_conn_total 271829
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 689092
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3184
telemt_desync_full_logged_total 947
telemt_desync_suppressed_total 2237
telemt_desync_frames_bucket_total{bucket="1_2"} 1006
telemt_desync_frames_bucket_total{bucket="3_10"} 1274
telemt_desync_frames_bucket_total{bucket="gt_10"} 904
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24274
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22810
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1456
telemt_user_connections_total{user="hello"} 705698
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 13664110300 (12.73 GB)
telemt_user_octets_to_client{user="hello"} 351206687660 (327.09 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 110727.5 (30h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1100754
telemt_connections_bad_total 111795
telemt_handshake_timeouts_total 9676
telemt_upstream_connect_attempt_total 21993
telemt_upstream_connect_success_total 21872
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 21993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11286
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27654
telemt_me_reconnect_success_total 16369
telemt_me_reader_eof_total 17765
telemt_me_idle_close_by_peer_total 17763
telemt_me_route_drop_no_conn_total 752930
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1073918
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
telemt_pool_swap_total 97
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16984
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16355
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 615
telemt_user_connections_total{user="hello"} 908890
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 14746616736 (13.73 GB)
telemt_user_octets_to_client{user="hello"} 391801125216 (364.89 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 58494.7 (16h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409168
telemt_connections_bad_total 44705
telemt_handshake_timeouts_total 10935
telemt_upstream_connect_attempt_total 21823
telemt_upstream_connect_success_total 21624
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 21823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9939
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30168
telemt_me_reconnect_success_total 18566
telemt_me_reader_eof_total 19634
telemt_me_idle_close_by_peer_total 19634
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 101363
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297803
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1244
telemt_desync_full_logged_total 382
telemt_desync_suppressed_total 862
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 480
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19136
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18532
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 570
telemt_user_connections_total{user="hello"} 297739
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 22461312769 (20.92 GB)
telemt_user_octets_to_client{user="hello"} 249232531886 (232.12 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 20
```