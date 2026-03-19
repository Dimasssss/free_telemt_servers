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

# Server Metrics 2026-03-19 08:52:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 39821.1 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 778110
telemt_connections_bad_total 76860
telemt_connections_current 1560
telemt_connections_me_current 1560
telemt_handshake_timeouts_total 32653
telemt_upstream_connect_attempt_total 7552
telemt_upstream_connect_success_total 7419
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 7552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 6564
telemt_me_reconnect_success_total 5410
telemt_me_reader_eof_total 5739
telemt_me_idle_close_by_peer_total 5738
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 221690
telemt_me_route_drop_channel_closed_total 90
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 594730
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3832
telemt_desync_full_logged_total 1124
telemt_desync_suppressed_total 2708
telemt_desync_frames_bucket_total{bucket="1_2"} 1285
telemt_desync_frames_bucket_total{bucket="3_10"} 1410
telemt_desync_frames_bucket_total{bucket="gt_10"} 1137
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5508
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5392
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 591742
telemt_user_connections_current{user="hello"} 1560
telemt_user_octets_from_client{user="hello"} 9598345456 (8.94 GB)
telemt_user_octets_to_client{user="hello"} 195515011336 (182.09 GB)
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 39825.3 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1904256
telemt_connections_bad_total 106044
telemt_connections_current 4113
telemt_connections_me_current 4113
telemt_handshake_timeouts_total 43544
telemt_upstream_connect_attempt_total 7549
telemt_upstream_connect_success_total 7407
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 7549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3705
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 6539
telemt_me_reconnect_success_total 5377
telemt_me_reader_eof_total 5694
telemt_me_idle_close_by_peer_total 5694
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 829544
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1576432
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6977
telemt_desync_full_logged_total 2372
telemt_desync_suppressed_total 4605
telemt_desync_frames_bucket_total{bucket="1_2"} 1250
telemt_desync_frames_bucket_total{bucket="3_10"} 2668
telemt_desync_frames_bucket_total{bucket="gt_10"} 3059
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5512
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5355
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 1576194
telemt_user_connections_current{user="hello"} 4113
telemt_user_octets_from_client{user="hello"} 26740301496 (24.90 GB)
telemt_user_octets_to_client{user="hello"} 596246686744 (555.30 GB)
telemt_user_unique_ips_current{user="hello"} 1412
telemt_user_unique_ips_recent_window{user="hello"} 620
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 39822.4 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1610801
telemt_connections_bad_total 202682
telemt_connections_current 3266
telemt_connections_me_current 3266
telemt_handshake_timeouts_total 39794
telemt_upstream_connect_attempt_total 7125
telemt_upstream_connect_success_total 7125
telemt_upstream_connect_attempts_per_request{bucket="1"} 7125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 5127
telemt_me_reconnect_success_total 5096
telemt_me_reader_eof_total 5400
telemt_me_idle_close_by_peer_total 5400
telemt_me_route_drop_no_conn_total 736138
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1239899
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5772
telemt_desync_full_logged_total 1796
telemt_desync_suppressed_total 3976
telemt_desync_frames_bucket_total{bucket="1_2"} 1289
telemt_desync_frames_bucket_total{bucket="3_10"} 2083
telemt_desync_frames_bucket_total{bucket="gt_10"} 2400
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5188
telemt_me_writer_restored_same_endpoint_total 5080
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 1239401
telemt_user_connections_current{user="hello"} 3266
telemt_user_octets_from_client{user="hello"} 20063092384 (18.69 GB)
telemt_user_octets_to_client{user="hello"} 597403053392 (556.37 GB)
telemt_user_unique_ips_current{user="hello"} 1119
telemt_user_unique_ips_recent_window{user="hello"} 501
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 39875.4 (11h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1664012
telemt_connections_bad_total 96742
telemt_connections_current 2871
telemt_connections_me_current 2871
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 42661
telemt_upstream_connect_attempt_total 15362
telemt_upstream_connect_success_total 15260
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 15362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4177
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7476
telemt_me_reconnect_success_total 5081
telemt_me_reader_eof_total 5403
telemt_me_idle_close_by_peer_total 5402
telemt_me_route_drop_no_conn_total 742549
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1203145
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4438
telemt_desync_full_logged_total 1521
telemt_desync_suppressed_total 2917
telemt_desync_frames_bucket_total{bucket="1_2"} 879
telemt_desync_frames_bucket_total{bucket="3_10"} 1746
telemt_desync_frames_bucket_total{bucket="gt_10"} 1813
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5340
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5057
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 1209929
telemt_user_connections_current{user="hello"} 2871
telemt_user_octets_from_client{user="hello"} 15398084352 (14.34 GB)
telemt_user_octets_to_client{user="hello"} 376244360930 (350.40 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 447
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 39818.8 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1975546
telemt_connections_bad_total 505714
telemt_connections_current 3397
telemt_connections_me_current 3397
telemt_handshake_timeouts_total 41188
telemt_upstream_connect_attempt_total 6840
telemt_upstream_connect_success_total 6791
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 6840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 4812
telemt_me_reconnect_success_total 4772
telemt_me_reader_eof_total 5063
telemt_me_idle_close_by_peer_total 5063
telemt_me_route_drop_no_conn_total 532396
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1230180
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6011
telemt_desync_full_logged_total 1874
telemt_desync_suppressed_total 4137
telemt_desync_frames_bucket_total{bucket="1_2"} 1213
telemt_desync_frames_bucket_total{bucket="3_10"} 2674
telemt_desync_frames_bucket_total{bucket="gt_10"} 2124
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 4842
telemt_me_writer_restored_same_endpoint_total 4748
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1229512
telemt_user_connections_current{user="hello"} 3397
telemt_user_octets_from_client{user="hello"} 24087584944 (22.43 GB)
telemt_user_octets_to_client{user="hello"} 566161039328 (527.28 GB)
telemt_user_unique_ips_current{user="hello"} 1188
telemt_user_unique_ips_recent_window{user="hello"} 519
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 39830.6 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340130
telemt_connections_bad_total 14751
telemt_connections_current 789
telemt_connections_me_current 789
telemt_handshake_timeouts_total 2879
telemt_upstream_connect_attempt_total 10199
telemt_upstream_connect_success_total 9935
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 10199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 13295
telemt_me_reconnect_success_total 7914
telemt_me_reader_eof_total 8405
telemt_me_idle_close_by_peer_total 8405
telemt_me_route_drop_no_conn_total 156843
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 304495
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 468
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 193
telemt_me_writer_removed_unexpected_total 8139
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7884
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 304464
telemt_user_connections_current{user="hello"} 789
telemt_user_octets_from_client{user="hello"} 4468024648 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 132063017628 (122.99 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 39821.3 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1316873
telemt_connections_bad_total 115107
telemt_connections_current 2964
telemt_connections_me_current 2964
telemt_handshake_timeouts_total 58293
telemt_upstream_connect_attempt_total 8035
telemt_upstream_connect_success_total 8034
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 7357
telemt_me_reconnect_success_total 6011
telemt_me_reader_eof_total 6374
telemt_me_idle_close_by_peer_total 6373
telemt_me_route_drop_no_conn_total 513491
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1092691
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6400
telemt_desync_full_logged_total 2103
telemt_desync_suppressed_total 4297
telemt_desync_frames_bucket_total{bucket="1_2"} 1207
telemt_desync_frames_bucket_total{bucket="3_10"} 2421
telemt_desync_frames_bucket_total{bucket="gt_10"} 2772
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6122
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5996
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 1091606
telemt_user_connections_current{user="hello"} 2964
telemt_user_octets_from_client{user="hello"} 15066100456 (14.03 GB)
telemt_user_octets_to_client{user="hello"} 548125062928 (510.48 GB)
telemt_user_unique_ips_current{user="hello"} 983
telemt_user_unique_ips_recent_window{user="hello"} 429
```