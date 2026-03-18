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

# Server Metrics 2026-03-18 01:06:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 109286.0 (30h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1277857
telemt_connections_bad_total 9601
telemt_handshake_timeouts_total 32482
telemt_upstream_connect_attempt_total 24449
telemt_upstream_connect_success_total 23950
telemt_upstream_connect_fail_total 499
telemt_upstream_connect_attempts_per_request{bucket="1"} 24449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 499
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33341
telemt_me_reconnect_success_total 16204
telemt_me_reader_eof_total 17596
telemt_me_idle_close_by_peer_total 17595
telemt_me_route_drop_no_conn_total 560309
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1175325
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7570
telemt_desync_full_logged_total 2222
telemt_desync_suppressed_total 5348
telemt_desync_frames_bucket_total{bucket="1_2"} 2025
telemt_desync_frames_bucket_total{bucket="3_10"} 2872
telemt_desync_frames_bucket_total{bucket="gt_10"} 2673
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 16978
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16182
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 774
telemt_user_connections_total{user="hello"} 1169538
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 22811221167 (21.24 GB)
telemt_user_octets_to_client{user="hello"} 417907610595 (389.21 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 109536.2 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1354684
telemt_connections_bad_total 62802
telemt_handshake_timeouts_total 46358
telemt_upstream_connect_attempt_total 467006
telemt_upstream_connect_success_total 465457
telemt_upstream_connect_fail_total 1549
telemt_upstream_connect_attempts_per_request{bucket="1"} 467006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32715
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1549
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122509
telemt_me_reconnect_success_total 17079
telemt_me_reader_eof_total 19207
telemt_me_idle_close_by_peer_total 19197
telemt_me_route_drop_no_conn_total 349582
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 734290
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3418
telemt_desync_full_logged_total 1139
telemt_desync_suppressed_total 2279
telemt_desync_frames_bucket_total{bucket="1_2"} 670
telemt_desync_frames_bucket_total{bucket="3_10"} 1408
telemt_desync_frames_bucket_total{bucket="gt_10"} 1340
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 18626
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17061
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1547
telemt_user_connections_total{user="hello"} 1176639
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 15903997525 (14.81 GB)
telemt_user_octets_to_client{user="hello"} 403565387250 (375.85 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 109312.2 (30h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 804874
telemt_connections_bad_total 53618
telemt_handshake_timeouts_total 24208
telemt_upstream_connect_attempt_total 25658
telemt_upstream_connect_success_total 25512
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 25658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40695
telemt_me_reconnect_success_total 20010
telemt_me_reader_eof_total 21793
telemt_me_idle_close_by_peer_total 21786
telemt_me_route_drop_no_conn_total 323541
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 683058
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2187
telemt_desync_full_logged_total 709
telemt_desync_suppressed_total 1478
telemt_desync_frames_bucket_total{bucket="1_2"} 621
telemt_desync_frames_bucket_total{bucket="3_10"} 845
telemt_desync_frames_bucket_total{bucket="gt_10"} 721
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 20928
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19998
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 918
telemt_user_connections_total{user="hello"} 681192
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 36858336708 (34.33 GB)
telemt_user_octets_to_client{user="hello"} 300807885264 (280.15 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 109371.8 (30h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1289074
telemt_connections_bad_total 54543
telemt_handshake_timeouts_total 21893
telemt_upstream_connect_attempt_total 86761
telemt_upstream_connect_success_total 85338
telemt_upstream_connect_fail_total 1423
telemt_upstream_connect_attempts_per_request{bucket="1"} 86761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1423
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 36230
telemt_me_reconnect_success_total 15868
telemt_me_reader_eof_total 17504
telemt_me_idle_close_by_peer_total 17502
telemt_me_route_drop_no_conn_total 526583
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1048996
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
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 16801
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15858
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 933
telemt_user_connections_total{user="hello"} 1112115
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 17456930543 (16.26 GB)
telemt_user_octets_to_client{user="hello"} 526045560794 (489.92 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 109343.5 (30h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 847696
telemt_connections_bad_total 99488
telemt_handshake_timeouts_total 6790
telemt_upstream_connect_attempt_total 44980
telemt_upstream_connect_success_total 44362
telemt_upstream_connect_fail_total 618
telemt_upstream_connect_attempts_per_request{bucket="1"} 44980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 412
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 618
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57377
telemt_me_reconnect_success_total 22418
telemt_me_reader_eof_total 24334
telemt_me_idle_close_by_peer_total 24332
telemt_me_route_drop_no_conn_total 269496
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 682609
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3180
telemt_desync_full_logged_total 944
telemt_desync_suppressed_total 2236
telemt_desync_frames_bucket_total{bucket="1_2"} 1005
telemt_desync_frames_bucket_total{bucket="3_10"} 1273
telemt_desync_frames_bucket_total{bucket="gt_10"} 902
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23869
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 22410
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1451
telemt_user_connections_total{user="hello"} 699215
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 13624006416 (12.69 GB)
telemt_user_octets_to_client{user="hello"} 349373393976 (325.38 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 109504.5 (30h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1091976
telemt_connections_bad_total 108531
telemt_handshake_timeouts_total 9668
telemt_upstream_connect_attempt_total 21782
telemt_upstream_connect_success_total 21662
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 21782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27492
telemt_me_reconnect_success_total 16209
telemt_me_reader_eof_total 17592
telemt_me_idle_close_by_peer_total 17590
telemt_me_route_drop_no_conn_total 740043
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1059997
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
telemt_pool_swap_total 96
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16821
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16195
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 612
telemt_user_connections_total{user="hello"} 903672
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 14694120412 (13.68 GB)
telemt_user_octets_to_client{user="hello"} 386383894208 (359.85 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 57271.7 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401381
telemt_connections_bad_total 44690
telemt_handshake_timeouts_total 10898
telemt_upstream_connect_attempt_total 21490
telemt_upstream_connect_success_total 21294
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 21490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 29881
telemt_me_reconnect_success_total 18280
telemt_me_reader_eof_total 19337
telemt_me_idle_close_by_peer_total 19337
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 100334
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294863
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1171
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 808
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 514
telemt_desync_frames_bucket_total{bucket="gt_10"} 440
telemt_pool_swap_total 36
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18848
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 18249
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 294800
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 22290878185 (20.76 GB)
telemt_user_octets_to_client{user="hello"} 244279445162 (227.50 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 42
```