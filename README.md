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

# Server Metrics 2026-03-20 01:54:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 31018.9 (8h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582557
telemt_connections_bad_total 37368
telemt_connections_current 760
telemt_connections_me_current 760
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9169
telemt_upstream_connect_attempt_total 6530
telemt_upstream_connect_success_total 6445
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 6530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3804
telemt_me_reconnect_success_total 3769
telemt_me_reader_eof_total 3977
telemt_me_idle_close_by_peer_total 3976
telemt_me_route_drop_no_conn_total 166527
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465074
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2159
telemt_desync_full_logged_total 778
telemt_desync_suppressed_total 1381
telemt_desync_frames_bucket_total{bucket="1_2"} 436
telemt_desync_frames_bucket_total{bucket="3_10"} 745
telemt_desync_frames_bucket_total{bucket="gt_10"} 978
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3796
telemt_me_writer_restored_same_endpoint_total 3756
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 466502
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 29889388900 (27.84 GB)
telemt_user_octets_to_client{user="hello"} 164678715209 (153.37 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 47473.6 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3018098
telemt_connections_bad_total 126911
telemt_connections_current 1437
telemt_connections_me_current 1437
telemt_handshake_timeouts_total 66537
telemt_upstream_connect_attempt_total 9419
telemt_upstream_connect_success_total 9262
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 9419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9916
telemt_me_reconnect_success_total 5673
telemt_me_reader_eof_total 6069
telemt_me_idle_close_by_peer_total 6069
telemt_me_route_drop_no_conn_total 1507837
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2587130
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11221
telemt_desync_full_logged_total 3693
telemt_desync_suppressed_total 7528
telemt_desync_frames_bucket_total{bucket="1_2"} 2144
telemt_desync_frames_bucket_total{bucket="3_10"} 4387
telemt_desync_frames_bucket_total{bucket="gt_10"} 4690
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5869
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5618
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 2586909
telemt_user_connections_current{user="hello"} 1437
telemt_user_octets_from_client{user="hello"} 39490842810 (36.78 GB)
telemt_user_octets_to_client{user="hello"} 952170663974 (886.78 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 653
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 47451.6 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2967619
telemt_connections_bad_total 476662
telemt_connections_current 1106
telemt_connections_me_current 1106
telemt_handshake_timeouts_total 43944
telemt_upstream_connect_attempt_total 7670
telemt_upstream_connect_success_total 7612
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 7670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6183
telemt_me_reconnect_success_total 5250
telemt_me_reader_eof_total 5510
telemt_me_idle_close_by_peer_total 5509
telemt_me_route_drop_no_conn_total 1924615
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2045296
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7671
telemt_desync_full_logged_total 2330
telemt_desync_suppressed_total 5341
telemt_desync_frames_bucket_total{bucket="1_2"} 1891
telemt_desync_frames_bucket_total{bucket="3_10"} 2920
telemt_desync_frames_bucket_total{bucket="gt_10"} 2860
telemt_pool_swap_total 46
telemt_me_writer_close_signal_drop_total 70
telemt_me_writer_removed_unexpected_total 5302
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5249
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 2040918
telemt_user_connections_current{user="hello"} 1106
telemt_user_octets_from_client{user="hello"} 30142418284 (28.07 GB)
telemt_user_octets_to_client{user="hello"} 785524810260 (731.58 GB)
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 47439.5 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2584990
telemt_connections_bad_total 135163
telemt_connections_current 1065
telemt_connections_me_current 1065
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31339
telemt_upstream_connect_attempt_total 55589
telemt_upstream_connect_success_total 51308
telemt_upstream_connect_fail_total 4281
telemt_upstream_connect_attempts_per_request{bucket="1"} 55589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7555
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4281
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8541
telemt_me_reconnect_success_total 5699
telemt_me_reader_eof_total 5927
telemt_me_idle_close_by_peer_total 5926
telemt_me_route_drop_no_conn_total 1866982
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2149348
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8360
telemt_desync_full_logged_total 2641
telemt_desync_suppressed_total 5719
telemt_desync_frames_bucket_total{bucket="1_2"} 2062
telemt_desync_frames_bucket_total{bucket="3_10"} 3038
telemt_desync_frames_bucket_total{bucket="gt_10"} 3260
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 477
telemt_me_writer_removed_unexpected_total 6327
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5695
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 2191419
telemt_user_connections_current{user="hello"} 1065
telemt_user_octets_from_client{user="hello"} 35708508461 (33.26 GB)
telemt_user_octets_to_client{user="hello"} 617241669357 (574.85 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 101162.8 (28h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6289006
telemt_connections_bad_total 1044966
telemt_connections_current 1319
telemt_connections_me_current 1319
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 113793
telemt_upstream_connect_attempt_total 127644
telemt_upstream_connect_success_total 94358
telemt_upstream_connect_fail_total 33286
telemt_upstream_connect_attempts_per_request{bucket="1"} 127644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33286
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78659
telemt_me_reconnect_success_total 12988
telemt_me_reader_eof_total 13991
telemt_me_idle_close_by_peer_total 13977
telemt_me_route_drop_no_conn_total 2801334
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4459855
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
telemt_desync_total 19570
telemt_desync_full_logged_total 6202
telemt_desync_suppressed_total 13368
telemt_desync_frames_bucket_total{bucket="1_2"} 3447
telemt_desync_frames_bucket_total{bucket="3_10"} 8055
telemt_desync_frames_bucket_total{bucket="gt_10"} 8068
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 13298
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12963
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 4535068
telemt_user_connections_current{user="hello"} 1319
telemt_user_octets_from_client{user="hello"} 72598884320 (67.61 GB)
telemt_user_octets_to_client{user="hello"} 1743709240484 (1.59 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 541
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 47402.6 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 720798
telemt_connections_bad_total 77190
telemt_connections_current 374
telemt_connections_me_current 374
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13063
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
telemt_me_route_drop_no_conn_total 471072
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
telemt_user_connections_total{user="hello"} 580151
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 7394362631 (6.89 GB)
telemt_user_octets_to_client{user="hello"} 146467914230 (136.41 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 47404.0 (13h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2035327
telemt_connections_bad_total 120279
telemt_connections_current 1229
telemt_connections_me_current 1229
telemt_handshake_timeouts_total 37738
telemt_upstream_connect_attempt_total 8485
telemt_upstream_connect_success_total 8425
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6096
telemt_me_reconnect_success_total 6053
telemt_me_reader_eof_total 6390
telemt_me_idle_close_by_peer_total 6390
telemt_me_route_drop_no_conn_total 745768
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1748450
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9269
telemt_desync_full_logged_total 2982
telemt_desync_suppressed_total 6287
telemt_desync_frames_bucket_total{bucket="1_2"} 1751
telemt_desync_frames_bucket_total{bucket="3_10"} 3251
telemt_desync_frames_bucket_total{bucket="gt_10"} 4267
telemt_pool_swap_total 47
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6144
telemt_me_writer_restored_same_endpoint_total 6036
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 1747557
telemt_user_connections_current{user="hello"} 1229
telemt_user_octets_from_client{user="hello"} 29903998300 (27.85 GB)
telemt_user_octets_to_client{user="hello"} 886689383324 (825.79 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 104
```