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

# Server Metrics 2026-03-22 23:13:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 94054.4 (26h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3371051
telemt_connections_bad_total 270375
telemt_connections_current 782
telemt_connections_me_current 782
telemt_handshake_timeouts_total 106665
telemt_upstream_connect_attempt_total 34634
telemt_upstream_connect_success_total 34633
telemt_upstream_connect_attempts_per_request{bucket="1"} 34633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1357
telemt_me_reconnect_success_total 565
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_route_drop_no_conn_total 2967352
telemt_me_route_drop_channel_closed_total 1230
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2814945
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 642
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 733
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 12015
telemt_desync_full_logged_total 3768
telemt_desync_suppressed_total 8247
telemt_desync_frames_bucket_total{bucket="1_2"} 3239
telemt_desync_frames_bucket_total{bucket="3_10"} 4387
telemt_desync_frames_bucket_total{bucket="gt_10"} 4389
telemt_pool_swap_total 104
telemt_pool_force_close_total 3227
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 636
telemt_me_draining_writers_reap_progress_total 31691
telemt_me_writer_removed_unexpected_total 561
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2312
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29608
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3171
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28464
telemt_me_writer_teardown_success_total{mode="normal"} 31920
telemt_me_writer_teardown_noop_total 31702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63622
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.873759
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63622
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 636
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 504
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2804234
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 40070608724 (37.32 GB)
telemt_user_octets_to_client{user="hello"} 762241731844 (709.89 GB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 107420.6 (29h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3963666
telemt_connections_bad_total 360631
telemt_connections_current 120
telemt_connections_me_current 120
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100042
telemt_upstream_connect_attempt_total 66496
telemt_upstream_connect_success_total 65690
telemt_upstream_connect_fail_total 714
telemt_upstream_connect_attempts_per_request{bucket="1"} 66404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 714
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9578
telemt_me_reconnect_success_total 3497
telemt_me_reader_eof_total 3504
telemt_me_idle_close_by_peer_total 3504
telemt_me_route_drop_no_conn_total 3636866
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3151867
telemt_me_endpoint_quarantine_total 815
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 833
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
telemt_me_writers_active_current 43
telemt_desync_total 12861
telemt_desync_full_logged_total 7204
telemt_desync_suppressed_total 5657
telemt_desync_frames_bucket_total{bucket="1_2"} 2911
telemt_desync_frames_bucket_total{bucket="3_10"} 5046
telemt_desync_frames_bucket_total{bucket="gt_10"} 4904
telemt_pool_swap_total 99
telemt_pool_force_close_total 2959
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 243
telemt_me_draining_writers_reap_progress_total 43309
telemt_me_writer_removed_unexpected_total 3439
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5923
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40853
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2501
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40350
telemt_me_writer_teardown_success_total{mode="normal"} 46776
telemt_me_writer_teardown_noop_total 43310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90086
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.533572
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90086
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 243
telemt_me_refill_failed_total 230
telemt_me_writer_restored_same_endpoint_total 3149
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 3164364
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 42786486338 (39.85 GB)
telemt_user_octets_to_client{user="hello"} 781931385668 (728.23 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 182280.5 (50h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16247389
telemt_connections_bad_total 1625817
telemt_connections_current 866
telemt_connections_me_current 866
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396462
telemt_upstream_connect_attempt_total 81118
telemt_upstream_connect_success_total 81018
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 81035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39342
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1704
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2921
telemt_me_reconnect_success_total 1519
telemt_me_reader_eof_total 1464
telemt_me_idle_close_by_peer_total 1462
telemt_me_route_drop_no_conn_total 14034641
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12912636
telemt_me_endpoint_quarantine_total 1180
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1365
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
telemt_desync_total 53367
telemt_desync_full_logged_total 16930
telemt_desync_suppressed_total 36437
telemt_desync_frames_bucket_total{bucket="1_2"} 11861
telemt_desync_frames_bucket_total{bucket="3_10"} 20784
telemt_desync_frames_bucket_total{bucket="gt_10"} 20722
telemt_pool_swap_total 197
telemt_pool_force_close_total 6555
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1049
telemt_me_draining_writers_reap_progress_total 60842
telemt_me_writer_removed_unexpected_total 1411
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5268
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56257
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6085
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54287
telemt_me_writer_teardown_success_total{mode="normal"} 61525
telemt_me_writer_teardown_noop_total 60895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122420
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.399446
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122420
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1049
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1312
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 12912847
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 190497615541 (177.41 GB)
telemt_user_octets_to_client{user="hello"} 3471848152687 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 182281.9 (50h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11793839
telemt_connections_bad_total 1216166
telemt_connections_current 666
telemt_connections_me_current 666
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344175
telemt_upstream_connect_attempt_total 95559
telemt_upstream_connect_success_total 94246
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 95111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3797
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4336
telemt_me_reconnect_success_total 1826
telemt_me_reader_eof_total 1688
telemt_me_idle_close_by_peer_total 1688
telemt_me_route_drop_no_conn_total 4546963
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8765633
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
telemt_me_adaptive_floor_target_writers_total 35
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
telemt_me_draining_writers_reap_progress_total 59172
telemt_me_writer_removed_unexpected_total 1722
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5389
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55357
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5408
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53252
telemt_me_writer_teardown_success_total{mode="normal"} 60746
telemt_me_writer_teardown_noop_total 59197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119943
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.278421
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119943
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1557
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8703442
telemt_user_connections_current{user="hello"} 666
telemt_user_octets_from_client{user="hello"} 217434585236 (202.50 GB)
telemt_user_octets_to_client{user="hello"} 3942718306083 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 182245.9 (50h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10989474
telemt_connections_bad_total 960225
telemt_connections_current 474
telemt_connections_me_current 474
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345099
telemt_upstream_connect_attempt_total 79654
telemt_upstream_connect_success_total 78102
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 78307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5667
telemt_me_reconnect_success_total 2314
telemt_me_reader_eof_total 2054
telemt_me_idle_close_by_peer_total 2053
telemt_me_route_drop_no_conn_total 5329022
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8315090
telemt_me_endpoint_quarantine_total 1269
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1343
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
telemt_me_writers_active_current 46
telemt_desync_total 37899
telemt_desync_full_logged_total 12568
telemt_desync_suppressed_total 25331
telemt_desync_frames_bucket_total{bucket="1_2"} 9571
telemt_desync_frames_bucket_total{bucket="3_10"} 14495
telemt_desync_frames_bucket_total{bucket="gt_10"} 13833
telemt_pool_swap_total 190
telemt_pool_force_close_total 5827
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 736
telemt_me_draining_writers_reap_progress_total 59336
telemt_me_writer_removed_unexpected_total 2208
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6116
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55356
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5256
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53509
telemt_me_writer_teardown_success_total{mode="normal"} 61472
telemt_me_writer_teardown_noop_total 59407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120879
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.648839
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120879
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 736
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2005
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8307086
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 192290333023 (179.08 GB)
telemt_user_octets_to_client{user="hello"} 3455597729033 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 52526.1 (14h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11133842
telemt_connections_bad_total 667595
telemt_connections_current 1045
telemt_connections_me_current 1045
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 258377
telemt_upstream_connect_attempt_total 54014
telemt_upstream_connect_success_total 51218
telemt_upstream_connect_fail_total 1892
telemt_upstream_connect_attempts_per_request{bucket="1"} 53110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5999
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1892
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7354
telemt_me_reconnect_success_total 1123
telemt_me_reader_eof_total 695
telemt_me_idle_close_by_peer_total 694
telemt_me_route_drop_no_conn_total 25271840
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9247789
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_outage_enter_total 84
telemt_me_single_endpoint_outage_exit_total 84
telemt_me_single_endpoint_outage_reconnect_attempt_total 157
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 157
telemt_me_single_endpoint_shadow_rotate_total 417
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
telemt_me_writers_active_current 44
telemt_desync_total 16005
telemt_desync_full_logged_total 4295
telemt_desync_suppressed_total 11710
telemt_desync_frames_bucket_total{bucket="1_2"} 3056
telemt_desync_frames_bucket_total{bucket="3_10"} 6470
telemt_desync_frames_bucket_total{bucket="gt_10"} 6479
telemt_pool_swap_total 54
telemt_pool_force_close_total 1836
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 467
telemt_me_draining_writers_reap_progress_total 15833
telemt_me_writer_removed_unexpected_total 1013
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2243
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14555
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1529
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13997
telemt_me_writer_teardown_success_total{mode="normal"} 16798
telemt_me_writer_teardown_noop_total 15852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32650
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.242007
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32650
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 467
telemt_me_refill_failed_total 332
telemt_me_writer_restored_same_endpoint_total 724
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 9273287
telemt_user_connections_current{user="hello"} 1045
telemt_user_octets_from_client{user="hello"} 86272440434 (80.35 GB)
telemt_user_octets_to_client{user="hello"} 582466708237 (542.46 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 182252.6 (50h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10925489
telemt_connections_bad_total 936595
telemt_connections_current 743
telemt_connections_me_current 743
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241076
telemt_upstream_connect_attempt_total 108472
telemt_upstream_connect_success_total 107345
telemt_upstream_connect_fail_total 955
telemt_upstream_connect_attempts_per_request{bucket="1"} 108300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41189
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 955
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72779
telemt_me_reconnect_success_total 2992
telemt_me_reader_eof_total 2684
telemt_me_idle_close_by_peer_total 2682
telemt_me_route_drop_no_conn_total 5249836
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8623160
telemt_me_endpoint_quarantine_total 1213
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1372
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
telemt_desync_total 46013
telemt_desync_full_logged_total 15749
telemt_desync_suppressed_total 30264
telemt_desync_frames_bucket_total{bucket="1_2"} 9337
telemt_desync_frames_bucket_total{bucket="3_10"} 17609
telemt_desync_frames_bucket_total{bucket="gt_10"} 19067
telemt_pool_swap_total 186
telemt_pool_force_close_total 5522
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 658
telemt_me_draining_writers_reap_progress_total 63458
telemt_me_writer_removed_unexpected_total 2715
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6620
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4773
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57936
telemt_me_writer_teardown_success_total{mode="normal"} 66206
telemt_me_writer_teardown_noop_total 63459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 127531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 129348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 129621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129665
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.195730
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129665
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 658
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2523
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8626224
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 194038739909 (180.71 GB)
telemt_user_octets_to_client{user="hello"} 3293594730052 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 119088.9 (33h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11598841
telemt_connections_bad_total 464139
telemt_connections_current 527
telemt_connections_me_current 527
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4749856
telemt_upstream_connect_attempt_total 56645
telemt_upstream_connect_success_total 56228
telemt_upstream_connect_fail_total 406
telemt_upstream_connect_attempts_per_request{bucket="1"} 56634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 406
telemt_me_reconnect_attempts_total 48740
telemt_me_reconnect_success_total 1755
telemt_me_reader_eof_total 1420
telemt_me_idle_close_by_peer_total 1419
telemt_me_route_drop_no_conn_total 4078256
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5577640
telemt_me_endpoint_quarantine_total 784
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 908
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31339
telemt_desync_full_logged_total 10677
telemt_desync_suppressed_total 20662
telemt_desync_frames_bucket_total{bucket="1_2"} 6222
telemt_desync_frames_bucket_total{bucket="3_10"} 12364
telemt_desync_frames_bucket_total{bucket="gt_10"} 12753
telemt_pool_swap_total 126
telemt_pool_force_close_total 3764
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 42539
telemt_me_writer_removed_unexpected_total 1473
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3612
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40441
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3323
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38775
telemt_me_writer_teardown_success_total{mode="normal"} 44053
telemt_me_writer_teardown_noop_total 42546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86599
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.643597
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86599
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 2730
telemt_me_writer_restored_same_endpoint_total 1559
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5570242
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 118742319528 (110.59 GB)
telemt_user_octets_to_client{user="hello"} 2153301323470 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 100059.7 (27h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1479714
telemt_connections_bad_total 36424
telemt_connections_current 517
telemt_connections_me_current 517
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29491
telemt_upstream_connect_attempt_total 46790
telemt_upstream_connect_success_total 46641
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 46762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24712
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 776
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2155
telemt_me_reconnect_success_total 874
telemt_me_reader_eof_total 854
telemt_me_idle_close_by_peer_total 854
telemt_me_route_drop_no_conn_total 509562
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1313778
telemt_me_endpoint_quarantine_total 813
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 822
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
telemt_me_writers_active_current 43
telemt_desync_total 8346
telemt_desync_full_logged_total 2509
telemt_desync_suppressed_total 5837
telemt_desync_frames_bucket_total{bucket="1_2"} 2132
telemt_desync_frames_bucket_total{bucket="3_10"} 3226
telemt_desync_frames_bucket_total{bucket="gt_10"} 2988
telemt_pool_swap_total 108
telemt_pool_force_close_total 2783
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 154
telemt_me_draining_writers_reap_progress_total 39277
telemt_me_writer_removed_unexpected_total 826
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3084
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37054
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2695
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36494
telemt_me_writer_teardown_success_total{mode="normal"} 40138
telemt_me_writer_teardown_noop_total 39281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79419
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.038594
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79419
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 154
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 741
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 1309654
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 25641293321 (23.88 GB)
telemt_user_octets_to_client{user="hello"} 560679232399 (522.17 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 182257.2 (50h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13240494
telemt_connections_bad_total 1573541
telemt_connections_current 787
telemt_connections_me_current 787
telemt_handshake_timeouts_total 381575
telemt_upstream_connect_attempt_total 70246
telemt_upstream_connect_success_total 69905
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 70110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35162
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2790
telemt_me_reconnect_success_total 1414
telemt_me_reader_eof_total 1393
telemt_me_idle_close_by_peer_total 1393
telemt_me_route_drop_no_conn_total 4475584
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10005895
telemt_me_endpoint_quarantine_total 1261
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1372
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 41797
telemt_desync_full_logged_total 13646
telemt_desync_suppressed_total 28151
telemt_desync_frames_bucket_total{bucket="1_2"} 10042
telemt_desync_frames_bucket_total{bucket="3_10"} 15378
telemt_desync_frames_bucket_total{bucket="gt_10"} 16377
telemt_pool_swap_total 202
telemt_pool_force_close_total 5475
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 669
telemt_me_draining_writers_reap_progress_total 63409
telemt_me_writer_removed_unexpected_total 1336
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5075
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59717
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5301
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57934
telemt_me_writer_teardown_success_total{mode="normal"} 64792
telemt_me_writer_teardown_noop_total 63411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128203
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.692828
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128203
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 669
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1239
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 9972645
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 194293635824 (180.95 GB)
telemt_user_octets_to_client{user="hello"} 4422596779672 (4.02 TB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 182253.8 (50h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11536761
telemt_connections_bad_total 1320209
telemt_connections_current 589
telemt_connections_me_current 589
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 306768
telemt_upstream_connect_attempt_total 96829
telemt_upstream_connect_success_total 95969
telemt_upstream_connect_fail_total 652
telemt_upstream_connect_attempts_per_request{bucket="1"} 96621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40739
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 652
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10142
telemt_me_reconnect_success_total 2481
telemt_me_reader_eof_total 2310
telemt_me_idle_close_by_peer_total 2309
telemt_me_seq_mismatch_total 88
telemt_me_route_drop_no_conn_total 5636012
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8908984
telemt_me_endpoint_quarantine_total 1428
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
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 41526
telemt_desync_full_logged_total 13334
telemt_desync_suppressed_total 28192
telemt_desync_frames_bucket_total{bucket="1_2"} 10703
telemt_desync_frames_bucket_total{bucket="3_10"} 15272
telemt_desync_frames_bucket_total{bucket="gt_10"} 15551
telemt_pool_swap_total 192
telemt_pool_force_close_total 5267
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 63294
telemt_me_writer_removed_unexpected_total 2347
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6429
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59292
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 58027
telemt_me_writer_teardown_success_total{mode="normal"} 65721
telemt_me_writer_teardown_noop_total 63299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 129020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 129020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 129020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 129020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 129020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 129020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 129020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 129020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 129020
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.364345
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 129020
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 396
telemt_me_writer_restored_same_endpoint_total 2007
telemt_me_writer_restored_fallback_total 122
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 8914344
telemt_user_connections_current{user="hello"} 589
telemt_user_octets_from_client{user="hello"} 156997387129 (146.22 GB)
telemt_user_octets_to_client{user="hello"} 3469650910095 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 63
```