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

# Server Metrics 2026-03-19 11:10:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 48101.5 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1130927
telemt_connections_bad_total 96066
telemt_connections_current 1626
telemt_connections_me_current 1626
telemt_handshake_timeouts_total 39693
telemt_upstream_connect_attempt_total 9261
telemt_upstream_connect_success_total 9099
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 9261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 8541
telemt_me_reconnect_success_total 6672
telemt_me_reader_eof_total 7057
telemt_me_idle_close_by_peer_total 7054
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 465494
telemt_me_route_drop_channel_closed_total 172
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 880615
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4908
telemt_desync_full_logged_total 1501
telemt_desync_suppressed_total 3407
telemt_desync_frames_bucket_total{bucket="1_2"} 1610
telemt_desync_frames_bucket_total{bucket="3_10"} 1792
telemt_desync_frames_bucket_total{bucket="gt_10"} 1506
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6826
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 6651
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 874555
telemt_user_connections_current{user="hello"} 1626
telemt_user_octets_from_client{user="hello"} 13129668244 (12.23 GB)
telemt_user_octets_to_client{user="hello"} 268746182808 (250.29 GB)
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 48106.2 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2997199
telemt_connections_bad_total 173346
telemt_connections_current 3922
telemt_connections_me_current 3922
telemt_handshake_timeouts_total 57580
telemt_upstream_connect_attempt_total 9173
telemt_upstream_connect_success_total 9006
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 9173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 12626
telemt_me_reconnect_success_total 6554
telemt_me_reader_eof_total 7060
telemt_me_idle_close_by_peer_total 7059
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 2057208
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2530270
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10274
telemt_desync_full_logged_total 3436
telemt_desync_suppressed_total 6838
telemt_desync_frames_bucket_total{bucket="1_2"} 1982
telemt_desync_frames_bucket_total{bucket="3_10"} 4052
telemt_desync_frames_bucket_total{bucket="gt_10"} 4240
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6860
telemt_me_refill_failed_total 189
telemt_me_writer_restored_same_endpoint_total 6532
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 306
telemt_user_connections_total{user="hello"} 2529891
telemt_user_connections_current{user="hello"} 3922
telemt_user_octets_from_client{user="hello"} 34946322756 (32.55 GB)
telemt_user_octets_to_client{user="hello"} 799137086640 (744.25 GB)
telemt_user_unique_ips_current{user="hello"} 1349
telemt_user_unique_ips_recent_window{user="hello"} 558
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 48103.3 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2384139
telemt_connections_bad_total 273607
telemt_connections_current 3269
telemt_connections_me_current 3269
telemt_handshake_timeouts_total 50640
telemt_upstream_connect_attempt_total 8674
telemt_upstream_connect_success_total 8674
telemt_upstream_connect_attempts_per_request{bucket="1"} 8674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 7414
telemt_me_reconnect_success_total 6220
telemt_me_reader_eof_total 6601
telemt_me_idle_close_by_peer_total 6601
telemt_me_route_drop_no_conn_total 1503426
telemt_me_route_drop_channel_closed_total 76
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1881587
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7912
telemt_desync_full_logged_total 2518
telemt_desync_suppressed_total 5394
telemt_desync_frames_bucket_total{bucket="1_2"} 1766
telemt_desync_frames_bucket_total{bucket="3_10"} 2925
telemt_desync_frames_bucket_total{bucket="gt_10"} 3221
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6364
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6204
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 1879482
telemt_user_connections_current{user="hello"} 3269
telemt_user_octets_from_client{user="hello"} 26485927328 (24.67 GB)
telemt_user_octets_to_client{user="hello"} 799533766764 (744.62 GB)
telemt_user_unique_ips_current{user="hello"} 1096
telemt_user_unique_ips_recent_window{user="hello"} 540
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 48156.0 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2367729
telemt_connections_bad_total 127393
telemt_connections_current 3182
telemt_connections_me_current 3182
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 61730
telemt_upstream_connect_attempt_total 16971
telemt_upstream_connect_success_total 16804
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 16971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 10525
telemt_me_reconnect_success_total 6189
telemt_me_reader_eof_total 6594
telemt_me_idle_close_by_peer_total 6593
telemt_me_route_drop_no_conn_total 1206509
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1796241
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6560
telemt_desync_full_logged_total 2215
telemt_desync_suppressed_total 4345
telemt_desync_frames_bucket_total{bucket="1_2"} 1386
telemt_desync_frames_bucket_total{bucket="3_10"} 2540
telemt_desync_frames_bucket_total{bucket="gt_10"} 2634
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6652
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6165
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 463
telemt_user_connections_total{user="hello"} 1802411
telemt_user_connections_current{user="hello"} 3182
telemt_user_octets_from_client{user="hello"} 20428584016 (19.03 GB)
telemt_user_octets_to_client{user="hello"} 518806994834 (483.18 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1060
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 48099.5 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2844414
telemt_connections_bad_total 634988
telemt_connections_current 3600
telemt_connections_me_current 3600
telemt_handshake_timeouts_total 55722
telemt_upstream_connect_attempt_total 8550
telemt_upstream_connect_success_total 8490
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 7260
telemt_me_reconnect_success_total 6056
telemt_me_reader_eof_total 6441
telemt_me_idle_close_by_peer_total 6440
telemt_me_route_drop_no_conn_total 1058576
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1873833
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8218
telemt_desync_full_logged_total 2555
telemt_desync_suppressed_total 5663
telemt_desync_frames_bucket_total{bucket="1_2"} 1582
telemt_desync_frames_bucket_total{bucket="3_10"} 3553
telemt_desync_frames_bucket_total{bucket="gt_10"} 3083
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6183
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6032
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 1872901
telemt_user_connections_current{user="hello"} 3600
telemt_user_octets_from_client{user="hello"} 32970436932 (30.71 GB)
telemt_user_octets_to_client{user="hello"} 760215761620 (708.01 GB)
telemt_user_unique_ips_current{user="hello"} 1222
telemt_user_unique_ips_recent_window{user="hello"} 541
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 48111.8 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491278
telemt_connections_bad_total 18583
telemt_connections_current 924
telemt_connections_me_current 924
telemt_handshake_timeouts_total 3846
telemt_upstream_connect_attempt_total 12057
telemt_upstream_connect_success_total 11750
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 12057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16898
telemt_me_reconnect_success_total 9310
telemt_me_reader_eof_total 9924
telemt_me_idle_close_by_peer_total 9924
telemt_me_route_drop_no_conn_total 255436
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 444678
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 928
telemt_desync_full_logged_total 319
telemt_desync_suppressed_total 609
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 358
telemt_desync_frames_bucket_total{bucket="gt_10"} 372
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9631
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9279
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 321
telemt_user_connections_total{user="hello"} 444624
telemt_user_connections_current{user="hello"} 924
telemt_user_octets_from_client{user="hello"} 7237129016 (6.74 GB)
telemt_user_octets_to_client{user="hello"} 166567030296 (155.13 GB)
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 48101.9 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2000452
telemt_connections_bad_total 170946
telemt_connections_current 3091
telemt_connections_me_current 3091
telemt_handshake_timeouts_total 71839
telemt_upstream_connect_attempt_total 9700
telemt_upstream_connect_success_total 9699
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8613
telemt_me_reconnect_success_total 7246
telemt_me_reader_eof_total 7670
telemt_me_idle_close_by_peer_total 7669
telemt_me_route_drop_no_conn_total 1028075
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1662903
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9016
telemt_desync_full_logged_total 2902
telemt_desync_suppressed_total 6114
telemt_desync_frames_bucket_total{bucket="1_2"} 1729
telemt_desync_frames_bucket_total{bucket="3_10"} 3438
telemt_desync_frames_bucket_total{bucket="gt_10"} 3849
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7380
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7231
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 1661618
telemt_user_connections_current{user="hello"} 3091
telemt_user_octets_from_client{user="hello"} 22031892088 (20.52 GB)
telemt_user_octets_to_client{user="hello"} 738453120584 (687.74 GB)
telemt_user_unique_ips_current{user="hello"} 976
telemt_user_unique_ips_recent_window{user="hello"} 379
```