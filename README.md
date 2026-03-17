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

# Server Metrics 2026-03-17 15:56:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 76246.3 (21h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 852481
telemt_connections_bad_total 6341
telemt_handshake_timeouts_total 24780
telemt_upstream_connect_attempt_total 18183
telemt_upstream_connect_success_total 17712
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 18183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 26301
telemt_me_reconnect_success_total 11589
telemt_me_reader_eof_total 12603
telemt_me_idle_close_by_peer_total 12602
telemt_me_route_drop_no_conn_total 361647
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 776226
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5366
telemt_desync_full_logged_total 1489
telemt_desync_suppressed_total 3877
telemt_desync_frames_bucket_total{bucket="1_2"} 1550
telemt_desync_frames_bucket_total{bucket="3_10"} 2097
telemt_desync_frames_bucket_total{bucket="gt_10"} 1719
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12207
telemt_me_refill_failed_total 454
telemt_me_writer_restored_same_endpoint_total 11567
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 776373
telemt_user_connections_current{user="hello"} 924
telemt_user_octets_from_client{user="hello"} 12303788231 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 255423467847 (237.88 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 76498.2 (21h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568896
telemt_connections_bad_total 32068
telemt_handshake_timeouts_total 28476
telemt_upstream_connect_attempt_total 127905
telemt_upstream_connect_success_total 127343
telemt_upstream_connect_fail_total 562
telemt_upstream_connect_attempts_per_request{bucket="1"} 127905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 562
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 41514
telemt_me_reconnect_success_total 13503
telemt_me_reader_eof_total 14932
telemt_me_idle_close_by_peer_total 14932
telemt_me_route_drop_no_conn_total 194894
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372799
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1485
telemt_desync_full_logged_total 467
telemt_desync_suppressed_total 1018
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 650
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14541
telemt_me_refill_failed_total 871
telemt_me_writer_restored_same_endpoint_total 13487
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1038
telemt_user_connections_total{user="hello"} 482718
telemt_user_connections_current{user="hello"} 919
telemt_user_octets_from_client{user="hello"} 5369344021 (5.00 GB)
telemt_user_octets_to_client{user="hello"} 136522084868 (127.15 GB)
telemt_user_msgs_from_client{user="hello"} 1628755
telemt_user_msgs_to_client{user="hello"} 6086500
telemt_user_unique_ips_current{user="hello"} 220
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 76273.9 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286670
telemt_connections_bad_total 7874
telemt_handshake_timeouts_total 18719
telemt_upstream_connect_attempt_total 19731
telemt_upstream_connect_success_total 19627
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 19731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10689
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 32266
telemt_me_reconnect_success_total 15756
telemt_me_reader_eof_total 17135
telemt_me_idle_close_by_peer_total 17132
telemt_me_route_drop_no_conn_total 135637
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245585
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 580
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 367
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16481
telemt_me_refill_failed_total 513
telemt_me_writer_restored_same_endpoint_total 15745
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 725
telemt_user_connections_total{user="hello"} 245436
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 19284484168 (17.96 GB)
telemt_user_octets_to_client{user="hello"} 59334421772 (55.26 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 76333.4 (21h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679069
telemt_connections_bad_total 8891
telemt_handshake_timeouts_total 14332
telemt_upstream_connect_attempt_total 59152
telemt_upstream_connect_success_total 58837
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 59152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 30888
telemt_me_reconnect_success_total 11975
telemt_me_reader_eof_total 13213
telemt_me_idle_close_by_peer_total 13212
telemt_me_route_drop_no_conn_total 255946
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 544602
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1867
telemt_desync_full_logged_total 633
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 472
telemt_desync_frames_bucket_total{bucket="3_10"} 838
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12774
telemt_me_refill_failed_total 586
telemt_me_writer_restored_same_endpoint_total 11966
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 799
telemt_user_connections_total{user="hello"} 587411
telemt_user_connections_current{user="hello"} 901
telemt_user_octets_from_client{user="hello"} 6993398085 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 176756321843 (164.62 GB)
telemt_user_msgs_from_client{user="hello"} 450107
telemt_user_msgs_to_client{user="hello"} 3309431
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 76305.3 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304815
telemt_connections_bad_total 57872
telemt_handshake_timeouts_total 3751
telemt_upstream_connect_attempt_total 21681
telemt_upstream_connect_success_total 21206
telemt_upstream_connect_fail_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 21681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 475
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 45578
telemt_me_reconnect_success_total 16978
telemt_me_reader_eof_total 18460
telemt_me_idle_close_by_peer_total 18458
telemt_me_route_drop_no_conn_total 87256
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230380
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1143
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 897
telemt_desync_frames_bucket_total{bucket="1_2"} 572
telemt_desync_frames_bucket_total{bucket="3_10"} 441
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 18151
telemt_me_refill_failed_total 889
telemt_me_writer_restored_same_endpoint_total 16970
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1173
telemt_user_connections_total{user="hello"} 230944
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 2838513199 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 85307478807 (79.45 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 76467.3 (21h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 746241
telemt_connections_bad_total 59841
telemt_handshake_timeouts_total 7132
telemt_upstream_connect_attempt_total 15370
telemt_upstream_connect_success_total 15288
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 21758
telemt_me_reconnect_success_total 11458
telemt_me_reader_eof_total 12463
telemt_me_idle_close_by_peer_total 12463
telemt_me_route_drop_no_conn_total 551426
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762652
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1121
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 718
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 448
telemt_desync_frames_bucket_total{bucket="gt_10"} 408
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 11961
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11444
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 641941
telemt_user_connections_current{user="hello"} 868
telemt_user_octets_from_client{user="hello"} 9372321452 (8.73 GB)
telemt_user_octets_to_client{user="hello"} 287489571084 (267.75 GB)
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 24233.3 (6h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18796
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 13048
telemt_upstream_connect_success_total 12939
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 13048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23120
telemt_me_reconnect_success_total 11551
telemt_me_reader_eof_total 12199
telemt_me_idle_close_by_peer_total 12199
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 7100
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17914
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 12037
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 11533
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 18010
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 554825089 (529.12 MB)
telemt_user_octets_to_client{user="hello"} 24637367658 (22.95 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```