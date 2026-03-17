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

# Server Metrics 2026-03-17 12:01:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 62146.4 (17h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 569667
telemt_connections_bad_total 4785
telemt_handshake_timeouts_total 17471
telemt_upstream_connect_attempt_total 15420
telemt_upstream_connect_success_total 14975
telemt_upstream_connect_fail_total 445
telemt_upstream_connect_attempts_per_request{bucket="1"} 15420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 445
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 11126
telemt_me_reconnect_success_total 9589
telemt_me_reader_eof_total 10166
telemt_me_idle_close_by_peer_total 10165
telemt_me_route_drop_no_conn_total 185096
telemt_me_route_drop_channel_closed_total 52
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514379
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3979
telemt_desync_full_logged_total 1058
telemt_desync_suppressed_total 2921
telemt_desync_frames_bucket_total{bucket="1_2"} 1147
telemt_desync_frames_bucket_total{bucket="3_10"} 1659
telemt_desync_frames_bucket_total{bucket="gt_10"} 1173
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9775
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 9567
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 516296
telemt_user_connections_current{user="hello"} 948
telemt_user_octets_from_client{user="hello"} 6959463991 (6.48 GB)
telemt_user_octets_to_client{user="hello"} 186742953027 (173.92 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 62398.3 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321116
telemt_connections_bad_total 14819
telemt_handshake_timeouts_total 18310
telemt_upstream_connect_attempt_total 15786
telemt_upstream_connect_success_total 15562
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 15785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 24790
telemt_me_reconnect_success_total 12454
telemt_me_reader_eof_total 13429
telemt_me_idle_close_by_peer_total 13429
telemt_me_route_drop_no_conn_total 118520
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272443
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 944
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 624
telemt_desync_frames_bucket_total{bucket="1_2"} 246
telemt_desync_frames_bucket_total{bucket="3_10"} 400
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 12975
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12438
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 272435
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 3165948240 (2.95 GB)
telemt_user_octets_to_client{user="hello"} 99727282484 (92.88 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 62173.9 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186854
telemt_connections_bad_total 7724
telemt_handshake_timeouts_total 15596
telemt_upstream_connect_attempt_total 16319
telemt_upstream_connect_success_total 16233
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 16319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 14971
telemt_me_reconnect_success_total 13098
telemt_me_reader_eof_total 13986
telemt_me_idle_close_by_peer_total 13986
telemt_me_route_drop_no_conn_total 55861
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153013
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 560
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 413
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13345
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13087
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 152914
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 14871079232 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 43635262372 (40.64 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 62233.1 (17h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423764
telemt_connections_bad_total 6852
telemt_handshake_timeouts_total 12199
telemt_upstream_connect_attempt_total 14222
telemt_upstream_connect_success_total 14088
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 14222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7414
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 14263
telemt_me_reconnect_success_total 10893
telemt_me_reader_eof_total 11629
telemt_me_idle_close_by_peer_total 11629
telemt_me_route_drop_no_conn_total 119672
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 354270
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1080
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 683
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 476
telemt_desync_frames_bucket_total{bucket="gt_10"} 348
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 11173
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 10884
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 354202
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 4537368994 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 127896348693 (119.11 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 62205.1 (17h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219615
telemt_connections_bad_total 52304
telemt_handshake_timeouts_total 3085
telemt_upstream_connect_attempt_total 18253
telemt_upstream_connect_success_total 18014
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 18253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28423
telemt_me_reconnect_success_total 14764
telemt_me_reader_eof_total 15804
telemt_me_idle_close_by_peer_total 15804
telemt_me_route_drop_no_conn_total 57826
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156934
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 902
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 725
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 15377
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 14756
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 156949
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 2142599251 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 65127947782 (60.66 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 62366.6 (17h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519970
telemt_connections_bad_total 51927
telemt_handshake_timeouts_total 4808
telemt_upstream_connect_attempt_total 12610
telemt_upstream_connect_success_total 12542
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 12610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6324
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 13313
telemt_me_reconnect_success_total 9419
telemt_me_reader_eof_total 10159
telemt_me_idle_close_by_peer_total 10159
telemt_me_route_drop_no_conn_total 343177
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 513058
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 777
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 490
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 300
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 9687
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9405
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 434739
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 6478347192 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 215904020164 (201.08 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 10133.2 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7673
telemt_connections_bad_total 45
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 5794
telemt_upstream_connect_success_total 5743
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 5794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2644
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 8295
telemt_me_reconnect_success_total 5054
telemt_me_reader_eof_total 5309
telemt_me_idle_close_by_peer_total 5309
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 2874
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7326
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 5204
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 5045
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 7432
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 158717341 (151.36 MB)
telemt_user_octets_to_client{user="hello"} 19364576502 (18.03 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```