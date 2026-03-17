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

# Server Metrics 2026-03-17 16:26:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 78084.8 (21h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901967
telemt_connections_bad_total 6359
telemt_handshake_timeouts_total 25510
telemt_upstream_connect_attempt_total 18624
telemt_upstream_connect_success_total 18152
telemt_upstream_connect_fail_total 472
telemt_upstream_connect_attempts_per_request{bucket="1"} 18624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 472
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 29051
telemt_me_reconnect_success_total 11938
telemt_me_reader_eof_total 13029
telemt_me_idle_close_by_peer_total 13028
telemt_me_route_drop_no_conn_total 416309
telemt_me_route_drop_channel_closed_total 102
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 828800
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5576
telemt_desync_full_logged_total 1550
telemt_desync_suppressed_total 4026
telemt_desync_frames_bucket_total{bucket="1_2"} 1592
telemt_desync_frames_bucket_total{bucket="3_10"} 2165
telemt_desync_frames_bucket_total{bucket="gt_10"} 1819
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12637
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 11916
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 699
telemt_user_connections_total{user="hello"} 823229
telemt_user_connections_current{user="hello"} 1374
telemt_user_octets_from_client{user="hello"} 12898040823 (12.01 GB)
telemt_user_octets_to_client{user="hello"} 272904345175 (254.16 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 78337.0 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 614000
telemt_connections_bad_total 32498
telemt_handshake_timeouts_total 28969
telemt_upstream_connect_attempt_total 165073
telemt_upstream_connect_success_total 164476
telemt_upstream_connect_fail_total 595
telemt_upstream_connect_attempts_per_request{bucket="1"} 165071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 135617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12846
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 595
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 44299
telemt_me_reconnect_success_total 13536
telemt_me_reader_eof_total 15049
telemt_me_idle_close_by_peer_total 15049
telemt_me_route_drop_no_conn_total 198614
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378044
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1494
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 1025
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 507
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14660
telemt_me_refill_failed_total 957
telemt_me_writer_restored_same_endpoint_total 13520
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1124
telemt_user_connections_total{user="hello"} 524970
telemt_user_connections_current{user="hello"} 1658
telemt_user_octets_from_client{user="hello"} 5810800486 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 144067280455 (134.17 GB)
telemt_user_msgs_from_client{user="hello"} 2175147
telemt_user_msgs_to_client{user="hello"} 8409793
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 78112.9 (21h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308067
telemt_connections_bad_total 9098
telemt_handshake_timeouts_total 19414
telemt_upstream_connect_attempt_total 19982
telemt_upstream_connect_success_total 19876
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 19982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10796
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 35172
telemt_me_reconnect_success_total 15908
telemt_me_reader_eof_total 17370
telemt_me_idle_close_by_peer_total 17367
telemt_me_route_drop_no_conn_total 151719
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264116
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 835
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 591
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 374
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16719
telemt_me_refill_failed_total 599
telemt_me_writer_restored_same_endpoint_total 15897
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 811
telemt_user_connections_total{user="hello"} 263664
telemt_user_connections_current{user="hello"} 981
telemt_user_octets_from_client{user="hello"} 20465539920 (19.06 GB)
telemt_user_octets_to_client{user="hello"} 64295784808 (59.88 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 78171.5 (21h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727756
telemt_connections_bad_total 11405
telemt_handshake_timeouts_total 14990
telemt_upstream_connect_attempt_total 79761
telemt_upstream_connect_success_total 79372
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 79761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 32370
telemt_me_reconnect_success_total 12077
telemt_me_reader_eof_total 13352
telemt_me_idle_close_by_peer_total 13351
telemt_me_route_drop_no_conn_total 268460
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 567587
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1936
telemt_desync_full_logged_total 651
telemt_desync_suppressed_total 1285
telemt_desync_frames_bucket_total{bucket="1_2"} 481
telemt_desync_frames_bucket_total{bucket="3_10"} 871
telemt_desync_frames_bucket_total{bucket="gt_10"} 584
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12920
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12068
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 843
telemt_user_connections_total{user="hello"} 630735
telemt_user_connections_current{user="hello"} 1401
telemt_user_octets_from_client{user="hello"} 7450018403 (6.94 GB)
telemt_user_octets_to_client{user="hello"} 188385765277 (175.45 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 78143.4 (21h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326912
telemt_connections_bad_total 60054
telemt_handshake_timeouts_total 3888
telemt_upstream_connect_attempt_total 31310
telemt_upstream_connect_success_total 30822
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 31310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 48382
telemt_me_reconnect_success_total 17094
telemt_me_reader_eof_total 18660
telemt_me_idle_close_by_peer_total 18658
telemt_me_route_drop_no_conn_total 91977
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239664
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1148
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 18352
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 17086
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1258
telemt_user_connections_total{user="hello"} 249664
telemt_user_connections_current{user="hello"} 1129
telemt_user_octets_from_client{user="hello"} 3077572057 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 91748901124 (85.45 GB)
telemt_user_msgs_from_client{user="hello"} 188170
telemt_user_msgs_to_client{user="hello"} 1203901
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 78304.7 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 774689
telemt_connections_bad_total 60195
telemt_handshake_timeouts_total 7277
telemt_upstream_connect_attempt_total 15766
telemt_upstream_connect_success_total 15681
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 15766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 22062
telemt_me_reconnect_success_total 11758
telemt_me_reader_eof_total 12781
telemt_me_idle_close_by_peer_total 12779
telemt_me_route_drop_no_conn_total 579404
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 796218
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1267
telemt_desync_full_logged_total 448
telemt_desync_suppressed_total 819
telemt_desync_frames_bucket_total{bucket="1_2"} 297
telemt_desync_frames_bucket_total{bucket="3_10"} 497
telemt_desync_frames_bucket_total{bucket="gt_10"} 473
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12270
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11744
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 668392
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 9657730624 (8.99 GB)
telemt_user_octets_to_client{user="hello"} 299862102344 (279.27 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 26071.5 (7h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25931
telemt_connections_bad_total 326
telemt_handshake_timeouts_total 351
telemt_upstream_connect_attempt_total 13707
telemt_upstream_connect_success_total 13590
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 13707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23685
telemt_me_reconnect_success_total 12113
telemt_me_reader_eof_total 12813
telemt_me_idle_close_by_peer_total 12813
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 10821
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24429
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 12611
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12093
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 24480
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 1396920665 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 31790035858 (29.61 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 51
```