# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-20 02:35:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 33467.2 (9h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 621051
telemt_connections_bad_total 39355
telemt_connections_current 729
telemt_connections_me_current 729
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10544
telemt_upstream_connect_attempt_total 6927
telemt_upstream_connect_success_total 6840
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 6927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4070
telemt_me_reconnect_success_total 4032
telemt_me_reader_eof_total 4259
telemt_me_idle_close_by_peer_total 4258
telemt_me_route_drop_no_conn_total 176853
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 495655
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2336
telemt_desync_full_logged_total 846
telemt_desync_suppressed_total 1490
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 824
telemt_desync_frames_bucket_total{bucket="gt_10"} 1033
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4065
telemt_me_writer_restored_same_endpoint_total 4019
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 497088
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 30372597940 (28.29 GB)
telemt_user_octets_to_client{user="hello"} 173829764261 (161.89 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 49921.8 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3086038
telemt_connections_bad_total 143036
telemt_connections_current 1642
telemt_connections_me_current 1642
telemt_handshake_timeouts_total 67946
telemt_upstream_connect_attempt_total 9864
telemt_upstream_connect_success_total 9695
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 9864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10220
telemt_me_reconnect_success_total 5974
telemt_me_reader_eof_total 6392
telemt_me_idle_close_by_peer_total 6392
telemt_me_route_drop_no_conn_total 1522070
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2636160
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11296
telemt_desync_full_logged_total 3730
telemt_desync_suppressed_total 7566
telemt_desync_frames_bucket_total{bucket="1_2"} 2159
telemt_desync_frames_bucket_total{bucket="3_10"} 4413
telemt_desync_frames_bucket_total{bucket="gt_10"} 4724
telemt_pool_swap_total 43
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6174
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5919
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 2635918
telemt_user_connections_current{user="hello"} 1642
telemt_user_octets_from_client{user="hello"} 40139722386 (37.38 GB)
telemt_user_octets_to_client{user="hello"} 979257977642 (912.01 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 719
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 49899.9 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3010305
telemt_connections_bad_total 477542
telemt_connections_current 1271
telemt_connections_me_current 1271
telemt_handshake_timeouts_total 46268
telemt_upstream_connect_attempt_total 8147
telemt_upstream_connect_success_total 8089
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 8147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6531
telemt_me_reconnect_success_total 5596
telemt_me_reader_eof_total 5879
telemt_me_idle_close_by_peer_total 5878
telemt_me_route_drop_no_conn_total 1935942
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2078291
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7824
telemt_desync_full_logged_total 2384
telemt_desync_suppressed_total 5440
telemt_desync_frames_bucket_total{bucket="1_2"} 1914
telemt_desync_frames_bucket_total{bucket="3_10"} 2967
telemt_desync_frames_bucket_total{bucket="gt_10"} 2943
telemt_pool_swap_total 49
telemt_me_writer_close_signal_drop_total 70
telemt_me_writer_removed_unexpected_total 5650
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5595
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 2073915
telemt_user_connections_current{user="hello"} 1271
telemt_user_octets_from_client{user="hello"} 30457448580 (28.37 GB)
telemt_user_octets_to_client{user="hello"} 798149855464 (743.33 GB)
telemt_user_unique_ips_current{user="hello"} 520
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 49887.7 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2670201
telemt_connections_bad_total 182091
telemt_connections_current 1204
telemt_connections_me_current 1204
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31845
telemt_upstream_connect_attempt_total 56008
telemt_upstream_connect_success_total 51710
telemt_upstream_connect_fail_total 4298
telemt_upstream_connect_attempts_per_request{bucket="1"} 56008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7744
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 532
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4298
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8821
telemt_me_reconnect_success_total 5970
telemt_me_reader_eof_total 6216
telemt_me_idle_close_by_peer_total 6215
telemt_me_route_drop_no_conn_total 1877478
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2182220
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8420
telemt_desync_full_logged_total 2671
telemt_desync_suppressed_total 5749
telemt_desync_frames_bucket_total{bucket="1_2"} 2069
telemt_desync_frames_bucket_total{bucket="3_10"} 3064
telemt_desync_frames_bucket_total{bucket="gt_10"} 3287
telemt_pool_swap_total 36
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6606
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5966
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 2224294
telemt_user_connections_current{user="hello"} 1204
telemt_user_octets_from_client{user="hello"} 36098836257 (33.62 GB)
telemt_user_octets_to_client{user="hello"} 628938503797 (585.74 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 103611.2 (28h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6336932
telemt_connections_bad_total 1051223
telemt_connections_current 1372
telemt_connections_me_current 1372
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 114586
telemt_upstream_connect_attempt_total 128104
telemt_upstream_connect_success_total 94816
telemt_upstream_connect_fail_total 33288
telemt_upstream_connect_attempts_per_request{bucket="1"} 128104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1436
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33288
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78988
telemt_me_reconnect_success_total 13316
telemt_me_reader_eof_total 14335
telemt_me_idle_close_by_peer_total 14321
telemt_me_route_drop_no_conn_total 2813700
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4499534
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19673
telemt_desync_full_logged_total 6239
telemt_desync_suppressed_total 13434
telemt_desync_frames_bucket_total{bucket="1_2"} 3465
telemt_desync_frames_bucket_total{bucket="3_10"} 8111
telemt_desync_frames_bucket_total{bucket="gt_10"} 8097
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 13625
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13291
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 4574756
telemt_user_connections_current{user="hello"} 1372
telemt_user_octets_from_client{user="hello"} 72984610244 (67.97 GB)
telemt_user_octets_to_client{user="hello"} 1759239292204 (1.60 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 49850.9 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 827721
telemt_connections_bad_total 80109
telemt_connections_current 467
telemt_connections_me_current 467
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13132
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 472306
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 683455
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 7605834719 (7.08 GB)
telemt_user_octets_to_client{user="hello"} 146570229222 (136.50 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 49852.3 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2078825
telemt_connections_bad_total 122898
telemt_connections_current 1344
telemt_connections_me_current 1344
telemt_handshake_timeouts_total 38267
telemt_upstream_connect_attempt_total 8987
telemt_upstream_connect_success_total 8925
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 8987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4084
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6467
telemt_me_reconnect_success_total 6422
telemt_me_reader_eof_total 6782
telemt_me_idle_close_by_peer_total 6782
telemt_me_route_drop_no_conn_total 755964
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1776079
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9332
telemt_desync_full_logged_total 3007
telemt_desync_suppressed_total 6325
telemt_desync_frames_bucket_total{bucket="1_2"} 1774
telemt_desync_frames_bucket_total{bucket="3_10"} 3265
telemt_desync_frames_bucket_total{bucket="gt_10"} 4293
telemt_pool_swap_total 50
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6515
telemt_me_writer_restored_same_endpoint_total 6405
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 1775187
telemt_user_connections_current{user="hello"} 1344
telemt_user_octets_from_client{user="hello"} 30259260668 (28.18 GB)
telemt_user_octets_to_client{user="hello"} 906084986252 (843.86 GB)
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 139
```