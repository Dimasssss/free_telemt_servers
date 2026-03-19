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

# Server Metrics 2026-03-19 10:54:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 47180.8 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090739
telemt_connections_bad_total 93629
telemt_connections_current 1500
telemt_connections_me_current 1500
telemt_handshake_timeouts_total 38544
telemt_upstream_connect_attempt_total 9026
telemt_upstream_connect_success_total 8866
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 9026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 7651
telemt_me_reconnect_success_total 6486
telemt_me_reader_eof_total 6849
telemt_me_idle_close_by_peer_total 6846
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 420153
telemt_me_route_drop_channel_closed_total 165
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 846081
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4755
telemt_desync_full_logged_total 1463
telemt_desync_suppressed_total 3292
telemt_desync_frames_bucket_total{bucket="1_2"} 1568
telemt_desync_frames_bucket_total{bucket="3_10"} 1733
telemt_desync_frames_bucket_total{bucket="gt_10"} 1454
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6616
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 6465
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 840034
telemt_user_connections_current{user="hello"} 1500
telemt_user_octets_from_client{user="hello"} 12612888956 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 260242562428 (242.37 GB)
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 47185.9 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2788965
telemt_connections_bad_total 166935
telemt_connections_current 4302
telemt_connections_me_current 4302
telemt_handshake_timeouts_total 56062
telemt_upstream_connect_attempt_total 9013
telemt_upstream_connect_success_total 8847
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 9013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4364
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 11205
telemt_me_reconnect_success_total 6447
telemt_me_reader_eof_total 6913
telemt_me_idle_close_by_peer_total 6912
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1666617
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2337510
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9933
telemt_desync_full_logged_total 3317
telemt_desync_suppressed_total 6616
telemt_desync_frames_bucket_total{bucket="1_2"} 1890
telemt_desync_frames_bucket_total{bucket="3_10"} 3901
telemt_desync_frames_bucket_total{bucket="gt_10"} 4142
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6712
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 6425
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 2337173
telemt_user_connections_current{user="hello"} 4302
telemt_user_octets_from_client{user="hello"} 33895563844 (31.57 GB)
telemt_user_octets_to_client{user="hello"} 780106164720 (726.53 GB)
telemt_user_unique_ips_current{user="hello"} 1402
telemt_user_unique_ips_recent_window{user="hello"} 1001
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 47183.4 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2300396
telemt_connections_bad_total 266990
telemt_connections_current 2970
telemt_connections_me_current 2970
telemt_handshake_timeouts_total 50038
telemt_upstream_connect_attempt_total 8463
telemt_upstream_connect_success_total 8463
telemt_upstream_connect_attempts_per_request{bucket="1"} 8463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4009
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 6098
telemt_me_reconnect_success_total 6056
telemt_me_reader_eof_total 6399
telemt_me_idle_close_by_peer_total 6399
telemt_me_route_drop_no_conn_total 1424027
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1810419
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7708
telemt_desync_full_logged_total 2455
telemt_desync_suppressed_total 5253
telemt_desync_frames_bucket_total{bucket="1_2"} 1712
telemt_desync_frames_bucket_total{bucket="3_10"} 2839
telemt_desync_frames_bucket_total{bucket="gt_10"} 3157
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6162
telemt_me_writer_restored_same_endpoint_total 6040
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 1808745
telemt_user_connections_current{user="hello"} 2970
telemt_user_octets_from_client{user="hello"} 25605785396 (23.85 GB)
telemt_user_octets_to_client{user="hello"} 776077306388 (722.78 GB)
telemt_user_unique_ips_current{user="hello"} 1045
telemt_user_unique_ips_recent_window{user="hello"} 449
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 47236.2 (13h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2284014
telemt_connections_bad_total 124148
telemt_connections_current 3128
telemt_connections_me_current 3128
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 59998
telemt_upstream_connect_attempt_total 16786
telemt_upstream_connect_success_total 16620
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 16786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9393
telemt_me_reconnect_success_total 6060
telemt_me_reader_eof_total 6433
telemt_me_idle_close_by_peer_total 6432
telemt_me_route_drop_no_conn_total 1152300
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1732166
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6334
telemt_desync_full_logged_total 2148
telemt_desync_suppressed_total 4186
telemt_desync_frames_bucket_total{bucket="1_2"} 1338
telemt_desync_frames_bucket_total{bucket="3_10"} 2462
telemt_desync_frames_bucket_total{bucket="gt_10"} 2534
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6489
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 6036
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 1738355
telemt_user_connections_current{user="hello"} 3128
telemt_user_octets_from_client{user="hello"} 19832877364 (18.47 GB)
telemt_user_octets_to_client{user="hello"} 501592338830 (467.14 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1034
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 47179.4 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2718724
telemt_connections_bad_total 604268
telemt_connections_current 3285
telemt_connections_me_current 3285
telemt_handshake_timeouts_total 53767
telemt_upstream_connect_attempt_total 8346
telemt_upstream_connect_success_total 8289
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 8346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7103
telemt_me_reconnect_success_total 5903
telemt_me_reader_eof_total 6269
telemt_me_idle_close_by_peer_total 6268
telemt_me_route_drop_no_conn_total 1004544
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1798614
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7944
telemt_desync_full_logged_total 2477
telemt_desync_suppressed_total 5467
telemt_desync_frames_bucket_total{bucket="1_2"} 1554
telemt_desync_frames_bucket_total{bucket="3_10"} 3418
telemt_desync_frames_bucket_total{bucket="gt_10"} 2972
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6027
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5879
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 1797669
telemt_user_connections_current{user="hello"} 3285
telemt_user_octets_from_client{user="hello"} 32046397536 (29.85 GB)
telemt_user_octets_to_client{user="hello"} 739942881552 (689.13 GB)
telemt_user_unique_ips_current{user="hello"} 1137
telemt_user_unique_ips_recent_window{user="hello"} 508
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 47192.3 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474480
telemt_connections_bad_total 18343
telemt_connections_current 885
telemt_connections_me_current 885
telemt_handshake_timeouts_total 3732
telemt_upstream_connect_attempt_total 11857
telemt_upstream_connect_success_total 11557
telemt_upstream_connect_fail_total 300
telemt_upstream_connect_attempts_per_request{bucket="1"} 11857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 300
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 15586
telemt_me_reconnect_success_total 9169
telemt_me_reader_eof_total 9740
telemt_me_idle_close_by_peer_total 9740
telemt_me_route_drop_no_conn_total 243521
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428834
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 881
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 582
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 350
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9447
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 9139
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 428784
telemt_user_connections_current{user="hello"} 885
telemt_user_octets_from_client{user="hello"} 6994529160 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 162766146688 (151.59 GB)
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 47182.0 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1840964
telemt_connections_bad_total 162327
telemt_connections_current 3259
telemt_connections_me_current 3259
telemt_handshake_timeouts_total 70940
telemt_upstream_connect_attempt_total 9532
telemt_upstream_connect_success_total 9531
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8492
telemt_me_reconnect_success_total 7136
telemt_me_reader_eof_total 7559
telemt_me_idle_close_by_peer_total 7558
telemt_me_route_drop_no_conn_total 711422
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1518541
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8691
telemt_desync_full_logged_total 2803
telemt_desync_suppressed_total 5888
telemt_desync_frames_bucket_total{bucket="1_2"} 1644
telemt_desync_frames_bucket_total{bucket="3_10"} 3296
telemt_desync_frames_bucket_total{bucket="gt_10"} 3751
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7268
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7121
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 1517283
telemt_user_connections_current{user="hello"} 3259
telemt_user_octets_from_client{user="hello"} 21531714560 (20.05 GB)
telemt_user_octets_to_client{user="hello"} 720998203336 (671.48 GB)
telemt_user_unique_ips_current{user="hello"} 1067
telemt_user_unique_ips_recent_window{user="hello"} 444
```