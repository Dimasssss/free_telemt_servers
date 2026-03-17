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

# Server Metrics 2026-03-17 23:50:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 104703.8 (29h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1243357
telemt_connections_bad_total 9216
telemt_handshake_timeouts_total 32319
telemt_upstream_connect_attempt_total 23542
telemt_upstream_connect_success_total 23046
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 23542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32652
telemt_me_reconnect_success_total 15517
telemt_me_reader_eof_total 16857
telemt_me_idle_close_by_peer_total 16856
telemt_me_route_drop_no_conn_total 550309
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1142124
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7481
telemt_desync_full_logged_total 2184
telemt_desync_suppressed_total 5297
telemt_desync_frames_bucket_total{bucket="1_2"} 1999
telemt_desync_frames_bucket_total{bucket="3_10"} 2837
telemt_desync_frames_bucket_total{bucket="gt_10"} 2645
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 16280
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15495
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 1136345
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 22608119675 (21.06 GB)
telemt_user_octets_to_client{user="hello"} 409684072467 (381.55 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 104955.0 (29h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1317362
telemt_connections_bad_total 61257
telemt_handshake_timeouts_total 45531
telemt_upstream_connect_attempt_total 459161
telemt_upstream_connect_success_total 458244
telemt_upstream_connect_fail_total 917
telemt_upstream_connect_attempts_per_request{bucket="1"} 459161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 383464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31484
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 917
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 59168
telemt_me_reconnect_success_total 16010
telemt_me_reader_eof_total 18059
telemt_me_idle_close_by_peer_total 18059
telemt_me_route_drop_no_conn_total 342800
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 707288
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3238
telemt_desync_full_logged_total 1063
telemt_desync_suppressed_total 2175
telemt_desync_frames_bucket_total{bucket="1_2"} 631
telemt_desync_frames_bucket_total{bucket="3_10"} 1328
telemt_desync_frames_bucket_total{bucket="gt_10"} 1279
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 17556
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 15994
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1546
telemt_user_connections_total{user="hello"} 1143713
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 15678989138 (14.60 GB)
telemt_user_octets_to_client{user="hello"} 392367652358 (365.42 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 104731.1 (29h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 778106
telemt_connections_bad_total 49567
telemt_handshake_timeouts_total 23761
telemt_upstream_connect_attempt_total 24661
telemt_upstream_connect_success_total 24517
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 24660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 39916
telemt_me_reconnect_success_total 19234
telemt_me_reader_eof_total 20964
telemt_me_idle_close_by_peer_total 20957
telemt_me_route_drop_no_conn_total 316785
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 661539
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2135
telemt_desync_full_logged_total 695
telemt_desync_suppressed_total 1440
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 20144
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19222
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 910
telemt_user_connections_total{user="hello"} 659766
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 32000686704 (29.80 GB)
telemt_user_octets_to_client{user="hello"} 291935302384 (271.89 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 104790.5 (29h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1264352
telemt_connections_bad_total 49944
telemt_handshake_timeouts_total 21670
telemt_upstream_connect_attempt_total 84274
telemt_upstream_connect_success_total 83835
telemt_upstream_connect_fail_total 439
telemt_upstream_connect_attempts_per_request{bucket="1"} 84274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 439
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35553
telemt_me_reconnect_success_total 15225
telemt_me_reader_eof_total 16762
telemt_me_idle_close_by_peer_total 16760
telemt_me_route_drop_no_conn_total 520053
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1031453
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3887
telemt_desync_full_logged_total 1283
telemt_desync_suppressed_total 2604
telemt_desync_frames_bucket_total{bucket="1_2"} 950
telemt_desync_frames_bucket_total{bucket="3_10"} 1634
telemt_desync_frames_bucket_total{bucket="gt_10"} 1303
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 16142
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15216
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 917
telemt_user_connections_total{user="hello"} 1093936
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 17221092147 (16.04 GB)
telemt_user_octets_to_client{user="hello"} 502753982709 (468.23 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 104762.5 (29h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 821827
telemt_connections_bad_total 96644
telemt_handshake_timeouts_total 6654
telemt_upstream_connect_attempt_total 43567
telemt_upstream_connect_success_total 42969
telemt_upstream_connect_fail_total 598
telemt_upstream_connect_attempts_per_request{bucket="1"} 43567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 408
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 598
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56201
telemt_me_reconnect_success_total 21246
telemt_me_reader_eof_total 23112
telemt_me_idle_close_by_peer_total 23110
telemt_me_route_drop_no_conn_total 260996
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 660690
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3134
telemt_desync_full_logged_total 925
telemt_desync_suppressed_total 2209
telemt_desync_frames_bucket_total{bucket="1_2"} 995
telemt_desync_frames_bucket_total{bucket="3_10"} 1251
telemt_desync_frames_bucket_total{bucket="gt_10"} 888
telemt_pool_swap_total 52
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22691
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21238
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1445
telemt_user_connections_total{user="hello"} 677298
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 13420169704 (12.50 GB)
telemt_user_octets_to_client{user="hello"} 337893114396 (314.69 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 104923.4 (29h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1057232
telemt_connections_bad_total 96312
telemt_handshake_timeouts_total 9556
telemt_upstream_connect_attempt_total 20800
telemt_upstream_connect_success_total 20685
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 20800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10688
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 26732
telemt_me_reconnect_success_total 15451
telemt_me_reader_eof_total 16772
telemt_me_idle_close_by_peer_total 16770
telemt_me_route_drop_no_conn_total 707447
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1023116
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
telemt_pool_swap_total 91
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16054
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15437
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 884138
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 14274779996 (13.29 GB)
telemt_user_octets_to_client{user="hello"} 373854104336 (348.18 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 52690.5 (14h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379864
telemt_connections_bad_total 44665
telemt_handshake_timeouts_total 10761
telemt_upstream_connect_attempt_total 19959
telemt_upstream_connect_success_total 19776
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 19959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 28578
telemt_me_reconnect_success_total 16980
telemt_me_reader_eof_total 17956
telemt_me_idle_close_by_peer_total 17956
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 95546
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284070
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1041
telemt_desync_full_logged_total 330
telemt_desync_suppressed_total 711
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 441
telemt_desync_frames_bucket_total{bucket="gt_10"} 386
telemt_pool_swap_total 32
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17539
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 16951
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 559
telemt_user_connections_total{user="hello"} 284011
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 22027559181 (20.51 GB)
telemt_user_octets_to_client{user="hello"} 233157086622 (217.14 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 25
```