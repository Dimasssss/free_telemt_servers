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

# Server Metrics 2026-03-17 13:32:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 67652.7 (18h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672569
telemt_connections_bad_total 5307
telemt_handshake_timeouts_total 20334
telemt_upstream_connect_attempt_total 16720
telemt_upstream_connect_success_total 16267
telemt_upstream_connect_fail_total 453
telemt_upstream_connect_attempts_per_request{bucket="1"} 16720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 453
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 16339
telemt_me_reconnect_success_total 10575
telemt_me_reader_eof_total 11312
telemt_me_idle_close_by_peer_total 11311
telemt_me_route_drop_no_conn_total 227014
telemt_me_route_drop_channel_closed_total 69
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 608954
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4453
telemt_desync_full_logged_total 1230
telemt_desync_suppressed_total 3223
telemt_desync_frames_bucket_total{bucket="1_2"} 1273
telemt_desync_frames_bucket_total{bucket="3_10"} 1829
telemt_desync_frames_bucket_total{bucket="gt_10"} 1351
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10907
telemt_me_refill_failed_total 175
telemt_me_writer_restored_same_endpoint_total 10553
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 610844
telemt_user_connections_current{user="hello"} 979
telemt_user_octets_from_client{user="hello"} 9546700115 (8.89 GB)
telemt_user_octets_to_client{user="hello"} 216012158271 (201.18 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 67904.4 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411823
telemt_connections_bad_total 24377
telemt_handshake_timeouts_total 21094
telemt_upstream_connect_attempt_total 17939
telemt_upstream_connect_success_total 17657
telemt_upstream_connect_fail_total 282
telemt_upstream_connect_attempts_per_request{bucket="1"} 17939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 455
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 282
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 28975
telemt_me_reconnect_success_total 13265
telemt_me_reader_eof_total 14328
telemt_me_idle_close_by_peer_total 14328
telemt_me_route_drop_no_conn_total 175142
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344324
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1368
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 930
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 603
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13919
telemt_me_refill_failed_total 487
telemt_me_writer_restored_same_endpoint_total 13249
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 654
telemt_user_connections_total{user="hello"} 345231
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 3745800675 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 116299345335 (108.31 GB)
telemt_user_msgs_from_client{user="hello"} 2850
telemt_user_msgs_to_client{user="hello"} 6435
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 67680.4 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221242
telemt_connections_bad_total 7769
telemt_handshake_timeouts_total 16658
telemt_upstream_connect_attempt_total 17927
telemt_upstream_connect_success_total 17837
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 17927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 18351
telemt_me_reconnect_success_total 14389
telemt_me_reader_eof_total 15384
telemt_me_idle_close_by_peer_total 15384
telemt_me_route_drop_no_conn_total 79312
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185344
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 728
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14714
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 14378
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 325
telemt_user_connections_total{user="hello"} 185229
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 15263523108 (14.22 GB)
telemt_user_octets_to_client{user="hello"} 51476315332 (47.94 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 67739.6 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 506187
telemt_connections_bad_total 7939
telemt_handshake_timeouts_total 12717
telemt_upstream_connect_attempt_total 16240
telemt_upstream_connect_success_total 16093
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 16240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 17906
telemt_me_reconnect_success_total 11641
telemt_me_reader_eof_total 12499
telemt_me_idle_close_by_peer_total 12499
telemt_me_route_drop_no_conn_total 148450
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428916
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1535
telemt_desync_full_logged_total 530
telemt_desync_suppressed_total 1005
telemt_desync_frames_bucket_total{bucket="1_2"} 374
telemt_desync_frames_bucket_total{bucket="3_10"} 690
telemt_desync_frames_bucket_total{bucket="gt_10"} 471
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12041
telemt_me_refill_failed_total 191
telemt_me_writer_restored_same_endpoint_total 11632
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 429777
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 5452514794 (5.08 GB)
telemt_user_octets_to_client{user="hello"} 146227785055 (136.19 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 67711.5 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252315
telemt_connections_bad_total 56231
telemt_handshake_timeouts_total 3249
telemt_upstream_connect_attempt_total 19482
telemt_upstream_connect_success_total 19226
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 19482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 33420
telemt_me_reconnect_success_total 15692
telemt_me_reader_eof_total 16882
telemt_me_idle_close_by_peer_total 16882
telemt_me_route_drop_no_conn_total 66662
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183451
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1089
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 862
telemt_desync_frames_bucket_total{bucket="1_2"} 545
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16451
telemt_me_refill_failed_total 551
telemt_me_writer_restored_same_endpoint_total 15684
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 759
telemt_user_connections_total{user="hello"} 183555
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 2367895887 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 70748742294 (65.89 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 67873.3 (18h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 603257
telemt_connections_bad_total 53256
telemt_handshake_timeouts_total 5992
telemt_upstream_connect_attempt_total 13774
telemt_upstream_connect_success_total 13701
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 13774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6900
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 16608
telemt_me_reconnect_success_total 10298
telemt_me_reader_eof_total 11135
telemt_me_idle_close_by_peer_total 11135
telemt_me_route_drop_no_conn_total 407956
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 604666
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 838
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 322
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10653
telemt_me_refill_failed_total 195
telemt_me_writer_restored_same_endpoint_total 10284
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 355
telemt_user_connections_total{user="hello"} 512844
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 7533392756 (7.02 GB)
telemt_user_octets_to_client{user="hello"} 243467576504 (226.75 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 15639.7 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12130
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 8886
telemt_upstream_connect_success_total 8814
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 8886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 14462
telemt_me_reconnect_success_total 7849
telemt_me_reader_eof_total 8247
telemt_me_idle_close_by_peer_total 8247
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 4215
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11731
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 8130
telemt_me_refill_failed_total 205
telemt_me_writer_restored_same_endpoint_total 7835
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 11832
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 343334401 (327.43 MB)
telemt_user_octets_to_client{user="hello"} 21747157362 (20.25 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 8
```