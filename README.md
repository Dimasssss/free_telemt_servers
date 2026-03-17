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

# Server Metrics 2026-03-17 13:02:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 65817.0 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 637404
telemt_connections_bad_total 5080
telemt_handshake_timeouts_total 19971
telemt_upstream_connect_attempt_total 16370
telemt_upstream_connect_success_total 15918
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 16370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 13076
telemt_me_reconnect_success_total 10320
telemt_me_reader_eof_total 10960
telemt_me_idle_close_by_peer_total 10959
telemt_me_route_drop_no_conn_total 208133
telemt_me_route_drop_channel_closed_total 63
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 575666
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4284
telemt_desync_full_logged_total 1166
telemt_desync_suppressed_total 3118
telemt_desync_frames_bucket_total{bucket="1_2"} 1240
telemt_desync_frames_bucket_total{bucket="3_10"} 1770
telemt_desync_frames_bucket_total{bucket="gt_10"} 1274
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10555
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 10298
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 577549
telemt_user_connections_current{user="hello"} 1123
telemt_user_octets_from_client{user="hello"} 8009654959 (7.46 GB)
telemt_user_octets_to_client{user="hello"} 204628764079 (190.58 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 66068.8 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377675
telemt_connections_bad_total 22336
telemt_handshake_timeouts_total 20194
telemt_upstream_connect_attempt_total 16725
telemt_upstream_connect_success_total 16459
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 16725
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 244
telemt_me_reconnect_attempts_total 26210
telemt_me_reconnect_success_total 13137
telemt_me_reader_eof_total 14129
telemt_me_idle_close_by_peer_total 14129
telemt_me_route_drop_no_conn_total 148666
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315251
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1197
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 800
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 533
telemt_desync_frames_bucket_total{bucket="gt_10"} 391
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13705
telemt_me_refill_failed_total 405
telemt_me_writer_restored_same_endpoint_total 13121
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 315227
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 3540921896 (3.30 GB)
telemt_user_octets_to_client{user="hello"} 112764261984 (105.02 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 65844.3 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209369
telemt_connections_bad_total 7746
telemt_handshake_timeouts_total 16528
telemt_upstream_connect_attempt_total 17223
telemt_upstream_connect_success_total 17134
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 17223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9431
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 15675
telemt_me_reconnect_success_total 13798
telemt_me_reader_eof_total 14720
telemt_me_idle_close_by_peer_total 14720
telemt_me_route_drop_no_conn_total 70856
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173966
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 686
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 502
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 131
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14051
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13787
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 173858
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 15202435016 (14.16 GB)
telemt_user_octets_to_client{user="hello"} 49223884676 (45.84 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 65903.6 (18h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 478780
telemt_connections_bad_total 7738
telemt_handshake_timeouts_total 12534
telemt_upstream_connect_attempt_total 15890
telemt_upstream_connect_success_total 15747
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 15890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 15136
telemt_me_reconnect_success_total 11403
telemt_me_reader_eof_total 12179
telemt_me_idle_close_by_peer_total 12179
telemt_me_route_drop_no_conn_total 135885
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403672
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1433
telemt_desync_full_logged_total 500
telemt_desync_suppressed_total 933
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 437
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11722
telemt_me_refill_failed_total 112
telemt_me_writer_restored_same_endpoint_total 11394
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 404546
telemt_user_connections_current{user="hello"} 839
telemt_user_octets_from_client{user="hello"} 5215602542 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 140341239871 (130.70 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 65875.4 (18h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239973
telemt_connections_bad_total 53147
telemt_handshake_timeouts_total 3187
telemt_upstream_connect_attempt_total 19204
telemt_upstream_connect_success_total 18957
telemt_upstream_connect_fail_total 247
telemt_upstream_connect_attempts_per_request{bucket="1"} 19204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 247
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 30748
telemt_me_reconnect_success_total 15517
telemt_me_reader_eof_total 16631
telemt_me_idle_close_by_peer_total 16631
telemt_me_route_drop_no_conn_total 64011
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175069
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1036
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 824
telemt_desync_frames_bucket_total{bucket="1_2"} 524
telemt_desync_frames_bucket_total{bucket="3_10"} 387
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16197
telemt_me_refill_failed_total 473
telemt_me_writer_restored_same_endpoint_total 15509
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 680
telemt_user_connections_total{user="hello"} 175074
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 2314262531 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 68863749206 (64.13 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 66037.3 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571972
telemt_connections_bad_total 52097
telemt_handshake_timeouts_total 5530
telemt_upstream_connect_attempt_total 13333
telemt_upstream_connect_success_total 13262
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 13853
telemt_me_reconnect_success_total 9951
telemt_me_reader_eof_total 10709
telemt_me_idle_close_by_peer_total 10709
telemt_me_route_drop_no_conn_total 372222
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 566802
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 834
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 305
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10225
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9937
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 484074
telemt_user_connections_current{user="hello"} 1004
telemt_user_octets_from_client{user="hello"} 7149832688 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 231703618420 (215.79 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 13803.6 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10716
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 44
telemt_upstream_connect_attempt_total 7689
telemt_upstream_connect_success_total 7623
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 7689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 10898
telemt_me_reconnect_success_total 6751
telemt_me_reader_eof_total 7068
telemt_me_idle_close_by_peer_total 7068
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 3874
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10324
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 6946
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6739
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 10427
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 286126781 (272.87 MB)
telemt_user_octets_to_client{user="hello"} 20931072722 (19.49 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 6
```