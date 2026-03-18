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

# Server Metrics 2026-03-18 06:57:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 130362.2 (36h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1691993
telemt_connections_bad_total 11613
telemt_handshake_timeouts_total 36977
telemt_upstream_connect_attempt_total 28212
telemt_upstream_connect_success_total 27689
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 28212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 36083
telemt_me_reconnect_success_total 18926
telemt_me_reader_eof_total 20509
telemt_me_idle_close_by_peer_total 20508
telemt_me_route_drop_no_conn_total 642345
telemt_me_route_drop_channel_closed_total 181
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1408242
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8493
telemt_desync_full_logged_total 2567
telemt_desync_suppressed_total 5926
telemt_desync_frames_bucket_total{bucket="1_2"} 2200
telemt_desync_frames_bucket_total{bucket="3_10"} 3281
telemt_desync_frames_bucket_total{bucket="gt_10"} 3012
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19747
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18904
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 821
telemt_user_connections_total{user="hello"} 1402490
telemt_user_connections_current{user="hello"} 1091
telemt_user_octets_from_client{user="hello"} 32839493683 (30.58 GB)
telemt_user_octets_to_client{user="hello"} 502077694423 (467.60 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 130614.0 (36h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1786676
telemt_connections_bad_total 91084
telemt_handshake_timeouts_total 57409
telemt_upstream_connect_attempt_total 471840
telemt_upstream_connect_success_total 470199
telemt_upstream_connect_fail_total 1640
telemt_upstream_connect_attempts_per_request{bucket="1"} 471839
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1640
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 127505
telemt_me_reconnect_success_total 20770
telemt_me_reader_eof_total 23085
telemt_me_idle_close_by_peer_total 23072
telemt_me_route_drop_no_conn_total 482532
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1111361
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5106
telemt_desync_full_logged_total 1777
telemt_desync_suppressed_total 3329
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 2076
telemt_desync_frames_bucket_total{bucket="gt_10"} 2064
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22407
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20752
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1637
telemt_user_connections_total{user="hello"} 1553684
telemt_user_connections_current{user="hello"} 2273
telemt_user_octets_from_client{user="hello"} 23830068169 (22.19 GB)
telemt_user_octets_to_client{user="hello"} 609983550470 (568.09 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 746
telemt_user_unique_ips_recent_window{user="hello"} 325
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 130389.8 (36h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1282416
telemt_connections_bad_total 81884
telemt_handshake_timeouts_total 32009
telemt_upstream_connect_attempt_total 29441
telemt_upstream_connect_success_total 29276
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 29441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 43468
telemt_me_reconnect_success_total 22757
telemt_me_reader_eof_total 24724
telemt_me_idle_close_by_peer_total 24716
telemt_me_route_drop_no_conn_total 434560
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 955717
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3323
telemt_desync_full_logged_total 1074
telemt_desync_suppressed_total 2249
telemt_desync_frames_bucket_total{bucket="1_2"} 878
telemt_desync_frames_bucket_total{bucket="3_10"} 1282
telemt_desync_frames_bucket_total{bucket="gt_10"} 1163
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 23720
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22745
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 963
telemt_user_connections_total{user="hello"} 953774
telemt_user_connections_current{user="hello"} 1555
telemt_user_octets_from_client{user="hello"} 48444467128 (45.12 GB)
telemt_user_octets_to_client{user="hello"} 468635018776 (436.45 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 130449.1 (36h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1676964
telemt_connections_bad_total 84028
telemt_handshake_timeouts_total 29913
telemt_upstream_connect_attempt_total 92551
telemt_upstream_connect_success_total 90096
telemt_upstream_connect_fail_total 2455
telemt_upstream_connect_attempts_per_request{bucket="1"} 92551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2455
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 39281
telemt_me_reconnect_success_total 18856
telemt_me_reader_eof_total 20657
telemt_me_idle_close_by_peer_total 20654
telemt_me_route_drop_no_conn_total 674910
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1379220
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5379
telemt_desync_full_logged_total 1717
telemt_desync_suppressed_total 3662
telemt_desync_frames_bucket_total{bucket="1_2"} 1271
telemt_desync_frames_bucket_total{bucket="3_10"} 2202
telemt_desync_frames_bucket_total{bucket="gt_10"} 1906
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 19842
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18836
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 986
telemt_user_connections_total{user="hello"} 1442448
telemt_user_connections_current{user="hello"} 2320
telemt_user_octets_from_client{user="hello"} 23921892754 (22.28 GB)
telemt_user_octets_to_client{user="hello"} 687816566366 (640.58 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 642
telemt_user_unique_ips_recent_window{user="hello"} 296
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 130421.1 (36h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1205082
telemt_connections_bad_total 107442
telemt_handshake_timeouts_total 12961
telemt_upstream_connect_attempt_total 49610
telemt_upstream_connect_success_total 48928
telemt_upstream_connect_fail_total 682
telemt_upstream_connect_attempts_per_request{bucket="1"} 49610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 430
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 682
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 62134
telemt_me_reconnect_success_total 25976
telemt_me_reader_eof_total 28098
telemt_me_idle_close_by_peer_total 28095
telemt_me_route_drop_no_conn_total 389936
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 994435
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4286
telemt_desync_full_logged_total 1329
telemt_desync_suppressed_total 2957
telemt_desync_frames_bucket_total{bucket="1_2"} 1155
telemt_desync_frames_bucket_total{bucket="3_10"} 1651
telemt_desync_frames_bucket_total{bucket="gt_10"} 1480
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27507
telemt_me_refill_failed_total 1124
telemt_me_writer_restored_same_endpoint_total 25968
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1531
telemt_user_connections_total{user="hello"} 1010828
telemt_user_connections_current{user="hello"} 1894
telemt_user_octets_from_client{user="hello"} 19076589472 (17.77 GB)
telemt_user_octets_to_client{user="hello"} 509859834624 (474.84 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 595
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 130582.1 (36h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1270907
telemt_connections_bad_total 133574
telemt_handshake_timeouts_total 10845
telemt_upstream_connect_attempt_total 25918
telemt_upstream_connect_success_total 25762
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 25918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13229
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 30574
telemt_me_reconnect_success_total 19273
telemt_me_reader_eof_total 20861
telemt_me_idle_close_by_peer_total 20858
telemt_me_route_drop_no_conn_total 847434
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1240708
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2417
telemt_desync_full_logged_total 852
telemt_desync_suppressed_total 1565
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 927
telemt_desync_frames_bucket_total{bucket="gt_10"} 952
telemt_pool_swap_total 118
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19922
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19259
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 649
telemt_user_connections_total{user="hello"} 1049365
telemt_user_connections_current{user="hello"} 847
telemt_user_octets_from_client{user="hello"} 16447160312 (15.32 GB)
telemt_user_octets_to_client{user="hello"} 463759726652 (431.91 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 78349.4 (21h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 676552
telemt_connections_bad_total 58213
telemt_handshake_timeouts_total 14929
telemt_upstream_connect_attempt_total 26492
telemt_upstream_connect_success_total 26213
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 26492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 33797
telemt_me_reconnect_success_total 22177
telemt_me_reader_eof_total 23429
telemt_me_idle_close_by_peer_total 23429
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 192062
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 508555
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2166
telemt_desync_full_logged_total 743
telemt_desync_suppressed_total 1423
telemt_desync_frames_bucket_total{bucket="1_2"} 353
telemt_desync_frames_bucket_total{bucket="3_10"} 942
telemt_desync_frames_bucket_total{bucket="gt_10"} 871
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22779
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 22131
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 602
telemt_user_connections_total{user="hello"} 508269
telemt_user_connections_current{user="hello"} 1485
telemt_user_octets_from_client{user="hello"} 27857995161 (25.94 GB)
telemt_user_octets_to_client{user="hello"} 377206496270 (351.30 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 192
```