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

# Server Metrics 2026-03-17 11:55:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 61840.7 (17h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565175
telemt_connections_bad_total 4767
telemt_handshake_timeouts_total 17436
telemt_upstream_connect_attempt_total 15336
telemt_upstream_connect_success_total 14892
telemt_upstream_connect_fail_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 15336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6887
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 444
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 11057
telemt_me_reconnect_success_total 9520
telemt_me_reader_eof_total 10097
telemt_me_idle_close_by_peer_total 10096
telemt_me_route_drop_no_conn_total 183377
telemt_me_route_drop_channel_closed_total 52
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 510056
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3965
telemt_desync_full_logged_total 1053
telemt_desync_suppressed_total 2912
telemt_desync_frames_bucket_total{bucket="1_2"} 1145
telemt_desync_frames_bucket_total{bucket="3_10"} 1652
telemt_desync_frames_bucket_total{bucket="gt_10"} 1168
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9706
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 9498
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 511979
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 6914883071 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 184766892343 (172.08 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 62092.0 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317413
telemt_connections_bad_total 14264
telemt_handshake_timeouts_total 18145
telemt_upstream_connect_attempt_total 15631
telemt_upstream_connect_success_total 15411
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 15631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 24681
telemt_me_reconnect_success_total 12346
telemt_me_reader_eof_total 13319
telemt_me_idle_close_by_peer_total 13319
telemt_me_route_drop_no_conn_total 117365
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269537
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 909
telemt_desync_full_logged_total 312
telemt_desync_suppressed_total 597
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 285
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 12865
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12330
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 269531
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 3146118748 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 98292396912 (91.54 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 61868.4 (17h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185187
telemt_connections_bad_total 7724
telemt_handshake_timeouts_total 15416
telemt_upstream_connect_attempt_total 16252
telemt_upstream_connect_success_total 16167
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 16252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8940
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 14931
telemt_me_reconnect_success_total 13058
telemt_me_reader_eof_total 13946
telemt_me_idle_close_by_peer_total 13946
telemt_me_route_drop_no_conn_total 55431
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151557
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 552
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 407
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13305
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13047
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 151458
telemt_user_connections_current{user="hello"} 268
telemt_user_octets_from_client{user="hello"} 14862972468 (13.84 GB)
telemt_user_octets_to_client{user="hello"} 43361870096 (40.38 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 61927.2 (17h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419920
telemt_connections_bad_total 6850
telemt_handshake_timeouts_total 12180
telemt_upstream_connect_attempt_total 14133
telemt_upstream_connect_success_total 13999
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 14133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7365
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 14217
telemt_me_reconnect_success_total 10847
telemt_me_reader_eof_total 11574
telemt_me_idle_close_by_peer_total 11574
telemt_me_route_drop_no_conn_total 118514
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350619
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1059
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 673
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 464
telemt_desync_frames_bucket_total{bucket="gt_10"} 345
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11127
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 10838
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 350552
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 4511077842 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 126997323885 (118.28 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 61899.2 (17h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218358
telemt_connections_bad_total 52246
telemt_handshake_timeouts_total 3066
telemt_upstream_connect_attempt_total 18168
telemt_upstream_connect_success_total 17931
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 18168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28380
telemt_me_reconnect_success_total 14723
telemt_me_reader_eof_total 15760
telemt_me_idle_close_by_peer_total 15760
telemt_me_route_drop_no_conn_total 57503
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155781
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
telemt_me_writer_removed_unexpected_total 15333
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 14715
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 155796
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 2136600583 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 64795011142 (60.35 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 62060.4 (17h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516519
telemt_connections_bad_total 51925
telemt_handshake_timeouts_total 4780
telemt_upstream_connect_attempt_total 12512
telemt_upstream_connect_success_total 12445
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 13261
telemt_me_reconnect_success_total 9368
telemt_me_reader_eof_total 10096
telemt_me_idle_close_by_peer_total 10096
telemt_me_route_drop_no_conn_total 341490
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 509713
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
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 9634
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9354
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 431394
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 6429295676 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 215142837576 (200.37 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 9827.4 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7439
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 5597
telemt_upstream_connect_success_total 5549
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 5597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 8144
telemt_me_reconnect_success_total 4905
telemt_me_reader_eof_total 5113
telemt_me_idle_close_by_peer_total 5113
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 2757
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7096
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 5055
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 4896
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 7202
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 157726377 (150.42 MB)
telemt_user_octets_to_client{user="hello"} 19331695038 (18.00 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 7
```