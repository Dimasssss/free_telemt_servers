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

# Server Metrics 2026-03-17 21:07:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 94909.5 (26h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1170371
telemt_connections_bad_total 8633
telemt_handshake_timeouts_total 30825
telemt_upstream_connect_attempt_total 21606
telemt_upstream_connect_success_total 21116
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 21606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31195
telemt_me_reconnect_success_total 14065
telemt_me_reader_eof_total 15291
telemt_me_idle_close_by_peer_total 15290
telemt_me_route_drop_no_conn_total 522999
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1072951
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7144
telemt_desync_full_logged_total 2051
telemt_desync_suppressed_total 5093
telemt_desync_frames_bucket_total{bucket="1_2"} 1917
telemt_desync_frames_bucket_total{bucket="3_10"} 2710
telemt_desync_frames_bucket_total{bucket="gt_10"} 2517
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 14809
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14043
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 744
telemt_user_connections_total{user="hello"} 1067187
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 19085353799 (17.77 GB)
telemt_user_octets_to_client{user="hello"} 378153745211 (352.18 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 95160.3 (26h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1211165
telemt_connections_bad_total 59470
telemt_handshake_timeouts_total 43674
telemt_upstream_connect_attempt_total 457105
telemt_upstream_connect_success_total 456220
telemt_upstream_connect_fail_total 885
telemt_upstream_connect_attempts_per_request{bucket="1"} 457105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43290
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 885
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57618
telemt_me_reconnect_success_total 14465
telemt_me_reader_eof_total 16427
telemt_me_idle_close_by_peer_total 16427
telemt_me_route_drop_no_conn_total 307156
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 608102
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2673
telemt_desync_full_logged_total 852
telemt_desync_suppressed_total 1821
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 1121
telemt_desync_frames_bucket_total{bucket="gt_10"} 1040
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 15995
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14449
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1530
telemt_user_connections_total{user="hello"} 1044529
telemt_user_connections_current{user="hello"} 1293
telemt_user_octets_from_client{user="hello"} 14498746302 (13.50 GB)
telemt_user_octets_to_client{user="hello"} 347666645522 (323.79 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 94936.4 (26h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 678725
telemt_connections_bad_total 39195
telemt_handshake_timeouts_total 22525
telemt_upstream_connect_attempt_total 22759
telemt_upstream_connect_success_total 22628
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 22759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38501
telemt_me_reconnect_success_total 17826
telemt_me_reader_eof_total 19456
telemt_me_idle_close_by_peer_total 19449
telemt_me_route_drop_no_conn_total 287913
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 584496
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1865
telemt_desync_full_logged_total 564
telemt_desync_suppressed_total 1301
telemt_desync_frames_bucket_total{bucket="1_2"} 522
telemt_desync_frames_bucket_total{bucket="3_10"} 732
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 18714
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17814
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 888
telemt_user_connections_total{user="hello"} 582767
telemt_user_connections_current{user="hello"} 914
telemt_user_octets_from_client{user="hello"} 28706075848 (26.73 GB)
telemt_user_octets_to_client{user="hello"} 245090151388 (228.26 GB)
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 94995.6 (26h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1180144
telemt_connections_bad_total 36373
telemt_handshake_timeouts_total 21217
telemt_upstream_connect_attempt_total 82335
telemt_upstream_connect_success_total 81919
telemt_upstream_connect_fail_total 416
telemt_upstream_connect_attempts_per_request{bucket="1"} 82335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 342
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 416
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 34104
telemt_me_reconnect_success_total 13789
telemt_me_reader_eof_total 15193
telemt_me_idle_close_by_peer_total 15192
telemt_me_route_drop_no_conn_total 491023
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 963584
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3310
telemt_desync_full_logged_total 1055
telemt_desync_suppressed_total 2255
telemt_desync_frames_bucket_total{bucket="1_2"} 813
telemt_desync_frames_bucket_total{bucket="3_10"} 1400
telemt_desync_frames_bucket_total{bucket="gt_10"} 1097
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14679
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13780
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 890
telemt_user_connections_total{user="hello"} 1026098
telemt_user_connections_current{user="hello"} 1126
telemt_user_octets_from_client{user="hello"} 15341535083 (14.29 GB)
telemt_user_octets_to_client{user="hello"} 429783719473 (400.27 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 94967.7 (26h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 733472
telemt_connections_bad_total 90730
telemt_handshake_timeouts_total 6232
telemt_upstream_connect_attempt_total 41147
telemt_upstream_connect_success_total 40600
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 41147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14067
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 393
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51841
telemt_me_reconnect_success_total 19356
telemt_me_reader_eof_total 21083
telemt_me_idle_close_by_peer_total 21081
telemt_me_route_drop_no_conn_total 229617
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580589
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2687
telemt_desync_full_logged_total 778
telemt_desync_suppressed_total 1909
telemt_desync_frames_bucket_total{bucket="1_2"} 882
telemt_desync_frames_bucket_total{bucket="3_10"} 1075
telemt_desync_frames_bucket_total{bucket="gt_10"} 730
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20701
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19348
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1345
telemt_user_connections_total{user="hello"} 597203
telemt_user_connections_current{user="hello"} 1190
telemt_user_octets_from_client{user="hello"} 11650879404 (10.85 GB)
telemt_user_octets_to_client{user="hello"} 291306726212 (271.30 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 95128.8 (26h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 979316
telemt_connections_bad_total 70422
telemt_handshake_timeouts_total 9281
telemt_upstream_connect_attempt_total 18809
telemt_upstream_connect_success_total 18699
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 18809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9671
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25221
telemt_me_reconnect_success_total 13944
telemt_me_reader_eof_total 15148
telemt_me_idle_close_by_peer_total 15146
telemt_me_route_drop_no_conn_total 680736
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 976514
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1994
telemt_desync_full_logged_total 696
telemt_desync_suppressed_total 1298
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 755
telemt_desync_frames_bucket_total{bucket="gt_10"} 786
telemt_pool_swap_total 80
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14526
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13930
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 839547
telemt_user_connections_current{user="hello"} 588
telemt_user_octets_from_client{user="hello"} 12996816684 (12.10 GB)
telemt_user_octets_to_client{user="hello"} 361678132920 (336.84 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 42895.8 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312353
telemt_connections_bad_total 40866
telemt_handshake_timeouts_total 9377
telemt_upstream_connect_attempt_total 17458
telemt_upstream_connect_success_total 17297
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 17458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26573
telemt_me_reconnect_success_total 14980
telemt_me_reader_eof_total 15830
telemt_me_idle_close_by_peer_total 15830
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 77076
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239611
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 752
telemt_desync_full_logged_total 213
telemt_desync_suppressed_total 539
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15519
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14952
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 239554
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 20821511549 (19.39 GB)
telemt_user_octets_to_client{user="hello"} 200860685614 (187.07 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 79
```