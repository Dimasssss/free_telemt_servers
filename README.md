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

# Server Metrics 2026-03-19 11:46:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 50259.7 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1217383
telemt_connections_bad_total 102043
telemt_connections_current 1789
telemt_connections_me_current 1789
telemt_handshake_timeouts_total 42499
telemt_upstream_connect_attempt_total 9604
telemt_upstream_connect_success_total 9439
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 9604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 8811
telemt_me_reconnect_success_total 6925
telemt_me_reader_eof_total 7334
telemt_me_idle_close_by_peer_total 7331
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 507554
telemt_me_route_drop_channel_closed_total 199
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 953474
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5329
telemt_desync_full_logged_total 1624
telemt_desync_suppressed_total 3705
telemt_desync_frames_bucket_total{bucket="1_2"} 1722
telemt_desync_frames_bucket_total{bucket="3_10"} 1931
telemt_desync_frames_bucket_total{bucket="gt_10"} 1676
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 7084
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 6904
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 947403
telemt_user_connections_current{user="hello"} 1789
telemt_user_octets_from_client{user="hello"} 14583918208 (13.58 GB)
telemt_user_octets_to_client{user="hello"} 287777174556 (268.01 GB)
telemt_user_unique_ips_current{user="hello"} 576
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 50264.1 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3387048
telemt_connections_bad_total 220324
telemt_connections_current 4156
telemt_connections_me_current 4156
telemt_handshake_timeouts_total 61535
telemt_upstream_connect_attempt_total 9475
telemt_upstream_connect_success_total 9303
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 9475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15519
telemt_me_reconnect_success_total 6757
telemt_me_reader_eof_total 7346
telemt_me_idle_close_by_peer_total 7345
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 2713189
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2848575
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11174
telemt_desync_full_logged_total 3737
telemt_desync_suppressed_total 7437
telemt_desync_frames_bucket_total{bucket="1_2"} 2167
telemt_desync_frames_bucket_total{bucket="3_10"} 4405
telemt_desync_frames_bucket_total{bucket="gt_10"} 4602
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7149
telemt_me_refill_failed_total 273
telemt_me_writer_restored_same_endpoint_total 6734
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 392
telemt_user_connections_total{user="hello"} 2848193
telemt_user_connections_current{user="hello"} 4156
telemt_user_octets_from_client{user="hello"} 36974163336 (34.43 GB)
telemt_user_octets_to_client{user="hello"} 836707693828 (779.24 GB)
telemt_user_unique_ips_current{user="hello"} 1290
telemt_user_unique_ips_recent_window{user="hello"} 820
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 50261.7 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2570648
telemt_connections_bad_total 300244
telemt_connections_current 3623
telemt_connections_me_current 3623
telemt_handshake_timeouts_total 52257
telemt_upstream_connect_attempt_total 9041
telemt_upstream_connect_success_total 9041
telemt_upstream_connect_attempts_per_request{bucket="1"} 9041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4336
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 7688
telemt_me_reconnect_success_total 6494
telemt_me_reader_eof_total 6891
telemt_me_idle_close_by_peer_total 6890
telemt_me_route_drop_no_conn_total 1574022
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2023623
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8373
telemt_desync_full_logged_total 2657
telemt_desync_suppressed_total 5716
telemt_desync_frames_bucket_total{bucket="1_2"} 1896
telemt_desync_frames_bucket_total{bucket="3_10"} 3070
telemt_desync_frames_bucket_total{bucket="gt_10"} 3407
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6643
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6478
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 2021404
telemt_user_connections_current{user="hello"} 3623
telemt_user_octets_from_client{user="hello"} 28309217132 (26.37 GB)
telemt_user_octets_to_client{user="hello"} 862138432016 (802.93 GB)
telemt_user_unique_ips_current{user="hello"} 1136
telemt_user_unique_ips_recent_window{user="hello"} 589
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 50314.2 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2639542
telemt_connections_bad_total 138354
telemt_connections_current 2852
telemt_connections_me_current 2852
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 64965
telemt_upstream_connect_attempt_total 17348
telemt_upstream_connect_success_total 17172
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 17348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5057
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 10813
telemt_me_reconnect_success_total 6465
telemt_me_reader_eof_total 6886
telemt_me_idle_close_by_peer_total 6885
telemt_me_route_drop_no_conn_total 1729955
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2043465
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7234
telemt_desync_full_logged_total 2402
telemt_desync_suppressed_total 4832
telemt_desync_frames_bucket_total{bucket="1_2"} 1538
telemt_desync_frames_bucket_total{bucket="3_10"} 2833
telemt_desync_frames_bucket_total{bucket="gt_10"} 2863
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6935
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6441
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 470
telemt_user_connections_total{user="hello"} 2049574
telemt_user_connections_current{user="hello"} 2852
telemt_user_octets_from_client{user="hello"} 22896269508 (21.32 GB)
telemt_user_octets_to_client{user="hello"} 549284860982 (511.56 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 993
telemt_user_unique_ips_recent_window{user="hello"} 476
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 50257.4 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3062493
telemt_connections_bad_total 661319
telemt_connections_current 3374
telemt_connections_me_current 3374
telemt_handshake_timeouts_total 61828
telemt_upstream_connect_attempt_total 8975
telemt_upstream_connect_success_total 8910
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 8975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 7588
telemt_me_reconnect_success_total 6382
telemt_me_reader_eof_total 6771
telemt_me_idle_close_by_peer_total 6770
telemt_me_route_drop_no_conn_total 1189276
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2034838
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8804
telemt_desync_full_logged_total 2734
telemt_desync_suppressed_total 6070
telemt_desync_frames_bucket_total{bucket="1_2"} 1660
telemt_desync_frames_bucket_total{bucket="3_10"} 3815
telemt_desync_frames_bucket_total{bucket="gt_10"} 3329
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6514
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6358
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 2033394
telemt_user_connections_current{user="hello"} 3374
telemt_user_octets_from_client{user="hello"} 34781425260 (32.39 GB)
telemt_user_octets_to_client{user="hello"} 813805108208 (757.92 GB)
telemt_user_unique_ips_current{user="hello"} 1222
telemt_user_unique_ips_recent_window{user="hello"} 597
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 50270.9 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530475
telemt_connections_bad_total 18821
telemt_connections_current 1133
telemt_connections_me_current 1133
telemt_handshake_timeouts_total 4122
telemt_upstream_connect_attempt_total 12398
telemt_upstream_connect_success_total 12081
telemt_upstream_connect_fail_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 12398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 317
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 17141
telemt_me_reconnect_success_total 9550
telemt_me_reader_eof_total 10186
telemt_me_idle_close_by_peer_total 10186
telemt_me_route_drop_no_conn_total 275568
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481711
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1048
telemt_desync_full_logged_total 366
telemt_desync_suppressed_total 682
telemt_desync_frames_bucket_total{bucket="1_2"} 216
telemt_desync_frames_bucket_total{bucket="3_10"} 423
telemt_desync_frames_bucket_total{bucket="gt_10"} 409
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9877
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9519
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 481650
telemt_user_connections_current{user="hello"} 1133
telemt_user_octets_from_client{user="hello"} 7689456436 (7.16 GB)
telemt_user_octets_to_client{user="hello"} 175826210276 (163.75 GB)
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 50260.0 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2144185
telemt_connections_bad_total 176654
telemt_connections_current 3267
telemt_connections_me_current 3267
telemt_handshake_timeouts_total 73005
telemt_upstream_connect_attempt_total 10059
telemt_upstream_connect_success_total 10058
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 8883
telemt_me_reconnect_success_total 7513
telemt_me_reader_eof_total 7952
telemt_me_idle_close_by_peer_total 7951
telemt_me_route_drop_no_conn_total 1076593
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1792689
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9752
telemt_desync_full_logged_total 3145
telemt_desync_suppressed_total 6607
telemt_desync_frames_bucket_total{bucket="1_2"} 1861
telemt_desync_frames_bucket_total{bucket="3_10"} 3712
telemt_desync_frames_bucket_total{bucket="gt_10"} 4179
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7655
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7498
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 1791402
telemt_user_connections_current{user="hello"} 3267
telemt_user_octets_from_client{user="hello"} 23559731068 (21.94 GB)
telemt_user_octets_to_client{user="hello"} 796601069368 (741.89 GB)
telemt_user_unique_ips_current{user="hello"} 1026
telemt_user_unique_ips_recent_window{user="hello"} 462
```