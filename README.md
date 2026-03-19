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

# Server Metrics 2026-03-19 09:32:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 42270.0 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 874933
telemt_connections_bad_total 80976
telemt_connections_current 1636
telemt_connections_me_current 1636
telemt_handshake_timeouts_total 33751
telemt_upstream_connect_attempt_total 7999
telemt_upstream_connect_success_total 7860
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 7999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4053
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6915
telemt_me_reconnect_success_total 5759
telemt_me_reader_eof_total 6106
telemt_me_idle_close_by_peer_total 6105
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 297811
telemt_me_route_drop_channel_closed_total 115
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 681602
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4202
telemt_desync_full_logged_total 1265
telemt_desync_suppressed_total 2937
telemt_desync_frames_bucket_total{bucket="1_2"} 1405
telemt_desync_frames_bucket_total{bucket="3_10"} 1538
telemt_desync_frames_bucket_total{bucket="gt_10"} 1259
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5864
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5740
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 676026
telemt_user_connections_current{user="hello"} 1636
telemt_user_octets_from_client{user="hello"} 10705191512 (9.97 GB)
telemt_user_octets_to_client{user="hello"} 219257399384 (204.20 GB)
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 42274.1 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2166127
telemt_connections_bad_total 122369
telemt_connections_current 4298
telemt_connections_me_current 4298
telemt_handshake_timeouts_total 47863
telemt_upstream_connect_attempt_total 8021
telemt_upstream_connect_success_total 7872
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 8021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8096
telemt_me_reconnect_success_total 5750
telemt_me_reader_eof_total 6121
telemt_me_idle_close_by_peer_total 6121
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 959912
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1799133
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8094
telemt_desync_full_logged_total 2711
telemt_desync_suppressed_total 5383
telemt_desync_frames_bucket_total{bucket="1_2"} 1482
telemt_desync_frames_bucket_total{bucket="3_10"} 3143
telemt_desync_frames_bucket_total{bucket="gt_10"} 3469
telemt_pool_swap_total 32
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5924
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 5728
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 1798894
telemt_user_connections_current{user="hello"} 4298
telemt_user_octets_from_client{user="hello"} 29112201316 (27.11 GB)
telemt_user_octets_to_client{user="hello"} 665649120752 (619.93 GB)
telemt_user_unique_ips_current{user="hello"} 1464
telemt_user_unique_ips_recent_window{user="hello"} 641
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 42271.5 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1830703
telemt_connections_bad_total 218220
telemt_connections_current 3125
telemt_connections_me_current 3125
telemt_handshake_timeouts_total 44981
telemt_upstream_connect_attempt_total 7510
telemt_upstream_connect_success_total 7510
telemt_upstream_connect_attempts_per_request{bucket="1"} 7510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5423
telemt_me_reconnect_success_total 5389
telemt_me_reader_eof_total 5704
telemt_me_idle_close_by_peer_total 5704
telemt_me_route_drop_no_conn_total 857142
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1425661
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6465
telemt_desync_full_logged_total 2024
telemt_desync_suppressed_total 4441
telemt_desync_frames_bucket_total{bucket="1_2"} 1456
telemt_desync_frames_bucket_total{bucket="3_10"} 2353
telemt_desync_frames_bucket_total{bucket="gt_10"} 2656
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 5484
telemt_me_writer_restored_same_endpoint_total 5373
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 1424305
telemt_user_connections_current{user="hello"} 3125
telemt_user_octets_from_client{user="hello"} 22089842760 (20.57 GB)
telemt_user_octets_to_client{user="hello"} 658151863128 (612.95 GB)
telemt_user_unique_ips_current{user="hello"} 1083
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 42324.6 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1904147
telemt_connections_bad_total 101890
telemt_connections_current 3028
telemt_connections_me_current 3028
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 48284
telemt_upstream_connect_attempt_total 15707
telemt_upstream_connect_success_total 15594
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 15707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 7724
telemt_me_reconnect_success_total 5313
telemt_me_reader_eof_total 5651
telemt_me_idle_close_by_peer_total 5650
telemt_me_route_drop_no_conn_total 957561
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1421431
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5146
telemt_desync_full_logged_total 1749
telemt_desync_suppressed_total 3397
telemt_desync_frames_bucket_total{bucket="1_2"} 1060
telemt_desync_frames_bucket_total{bucket="3_10"} 2002
telemt_desync_frames_bucket_total{bucket="gt_10"} 2084
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5584
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5289
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 1428111
telemt_user_connections_current{user="hello"} 3028
telemt_user_octets_from_client{user="hello"} 16938593360 (15.78 GB)
telemt_user_octets_to_client{user="hello"} 415272517210 (386.75 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1004
telemt_user_unique_ips_recent_window{user="hello"} 462
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 42267.8 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2211133
telemt_connections_bad_total 536564
telemt_connections_current 3420
telemt_connections_me_current 3420
telemt_handshake_timeouts_total 47207
telemt_upstream_connect_attempt_total 7275
telemt_upstream_connect_success_total 7224
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 7275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 5157
telemt_me_reconnect_success_total 5115
telemt_me_reader_eof_total 5423
telemt_me_idle_close_by_peer_total 5423
telemt_me_route_drop_no_conn_total 631504
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1410310
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6551
telemt_desync_full_logged_total 2039
telemt_desync_suppressed_total 4512
telemt_desync_frames_bucket_total{bucket="1_2"} 1315
telemt_desync_frames_bucket_total{bucket="3_10"} 2883
telemt_desync_frames_bucket_total{bucket="gt_10"} 2353
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5190
telemt_me_writer_restored_same_endpoint_total 5091
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1409499
telemt_user_connections_current{user="hello"} 3420
telemt_user_octets_from_client{user="hello"} 26420387672 (24.61 GB)
telemt_user_octets_to_client{user="hello"} 624321524712 (581.44 GB)
telemt_user_unique_ips_current{user="hello"} 1187
telemt_user_unique_ips_recent_window{user="hello"} 523
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 42280.2 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392379
telemt_connections_bad_total 17699
telemt_connections_current 884
telemt_connections_me_current 884
telemt_handshake_timeouts_total 3207
telemt_upstream_connect_attempt_total 10726
telemt_upstream_connect_success_total 10455
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 10726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 13726
telemt_me_reconnect_success_total 8342
telemt_me_reader_eof_total 8842
telemt_me_idle_close_by_peer_total 8842
telemt_me_route_drop_no_conn_total 201075
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 351559
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 551
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 193
telemt_me_writer_removed_unexpected_total 8576
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8312
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 351521
telemt_user_connections_current{user="hello"} 884
telemt_user_octets_from_client{user="hello"} 5201459624 (4.84 GB)
telemt_user_octets_to_client{user="hello"} 141142722676 (131.45 GB)
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 42270.3 (11h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1492806
telemt_connections_bad_total 130394
telemt_connections_current 3199
telemt_connections_me_current 3199
telemt_handshake_timeouts_total 65349
telemt_upstream_connect_attempt_total 8542
telemt_upstream_connect_success_total 8541
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 7769
telemt_me_reconnect_success_total 6420
telemt_me_reader_eof_total 6802
telemt_me_idle_close_by_peer_total 6801
telemt_me_route_drop_no_conn_total 585494
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1241361
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7060
telemt_desync_full_logged_total 2317
telemt_desync_suppressed_total 4743
telemt_desync_frames_bucket_total{bucket="1_2"} 1345
telemt_desync_frames_bucket_total{bucket="3_10"} 2652
telemt_desync_frames_bucket_total{bucket="gt_10"} 3063
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6537
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6405
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 1240244
telemt_user_connections_current{user="hello"} 3199
telemt_user_octets_from_client{user="hello"} 17048507904 (15.88 GB)
telemt_user_octets_to_client{user="hello"} 605217316532 (563.65 GB)
telemt_user_unique_ips_current{user="hello"} 1043
telemt_user_unique_ips_recent_window{user="hello"} 448
```