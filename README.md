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

# Server Metrics 2026-03-19 10:39:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 46262.0 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1057376
telemt_connections_bad_total 91494
telemt_connections_current 1383
telemt_connections_me_current 1383
telemt_handshake_timeouts_total 37431
telemt_upstream_connect_attempt_total 8798
telemt_upstream_connect_success_total 8643
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 8798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 7473
telemt_me_reconnect_success_total 6310
telemt_me_reader_eof_total 6678
telemt_me_idle_close_by_peer_total 6675
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 406445
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 817603
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4655
telemt_desync_full_logged_total 1428
telemt_desync_suppressed_total 3227
telemt_desync_frames_bucket_total{bucket="1_2"} 1537
telemt_desync_frames_bucket_total{bucket="3_10"} 1701
telemt_desync_frames_bucket_total{bucket="gt_10"} 1417
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6426
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 6290
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 811756
telemt_user_connections_current{user="hello"} 1383
telemt_user_octets_from_client{user="hello"} 12349039192 (11.50 GB)
telemt_user_octets_to_client{user="hello"} 252271044260 (234.95 GB)
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 46265.5 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2634764
telemt_connections_bad_total 162983
telemt_connections_current 3896
telemt_connections_me_current 3896
telemt_handshake_timeouts_total 55094
telemt_upstream_connect_attempt_total 8860
telemt_upstream_connect_success_total 8696
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 8860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 9754
telemt_me_reconnect_success_total 6342
telemt_me_reader_eof_total 6765
telemt_me_idle_close_by_peer_total 6764
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1328448
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2193869
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9737
telemt_desync_full_logged_total 3235
telemt_desync_suppressed_total 6502
telemt_desync_frames_bucket_total{bucket="1_2"} 1824
telemt_desync_frames_bucket_total{bucket="3_10"} 3824
telemt_desync_frames_bucket_total{bucket="gt_10"} 4089
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6564
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 6320
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 2193535
telemt_user_connections_current{user="hello"} 3896
telemt_user_octets_from_client{user="hello"} 32942460460 (30.68 GB)
telemt_user_octets_to_client{user="hello"} 763685999408 (711.24 GB)
telemt_user_unique_ips_current{user="hello"} 1375
telemt_user_unique_ips_recent_window{user="hello"} 694
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 46262.7 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2227195
telemt_connections_bad_total 259093
telemt_connections_current 2959
telemt_connections_me_current 2959
telemt_handshake_timeouts_total 49147
telemt_upstream_connect_attempt_total 8254
telemt_upstream_connect_success_total 8254
telemt_upstream_connect_attempts_per_request{bucket="1"} 8254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5936
telemt_me_reconnect_success_total 5897
telemt_me_reader_eof_total 6238
telemt_me_idle_close_by_peer_total 6238
telemt_me_route_drop_no_conn_total 1368528
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1750504
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7504
telemt_desync_full_logged_total 2392
telemt_desync_suppressed_total 5112
telemt_desync_frames_bucket_total{bucket="1_2"} 1667
telemt_desync_frames_bucket_total{bucket="3_10"} 2768
telemt_desync_frames_bucket_total{bucket="gt_10"} 3069
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6001
telemt_me_writer_restored_same_endpoint_total 5881
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 1748853
telemt_user_connections_current{user="hello"} 2959
telemt_user_octets_from_client{user="hello"} 24923638196 (23.21 GB)
telemt_user_octets_to_client{user="hello"} 756424783292 (704.48 GB)
telemt_user_unique_ips_current{user="hello"} 1021
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 46316.1 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2208359
telemt_connections_bad_total 120761
telemt_connections_current 2977
telemt_connections_me_current 2977
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 58494
telemt_upstream_connect_attempt_total 16567
telemt_upstream_connect_success_total 16410
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 16567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9223
telemt_me_reconnect_success_total 5896
telemt_me_reader_eof_total 6263
telemt_me_idle_close_by_peer_total 6262
telemt_me_route_drop_no_conn_total 1121868
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1677893
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6121
telemt_desync_full_logged_total 2079
telemt_desync_suppressed_total 4042
telemt_desync_frames_bucket_total{bucket="1_2"} 1285
telemt_desync_frames_bucket_total{bucket="3_10"} 2386
telemt_desync_frames_bucket_total{bucket="gt_10"} 2450
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6318
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 5872
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 422
telemt_user_connections_total{user="hello"} 1684094
telemt_user_connections_current{user="hello"} 2977
telemt_user_octets_from_client{user="hello"} 19323618164 (18.00 GB)
telemt_user_octets_to_client{user="hello"} 484953793122 (451.65 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1015
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 46259.1 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2627839
telemt_connections_bad_total 585150
telemt_connections_current 3581
telemt_connections_me_current 3581
telemt_handshake_timeouts_total 52443
telemt_upstream_connect_attempt_total 8148
telemt_upstream_connect_success_total 8091
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 8148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6950
telemt_me_reconnect_success_total 5750
telemt_me_reader_eof_total 6114
telemt_me_idle_close_by_peer_total 6113
telemt_me_route_drop_no_conn_total 976602
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1735048
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7699
telemt_desync_full_logged_total 2397
telemt_desync_suppressed_total 5302
telemt_desync_frames_bucket_total{bucket="1_2"} 1521
telemt_desync_frames_bucket_total{bucket="3_10"} 3322
telemt_desync_frames_bucket_total{bucket="gt_10"} 2856
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 5872
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5726
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 1734144
telemt_user_connections_current{user="hello"} 3581
telemt_user_octets_from_client{user="hello"} 30825907956 (28.71 GB)
telemt_user_octets_to_client{user="hello"} 718236154388 (668.91 GB)
telemt_user_unique_ips_current{user="hello"} 1203
telemt_user_unique_ips_recent_window{user="hello"} 559
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 46271.4 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460911
telemt_connections_bad_total 18316
telemt_connections_current 864
telemt_connections_me_current 864
telemt_handshake_timeouts_total 3626
telemt_upstream_connect_attempt_total 11630
telemt_upstream_connect_success_total 11338
telemt_upstream_connect_fail_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 11630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 292
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 14389
telemt_me_reconnect_success_total 8996
telemt_me_reader_eof_total 9532
telemt_me_idle_close_by_peer_total 9532
telemt_me_route_drop_no_conn_total 236167
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 415902
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 849
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 567
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 329
telemt_desync_frames_bucket_total{bucket="gt_10"} 335
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9239
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8966
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 415862
telemt_user_connections_current{user="hello"} 864
telemt_user_octets_from_client{user="hello"} 6572355904 (6.12 GB)
telemt_user_octets_to_client{user="hello"} 158625724216 (147.73 GB)
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 46261.7 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1770674
telemt_connections_bad_total 147792
telemt_connections_current 3064
telemt_connections_me_current 3064
telemt_handshake_timeouts_total 70109
telemt_upstream_connect_attempt_total 9393
telemt_upstream_connect_success_total 9392
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8396
telemt_me_reconnect_success_total 7040
telemt_me_reader_eof_total 7458
telemt_me_idle_close_by_peer_total 7457
telemt_me_route_drop_no_conn_total 692480
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1468872
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8393
telemt_desync_full_logged_total 2708
telemt_desync_suppressed_total 5685
telemt_desync_frames_bucket_total{bucket="1_2"} 1578
telemt_desync_frames_bucket_total{bucket="3_10"} 3171
telemt_desync_frames_bucket_total{bucket="gt_10"} 3644
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7170
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7025
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 1467640
telemt_user_connections_current{user="hello"} 3064
telemt_user_octets_from_client{user="hello"} 20637624712 (19.22 GB)
telemt_user_octets_to_client{user="hello"} 702775309544 (654.51 GB)
telemt_user_unique_ips_current{user="hello"} 1024
telemt_user_unique_ips_recent_window{user="hello"} 452
```