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

# Server Metrics 2026-03-22 23:19:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 94359.5 (26h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3379573
telemt_connections_bad_total 272349
telemt_connections_current 822
telemt_connections_me_current 822
telemt_handshake_timeouts_total 106708
telemt_upstream_connect_attempt_total 34735
telemt_upstream_connect_success_total 34734
telemt_upstream_connect_attempts_per_request{bucket="1"} 34734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1357
telemt_me_reconnect_success_total 565
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_route_drop_no_conn_total 2968226
telemt_me_route_drop_channel_closed_total 1230
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2818401
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 642
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 734
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 12039
telemt_desync_full_logged_total 3778
telemt_desync_suppressed_total 8261
telemt_desync_frames_bucket_total{bucket="1_2"} 3242
telemt_desync_frames_bucket_total{bucket="3_10"} 4398
telemt_desync_frames_bucket_total{bucket="gt_10"} 4399
telemt_pool_swap_total 104
telemt_pool_force_close_total 3227
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 636
telemt_me_draining_writers_reap_progress_total 31792
telemt_me_writer_removed_unexpected_total 561
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29707
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3171
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28565
telemt_me_writer_teardown_success_total{mode="normal"} 32021
telemt_me_writer_teardown_noop_total 31803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63824
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.898152
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63824
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 636
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 504
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2807690
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 40101321316 (37.35 GB)
telemt_user_octets_to_client{user="hello"} 763146318676 (710.74 GB)
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 107725.6 (29h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3965135
telemt_connections_bad_total 360641
telemt_connections_current 369
telemt_connections_me_current 369
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100062
telemt_upstream_connect_attempt_total 66656
telemt_upstream_connect_success_total 65850
telemt_upstream_connect_fail_total 714
telemt_upstream_connect_attempts_per_request{bucket="1"} 66564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28678
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 714
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9585
telemt_me_reconnect_success_total 3503
telemt_me_reader_eof_total 3510
telemt_me_idle_close_by_peer_total 3510
telemt_me_route_drop_no_conn_total 3637080
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3153260
telemt_me_endpoint_quarantine_total 815
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 836
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_active_current 45
telemt_desync_total 12868
telemt_desync_full_logged_total 7208
telemt_desync_suppressed_total 5660
telemt_desync_frames_bucket_total{bucket="1_2"} 2912
telemt_desync_frames_bucket_total{bucket="3_10"} 5049
telemt_desync_frames_bucket_total{bucket="gt_10"} 4907
telemt_pool_swap_total 99
telemt_pool_force_close_total 2959
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 243
telemt_me_draining_writers_reap_progress_total 43434
telemt_me_writer_removed_unexpected_total 3445
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5929
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40978
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2501
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40475
telemt_me_writer_teardown_success_total{mode="normal"} 46907
telemt_me_writer_teardown_noop_total 43435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90342
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.534975
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90342
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 243
telemt_me_refill_failed_total 230
telemt_me_writer_restored_same_endpoint_total 3155
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 3165757
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 42791881198 (39.85 GB)
telemt_user_octets_to_client{user="hello"} 782257345872 (728.53 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 182585.4 (50h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16253535
telemt_connections_bad_total 1628416
telemt_connections_current 1052
telemt_connections_me_current 1052
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396485
telemt_upstream_connect_attempt_total 81229
telemt_upstream_connect_success_total 81129
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 81146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39415
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1704
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2921
telemt_me_reconnect_success_total 1519
telemt_me_reader_eof_total 1464
telemt_me_idle_close_by_peer_total 1462
telemt_me_route_drop_no_conn_total 14035281
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12915899
telemt_me_endpoint_quarantine_total 1180
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1366
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53380
telemt_desync_full_logged_total 16938
telemt_desync_suppressed_total 36442
telemt_desync_frames_bucket_total{bucket="1_2"} 11865
telemt_desync_frames_bucket_total{bucket="3_10"} 20789
telemt_desync_frames_bucket_total{bucket="gt_10"} 20726
telemt_pool_swap_total 197
telemt_pool_force_close_total 6555
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1049
telemt_me_draining_writers_reap_progress_total 60950
telemt_me_writer_removed_unexpected_total 1411
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5269
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56364
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6085
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54395
telemt_me_writer_teardown_success_total{mode="normal"} 61633
telemt_me_writer_teardown_noop_total 61003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122636
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.401364
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122636
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1049
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1312
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 12916110
telemt_user_connections_current{user="hello"} 1052
telemt_user_octets_from_client{user="hello"} 190531931349 (177.45 GB)
telemt_user_octets_to_client{user="hello"} 3473263807915 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 182586.8 (50h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11796965
telemt_connections_bad_total 1216797
telemt_connections_current 644
telemt_connections_me_current 644
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344190
telemt_upstream_connect_attempt_total 95712
telemt_upstream_connect_success_total 94399
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 95264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39351
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3797
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4342
telemt_me_reconnect_success_total 1831
telemt_me_reader_eof_total 1693
telemt_me_idle_close_by_peer_total 1693
telemt_me_route_drop_no_conn_total 4547358
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8768011
telemt_me_endpoint_quarantine_total 1190
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1388
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_me_writers_active_current 44
telemt_desync_total 38629
telemt_desync_full_logged_total 13001
telemt_desync_suppressed_total 25628
telemt_desync_frames_bucket_total{bucket="1_2"} 9553
telemt_desync_frames_bucket_total{bucket="3_10"} 14844
telemt_desync_frames_bucket_total{bucket="gt_10"} 14232
telemt_pool_swap_total 194
telemt_pool_force_close_total 5920
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 59292
telemt_me_writer_removed_unexpected_total 1727
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5396
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55475
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5408
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53372
telemt_me_writer_teardown_success_total{mode="normal"} 60871
telemt_me_writer_teardown_noop_total 59317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120188
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.280084
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120188
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1562
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8705819
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 217464986944 (202.53 GB)
telemt_user_octets_to_client{user="hello"} 3943444364339 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 182550.8 (50h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10993665
telemt_connections_bad_total 961283
telemt_connections_current 530
telemt_connections_me_current 530
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345109
telemt_upstream_connect_attempt_total 79818
telemt_upstream_connect_success_total 78266
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 78471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5667
telemt_me_reconnect_success_total 2314
telemt_me_reader_eof_total 2054
telemt_me_idle_close_by_peer_total 2053
telemt_me_route_drop_no_conn_total 5329474
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8317104
telemt_me_endpoint_quarantine_total 1269
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1345
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_me_writers_active_current 47
telemt_desync_total 37920
telemt_desync_full_logged_total 12572
telemt_desync_suppressed_total 25348
telemt_desync_frames_bucket_total{bucket="1_2"} 9578
telemt_desync_frames_bucket_total{bucket="3_10"} 14502
telemt_desync_frames_bucket_total{bucket="gt_10"} 13840
telemt_pool_swap_total 190
telemt_pool_force_close_total 5827
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 736
telemt_me_draining_writers_reap_progress_total 59499
telemt_me_writer_removed_unexpected_total 2208
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6123
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55512
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5256
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53672
telemt_me_writer_teardown_success_total{mode="normal"} 61635
telemt_me_writer_teardown_noop_total 59570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121205
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.650529
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121205
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 736
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2005
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8309098
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 192326877811 (179.12 GB)
telemt_user_octets_to_client{user="hello"} 3456676693845 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 52831.0 (14h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11138793
telemt_connections_bad_total 667629
telemt_connections_current 1037
telemt_connections_me_current 1037
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 259023
telemt_upstream_connect_attempt_total 54144
telemt_upstream_connect_success_total 51348
telemt_upstream_connect_fail_total 1892
telemt_upstream_connect_attempts_per_request{bucket="1"} 53240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6001
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1892
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7362
telemt_me_reconnect_success_total 1130
telemt_me_reader_eof_total 702
telemt_me_idle_close_by_peer_total 701
telemt_me_route_drop_no_conn_total 25272679
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9251849
telemt_me_endpoint_quarantine_total 375
telemt_me_single_endpoint_outage_enter_total 84
telemt_me_single_endpoint_outage_exit_total 84
telemt_me_single_endpoint_outage_reconnect_attempt_total 157
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 157
telemt_me_single_endpoint_shadow_rotate_total 420
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 45
telemt_desync_total 16031
telemt_desync_full_logged_total 4305
telemt_desync_suppressed_total 11726
telemt_desync_frames_bucket_total{bucket="1_2"} 3059
telemt_desync_frames_bucket_total{bucket="3_10"} 6479
telemt_desync_frames_bucket_total{bucket="gt_10"} 6493
telemt_pool_swap_total 54
telemt_pool_force_close_total 1836
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 467
telemt_me_draining_writers_reap_progress_total 15946
telemt_me_writer_removed_unexpected_total 1020
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2250
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14668
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1529
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14110
telemt_me_writer_teardown_success_total{mode="normal"} 16918
telemt_me_writer_teardown_noop_total 15965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32883
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.244153
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32883
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 467
telemt_me_refill_failed_total 332
telemt_me_writer_restored_same_endpoint_total 731
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 9277347
telemt_user_connections_current{user="hello"} 1037
telemt_user_octets_from_client{user="hello"} 86305050038 (80.38 GB)
telemt_user_octets_to_client{user="hello"} 583820745801 (543.73 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 182557.6 (50h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10931154
telemt_connections_bad_total 939429
telemt_connections_current 767
telemt_connections_me_current 767
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241368
telemt_upstream_connect_attempt_total 108621
telemt_upstream_connect_success_total 107494
telemt_upstream_connect_fail_total 955
telemt_upstream_connect_attempts_per_request{bucket="1"} 108449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41275
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 955
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72782
telemt_me_reconnect_success_total 2994
telemt_me_reader_eof_total 2686
telemt_me_idle_close_by_peer_total 2684
telemt_me_route_drop_no_conn_total 5250262
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8625562
telemt_me_endpoint_quarantine_total 1213
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1373
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_active_current 46
telemt_desync_total 46026
telemt_desync_full_logged_total 15753
telemt_desync_suppressed_total 30273
telemt_desync_frames_bucket_total{bucket="1_2"} 9343
telemt_desync_frames_bucket_total{bucket="3_10"} 17616
telemt_desync_frames_bucket_total{bucket="gt_10"} 19067
telemt_pool_swap_total 186
telemt_pool_force_close_total 5522
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 658
telemt_me_draining_writers_reap_progress_total 63590
telemt_me_writer_removed_unexpected_total 2717
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6624
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59716
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4773
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58068
telemt_me_writer_teardown_success_total{mode="normal"} 66340
telemt_me_writer_teardown_noop_total 63591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 129195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129931
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.196389
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129931
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 658
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2525
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8628626
telemt_user_connections_current{user="hello"} 767
telemt_user_octets_from_client{user="hello"} 194089054825 (180.76 GB)
telemt_user_octets_to_client{user="hello"} 3293993518864 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 119393.8 (33h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11605730
telemt_connections_bad_total 467042
telemt_connections_current 663
telemt_connections_me_current 663
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4750623
telemt_upstream_connect_attempt_total 56820
telemt_upstream_connect_success_total 56403
telemt_upstream_connect_fail_total 406
telemt_upstream_connect_attempts_per_request{bucket="1"} 56809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 406
telemt_me_reconnect_attempts_total 48740
telemt_me_reconnect_success_total 1755
telemt_me_reader_eof_total 1420
telemt_me_idle_close_by_peer_total 1419
telemt_me_route_drop_no_conn_total 4078560
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5579849
telemt_me_endpoint_quarantine_total 784
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 910
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31348
telemt_desync_full_logged_total 10682
telemt_desync_suppressed_total 20666
telemt_desync_frames_bucket_total{bucket="1_2"} 6223
telemt_desync_frames_bucket_total{bucket="3_10"} 12368
telemt_desync_frames_bucket_total{bucket="gt_10"} 12757
telemt_pool_swap_total 126
telemt_pool_force_close_total 3764
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 42712
telemt_me_writer_removed_unexpected_total 1473
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3613
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40613
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3323
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38948
telemt_me_writer_teardown_success_total{mode="normal"} 44226
telemt_me_writer_teardown_noop_total 42719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86945
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.644267
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86945
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 2730
telemt_me_writer_restored_same_endpoint_total 1559
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5572451
telemt_user_connections_current{user="hello"} 663
telemt_user_octets_from_client{user="hello"} 118763926664 (110.61 GB)
telemt_user_octets_to_client{user="hello"} 2154786322394 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 100364.5 (27h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1482275
telemt_connections_bad_total 36435
telemt_connections_current 519
telemt_connections_me_current 519
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29531
telemt_upstream_connect_attempt_total 46926
telemt_upstream_connect_success_total 46777
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 46898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 776
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2157
telemt_me_reconnect_success_total 875
telemt_me_reader_eof_total 855
telemt_me_idle_close_by_peer_total 855
telemt_me_route_drop_no_conn_total 509852
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1316128
telemt_me_endpoint_quarantine_total 813
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 829
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 8373
telemt_desync_full_logged_total 2515
telemt_desync_suppressed_total 5858
telemt_desync_frames_bucket_total{bucket="1_2"} 2146
telemt_desync_frames_bucket_total{bucket="3_10"} 3233
telemt_desync_frames_bucket_total{bucket="gt_10"} 2994
telemt_pool_swap_total 108
telemt_pool_force_close_total 2806
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 156
telemt_me_draining_writers_reap_progress_total 39412
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3094
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37180
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2718
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36606
telemt_me_writer_teardown_success_total{mode="normal"} 40274
telemt_me_writer_teardown_noop_total 39416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79690
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.067829
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79690
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 156
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 742
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 1311996
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 25652221913 (23.89 GB)
telemt_user_octets_to_client{user="hello"} 562087992051 (523.49 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 182562.1 (50h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13243408
telemt_connections_bad_total 1574075
telemt_connections_current 802
telemt_connections_me_current 802
telemt_handshake_timeouts_total 381953
telemt_upstream_connect_attempt_total 70390
telemt_upstream_connect_success_total 70049
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 70254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2790
telemt_me_reconnect_success_total 1414
telemt_me_reader_eof_total 1393
telemt_me_idle_close_by_peer_total 1393
telemt_me_route_drop_no_conn_total 4475994
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10007780
telemt_me_endpoint_quarantine_total 1261
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1373
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
telemt_desync_total 41810
telemt_desync_full_logged_total 13651
telemt_desync_suppressed_total 28159
telemt_desync_frames_bucket_total{bucket="1_2"} 10051
telemt_desync_frames_bucket_total{bucket="3_10"} 15379
telemt_desync_frames_bucket_total{bucket="gt_10"} 16380
telemt_pool_swap_total 202
telemt_pool_force_close_total 5475
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 669
telemt_me_draining_writers_reap_progress_total 63553
telemt_me_writer_removed_unexpected_total 1336
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5079
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59857
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5301
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58078
telemt_me_writer_teardown_success_total{mode="normal"} 64936
telemt_me_writer_teardown_noop_total 63555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128491
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.693713
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128491
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 669
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1239
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 9974529
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 194308585172 (180.96 GB)
telemt_user_octets_to_client{user="hello"} 4424202320700 (4.02 TB)
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 182558.8 (50h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11540005
telemt_connections_bad_total 1321040
telemt_connections_current 581
telemt_connections_me_current 581
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 306787
telemt_upstream_connect_attempt_total 96990
telemt_upstream_connect_success_total 96130
telemt_upstream_connect_fail_total 652
telemt_upstream_connect_attempts_per_request{bucket="1"} 96782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 652
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10148
telemt_me_reconnect_success_total 2486
telemt_me_reader_eof_total 2315
telemt_me_idle_close_by_peer_total 2314
telemt_me_seq_mismatch_total 89
telemt_me_route_drop_no_conn_total 5636430
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8911308
telemt_me_endpoint_quarantine_total 1429
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1376
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 45
telemt_desync_total 41534
telemt_desync_full_logged_total 13338
telemt_desync_suppressed_total 28196
telemt_desync_frames_bucket_total{bucket="1_2"} 10703
telemt_desync_frames_bucket_total{bucket="3_10"} 15275
telemt_desync_frames_bucket_total{bucket="gt_10"} 15556
telemt_pool_swap_total 192
telemt_pool_force_close_total 5267
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 63430
telemt_me_writer_removed_unexpected_total 2352
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6438
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59425
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58163
telemt_me_writer_teardown_success_total{mode="normal"} 65863
telemt_me_writer_teardown_noop_total 63435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129298
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.365678
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129298
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 396
telemt_me_writer_restored_same_endpoint_total 2011
telemt_me_writer_restored_fallback_total 123
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 8916668
telemt_user_connections_current{user="hello"} 581
telemt_user_octets_from_client{user="hello"} 157006196773 (146.22 GB)
telemt_user_octets_to_client{user="hello"} 3470480072271 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 60
```