# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 23:54:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 96496.1 (26h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3422465
telemt_connections_bad_total 285203
telemt_connections_current 650
telemt_connections_me_current 650
telemt_handshake_timeouts_total 107500
telemt_upstream_connect_attempt_total 35674
telemt_upstream_connect_success_total 35673
telemt_upstream_connect_attempts_per_request{bucket="1"} 35673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23186
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1368
telemt_me_reconnect_success_total 577
telemt_me_reader_eof_total 593
telemt_me_idle_close_by_peer_total 593
telemt_me_route_drop_no_conn_total 2972989
telemt_me_route_drop_channel_closed_total 1230
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2844077
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 669
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 750
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 12204
telemt_desync_full_logged_total 3825
telemt_desync_suppressed_total 8379
telemt_desync_frames_bucket_total{bucket="1_2"} 3304
telemt_desync_frames_bucket_total{bucket="3_10"} 4442
telemt_desync_frames_bucket_total{bucket="gt_10"} 4458
telemt_pool_swap_total 107
telemt_pool_force_close_total 3324
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 646
telemt_me_draining_writers_reap_progress_total 32672
telemt_me_writer_removed_unexpected_total 572
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2380
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30511
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29348
telemt_me_writer_teardown_success_total{mode="normal"} 32891
telemt_me_writer_teardown_noop_total 32683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65574
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 375.327792
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65574
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 646
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 515
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2833321
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 40657214032 (37.86 GB)
telemt_user_octets_to_client{user="hello"} 773786308916 (720.64 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 266
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 109862.0 (30h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3975790
telemt_connections_bad_total 362029
telemt_connections_current 409
telemt_connections_me_current 409
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100277
telemt_upstream_connect_attempt_total 67925
telemt_upstream_connect_success_total 67105
telemt_upstream_connect_fail_total 726
telemt_upstream_connect_attempts_per_request{bucket="1"} 67831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 726
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9754
telemt_me_reconnect_success_total 3535
telemt_me_reader_eof_total 3540
telemt_me_idle_close_by_peer_total 3540
telemt_me_route_drop_no_conn_total 3638614
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3162102
telemt_me_endpoint_quarantine_total 836
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 853
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 17
telemt_desync_total 12912
telemt_desync_full_logged_total 7235
telemt_desync_suppressed_total 5677
telemt_desync_frames_bucket_total{bucket="1_2"} 2932
telemt_desync_frames_bucket_total{bucket="3_10"} 5061
telemt_desync_frames_bucket_total{bucket="gt_10"} 4919
telemt_pool_swap_total 101
telemt_pool_force_close_total 2993
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 44575
telemt_me_writer_removed_unexpected_total 3474
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6004
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42074
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2535
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41582
telemt_me_writer_teardown_success_total{mode="normal"} 48078
telemt_me_writer_teardown_noop_total 44576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92654
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.555149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92654
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 238
telemt_me_writer_restored_same_endpoint_total 3176
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 3174586
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 42891478986 (39.95 GB)
telemt_user_octets_to_client{user="hello"} 787072641288 (733.02 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 184722.0 (51h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16283448
telemt_connections_bad_total 1638274
telemt_connections_current 753
telemt_connections_me_current 753
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396739
telemt_upstream_connect_attempt_total 82405
telemt_upstream_connect_success_total 82302
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 82319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40103
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1709
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2961
telemt_me_reconnect_success_total 1539
telemt_me_reader_eof_total 1486
telemt_me_idle_close_by_peer_total 1484
telemt_me_route_drop_no_conn_total 14039271
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12935312
telemt_me_endpoint_quarantine_total 1213
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1385
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 53546
telemt_desync_full_logged_total 16992
telemt_desync_suppressed_total 36554
telemt_desync_frames_bucket_total{bucket="1_2"} 11915
telemt_desync_frames_bucket_total{bucket="3_10"} 20873
telemt_desync_frames_bucket_total{bucket="gt_10"} 20758
telemt_pool_swap_total 200
telemt_pool_force_close_total 6623
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1055
telemt_me_draining_writers_reap_progress_total 62029
telemt_me_writer_removed_unexpected_total 1432
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5347
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57387
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6153
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55406
telemt_me_writer_teardown_success_total{mode="normal"} 62734
telemt_me_writer_teardown_noop_total 62082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124816
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.531630
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124816
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1055
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1331
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 12935377
telemt_user_connections_current{user="hello"} 753
telemt_user_octets_from_client{user="hello"} 190814676901 (177.71 GB)
telemt_user_octets_to_client{user="hello"} 3480015225279 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 184723.1 (51h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11824415
telemt_connections_bad_total 1222096
telemt_connections_current 509
telemt_connections_me_current 509
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344343
telemt_upstream_connect_attempt_total 96821
telemt_upstream_connect_success_total 95507
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 96372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4358
telemt_me_reconnect_success_total 1845
telemt_me_reader_eof_total 1710
telemt_me_idle_close_by_peer_total 1710
telemt_me_route_drop_no_conn_total 4549837
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8784263
telemt_me_endpoint_quarantine_total 1219
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1408
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 38654
telemt_desync_full_logged_total 13010
telemt_desync_suppressed_total 25644
telemt_desync_frames_bucket_total{bucket="1_2"} 9562
telemt_desync_frames_bucket_total{bucket="3_10"} 14851
telemt_desync_frames_bucket_total{bucket="gt_10"} 14241
telemt_pool_swap_total 197
telemt_pool_force_close_total 5982
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 707
telemt_me_draining_writers_reap_progress_total 60312
telemt_me_writer_removed_unexpected_total 1741
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5463
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56445
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5470
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54330
telemt_me_writer_teardown_success_total{mode="normal"} 61908
telemt_me_writer_teardown_noop_total 60337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122245
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.372736
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122245
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 707
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1576
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8722056
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 217613956192 (202.67 GB)
telemt_user_octets_to_client{user="hello"} 3948831839231 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 184687.2 (51h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11014895
telemt_connections_bad_total 966743
telemt_connections_current 627
telemt_connections_me_current 627
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345282
telemt_upstream_connect_attempt_total 81012
telemt_upstream_connect_success_total 79458
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 79663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38418
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5688
telemt_me_reconnect_success_total 2333
telemt_me_reader_eof_total 2074
telemt_me_idle_close_by_peer_total 2073
telemt_me_route_drop_no_conn_total 5332221
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8331179
telemt_me_endpoint_quarantine_total 1294
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1360
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 37961
telemt_desync_full_logged_total 12588
telemt_desync_suppressed_total 25373
telemt_desync_frames_bucket_total{bucket="1_2"} 9587
telemt_desync_frames_bucket_total{bucket="3_10"} 14514
telemt_desync_frames_bucket_total{bucket="gt_10"} 13860
telemt_pool_swap_total 193
telemt_pool_force_close_total 5868
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 736
telemt_me_draining_writers_reap_progress_total 60588
telemt_me_writer_removed_unexpected_total 2227
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6200
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56544
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5297
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54720
telemt_me_writer_teardown_success_total{mode="normal"} 62744
telemt_me_writer_teardown_noop_total 60659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123403
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.665491
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123403
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 736
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2024
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8323161
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 192506259451 (179.29 GB)
telemt_user_octets_to_client{user="hello"} 3459673631809 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 54967.3 (15h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11171373
telemt_connections_bad_total 668045
telemt_connections_current 972
telemt_connections_me_current 972
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 263233
telemt_upstream_connect_attempt_total 55066
telemt_upstream_connect_success_total 52233
telemt_upstream_connect_fail_total 1900
telemt_upstream_connect_attempts_per_request{bucket="1"} 54133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17724
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6003
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1900
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7450
telemt_me_reconnect_success_total 1146
telemt_me_reader_eof_total 721
telemt_me_idle_close_by_peer_total 720
telemt_me_route_drop_no_conn_total 25277631
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9278510
telemt_me_endpoint_quarantine_total 393
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 432
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_me_writers_warm_current 26
telemt_desync_total 16209
telemt_desync_full_logged_total 4390
telemt_desync_suppressed_total 11819
telemt_desync_frames_bucket_total{bucket="1_2"} 3073
telemt_desync_frames_bucket_total{bucket="3_10"} 6577
telemt_desync_frames_bucket_total{bucket="gt_10"} 6559
telemt_pool_swap_total 56
telemt_pool_force_close_total 1890
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 470
telemt_me_draining_writers_reap_progress_total 16749
telemt_me_writer_removed_unexpected_total 1037
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2310
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15417
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1583
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14859
telemt_me_writer_teardown_success_total{mode="normal"} 17727
telemt_me_writer_teardown_noop_total 16768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34495
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.526899
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34495
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 470
telemt_me_refill_failed_total 336
telemt_me_writer_restored_same_endpoint_total 744
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 9303972
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 86507273490 (80.57 GB)
telemt_user_octets_to_client{user="hello"} 593432782305 (552.68 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 184693.8 (51h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10950965
telemt_connections_bad_total 941647
telemt_connections_current 691
telemt_connections_me_current 691
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241668
telemt_upstream_connect_attempt_total 109902
telemt_upstream_connect_success_total 108765
telemt_upstream_connect_fail_total 965
telemt_upstream_connect_attempts_per_request{bucket="1"} 109730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 965
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72811
telemt_me_reconnect_success_total 3019
telemt_me_reader_eof_total 2711
telemt_me_idle_close_by_peer_total 2709
telemt_me_route_drop_no_conn_total 5254892
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8642104
telemt_me_endpoint_quarantine_total 1232
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1390
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 46109
telemt_desync_full_logged_total 15780
telemt_desync_suppressed_total 30329
telemt_desync_frames_bucket_total{bucket="1_2"} 9369
telemt_desync_frames_bucket_total{bucket="3_10"} 17650
telemt_desync_frames_bucket_total{bucket="gt_10"} 19090
telemt_pool_swap_total 189
telemt_pool_force_close_total 5565
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 64743
telemt_me_writer_removed_unexpected_total 2742
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6696
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60822
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4816
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59178
telemt_me_writer_teardown_success_total{mode="normal"} 67518
telemt_me_writer_teardown_noop_total 64744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132262
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.206430
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132262
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2550
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8645156
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 194232550413 (180.89 GB)
telemt_user_octets_to_client{user="hello"} 3300384102952 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 121530.1 (33h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11644562
telemt_connections_bad_total 476129
telemt_connections_current 543
telemt_connections_me_current 543
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4758211
telemt_upstream_connect_attempt_total 57996
telemt_upstream_connect_success_total 57574
telemt_upstream_connect_fail_total 411
telemt_upstream_connect_attempts_per_request{bucket="1"} 57985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 411
telemt_me_reconnect_attempts_total 48806
telemt_me_reconnect_success_total 1770
telemt_me_reader_eof_total 1440
telemt_me_idle_close_by_peer_total 1439
telemt_me_route_drop_no_conn_total 4081443
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5593664
telemt_me_endpoint_quarantine_total 803
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 926
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 3
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31462
telemt_desync_full_logged_total 10720
telemt_desync_suppressed_total 20742
telemt_desync_frames_bucket_total{bucket="1_2"} 6265
telemt_desync_frames_bucket_total{bucket="3_10"} 12409
telemt_desync_frames_bucket_total{bucket="gt_10"} 12788
telemt_pool_swap_total 128
telemt_pool_force_close_total 3805
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 374
telemt_me_draining_writers_reap_progress_total 43779
telemt_me_writer_removed_unexpected_total 1491
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3670
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41643
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3364
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39974
telemt_me_writer_teardown_success_total{mode="normal"} 45313
telemt_me_writer_teardown_noop_total 43786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89099
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.650292
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89099
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 374
telemt_me_refill_failed_total 2733
telemt_me_writer_restored_same_endpoint_total 1572
telemt_me_writer_restored_fallback_total 23
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5586249
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 118884465932 (110.72 GB)
telemt_user_octets_to_client{user="hello"} 2162289622762 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 102501.0 (28h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1495527
telemt_connections_bad_total 36635
telemt_connections_current 421
telemt_connections_me_current 421
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29920
telemt_upstream_connect_attempt_total 47914
telemt_upstream_connect_success_total 47763
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 47886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 781
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2165
telemt_me_reconnect_success_total 881
telemt_me_reader_eof_total 861
telemt_me_idle_close_by_peer_total 861
telemt_me_route_drop_no_conn_total 512878
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1328308
telemt_me_endpoint_quarantine_total 826
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 845
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 8578
telemt_desync_full_logged_total 2554
telemt_desync_suppressed_total 6024
telemt_desync_frames_bucket_total{bucket="1_2"} 2272
telemt_desync_frames_bucket_total{bucket="3_10"} 3300
telemt_desync_frames_bucket_total{bucket="gt_10"} 3006
telemt_pool_swap_total 110
telemt_pool_force_close_total 2850
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 40339
telemt_me_writer_removed_unexpected_total 833
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3148
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38059
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2762
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37489
telemt_me_writer_teardown_success_total{mode="normal"} 41207
telemt_me_writer_teardown_noop_total 40343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81550
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.123466
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81550
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 748
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 1324155
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 25770319369 (24.00 GB)
telemt_user_octets_to_client{user="hello"} 569825127647 (530.69 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 184698.5 (51h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13279293
telemt_connections_bad_total 1587565
telemt_connections_current 338
telemt_connections_me_current 338
telemt_handshake_timeouts_total 385710
telemt_upstream_connect_attempt_total 71756
telemt_upstream_connect_success_total 71411
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 71620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2891
telemt_me_reconnect_success_total 1442
telemt_me_reader_eof_total 1425
telemt_me_idle_close_by_peer_total 1425
telemt_me_route_drop_no_conn_total 4478602
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10021026
telemt_me_endpoint_quarantine_total 1290
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1393
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 41882
telemt_desync_full_logged_total 13674
telemt_desync_suppressed_total 28208
telemt_desync_frames_bucket_total{bucket="1_2"} 10080
telemt_desync_frames_bucket_total{bucket="3_10"} 15400
telemt_desync_frames_bucket_total{bucket="gt_10"} 16402
telemt_pool_swap_total 205
telemt_pool_force_close_total 5520
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 64797
telemt_me_writer_removed_unexpected_total 1365
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5164
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61048
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5346
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59277
telemt_me_writer_teardown_success_total{mode="normal"} 66212
telemt_me_writer_teardown_noop_total 64799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 130878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 130998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131011
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.738088
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131011
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1264
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 9987759
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 194423849860 (181.07 GB)
telemt_user_octets_to_client{user="hello"} 4431425024300 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 184694.9 (51h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11567247
telemt_connections_bad_total 1330362
telemt_connections_current 593
telemt_connections_me_current 593
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 308958
telemt_upstream_connect_attempt_total 98457
telemt_upstream_connect_success_total 97582
telemt_upstream_connect_fail_total 667
telemt_upstream_connect_attempts_per_request{bucket="1"} 98249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 667
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10319
telemt_me_reconnect_success_total 2532
telemt_me_reader_eof_total 2352
telemt_me_idle_close_by_peer_total 2351
telemt_me_seq_mismatch_total 92
telemt_me_route_drop_no_conn_total 5638857
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8926317
telemt_me_endpoint_quarantine_total 1471
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1395
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 33
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 41644
telemt_desync_full_logged_total 13376
telemt_desync_suppressed_total 28268
telemt_desync_frames_bucket_total{bucket="1_2"} 10745
telemt_desync_frames_bucket_total{bucket="3_10"} 15305
telemt_desync_frames_bucket_total{bucket="gt_10"} 15594
telemt_pool_swap_total 195
telemt_pool_force_close_total 5300
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 658
telemt_me_draining_writers_reap_progress_total 64773
telemt_me_writer_removed_unexpected_total 2390
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6524
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60722
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4829
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59473
telemt_me_writer_teardown_success_total{mode="normal"} 67246
telemt_me_writer_teardown_noop_total 64778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132024
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.434227
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132024
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 658
telemt_me_refill_failed_total 403
telemt_me_writer_restored_same_endpoint_total 2045
telemt_me_writer_restored_fallback_total 127
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 8931660
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 157107670069 (146.32 GB)
telemt_user_octets_to_client{user="hello"} 3475326760199 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 83
```