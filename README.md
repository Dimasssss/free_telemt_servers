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

# Server Metrics 2026-03-23 05:15:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 115755.9 (32h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4039483
telemt_connections_bad_total 391766
telemt_connections_current 1843
telemt_connections_me_current 1843
telemt_handshake_timeouts_total 134483
telemt_upstream_connect_attempt_total 43090
telemt_upstream_connect_success_total 43089
telemt_upstream_connect_attempts_per_request{bucket="1"} 43089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 698
telemt_me_reconnect_attempts_total 1496
telemt_me_reconnect_success_total 677
telemt_me_reader_eof_total 697
telemt_me_idle_close_by_peer_total 697
telemt_me_route_drop_no_conn_total 3179477
telemt_me_route_drop_channel_closed_total 1295
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3299475
telemt_me_writer_pick_total{mode="p2c",result="full"} 18
telemt_me_endpoint_quarantine_total 824
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 907
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 13885
telemt_desync_full_logged_total 4423
telemt_desync_suppressed_total 9462
telemt_desync_frames_bucket_total{bucket="1_2"} 3605
telemt_desync_frames_bucket_total{bucket="3_10"} 5150
telemt_desync_frames_bucket_total{bucket="gt_10"} 5130
telemt_pool_swap_total 128
telemt_pool_force_close_total 3915
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 728
telemt_me_draining_writers_reap_progress_total 39477
telemt_me_writer_removed_unexpected_total 671
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2826
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36925
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3850
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35562
telemt_me_writer_teardown_success_total{mode="normal"} 39751
telemt_me_writer_teardown_noop_total 39490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79241
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 419.729913
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79241
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 728
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 607
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 3287189
telemt_user_connections_current{user="hello"} 1843
telemt_user_octets_from_client{user="hello"} 44838334800 (41.76 GB)
telemt_user_octets_to_client{user="hello"} 879521766084 (819.12 GB)
telemt_user_unique_ips_current{user="hello"} 633
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 129122.1 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4138161
telemt_connections_bad_total 384846
telemt_connections_current 511
telemt_connections_me_current 511
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 106576
telemt_upstream_connect_attempt_total 80641
telemt_upstream_connect_success_total 79672
telemt_upstream_connect_fail_total 861
telemt_upstream_connect_attempts_per_request{bucket="1"} 80533
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 861
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10932
telemt_me_reconnect_success_total 3899
telemt_me_reader_eof_total 3870
telemt_me_idle_close_by_peer_total 3870
telemt_me_route_drop_no_conn_total 3667137
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3280963
telemt_me_endpoint_quarantine_total 1056
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 55
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 55
telemt_me_single_endpoint_shadow_rotate_total 1019
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 13509
telemt_desync_full_logged_total 7614
telemt_desync_suppressed_total 5895
telemt_desync_frames_bucket_total{bucket="1_2"} 3081
telemt_desync_frames_bucket_total{bucket="3_10"} 5297
telemt_desync_frames_bucket_total{bucket="gt_10"} 5131
telemt_pool_swap_total 122
telemt_pool_force_close_total 3391
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 262
telemt_me_draining_writers_reap_progress_total 54124
telemt_me_writer_removed_unexpected_total 3790
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6852
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51104
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2909
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 482
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50733
telemt_me_writer_teardown_success_total{mode="normal"} 57956
telemt_me_writer_teardown_noop_total 54125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112081
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.942759
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112081
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 262
telemt_me_refill_failed_total 278
telemt_me_writer_restored_same_endpoint_total 3446
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 3295407
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 44322019195 (41.28 GB)
telemt_user_octets_to_client{user="hello"} 828209971497 (771.33 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 203982.0 (56h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16637254
telemt_connections_bad_total 1686365
telemt_connections_current 1473
telemt_connections_me_current 1473
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 406798
telemt_upstream_connect_attempt_total 91718
telemt_upstream_connect_success_total 91611
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 91628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45257
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1731
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3209
telemt_me_reconnect_success_total 1681
telemt_me_reader_eof_total 1639
telemt_me_idle_close_by_peer_total 1637
telemt_me_route_drop_no_conn_total 14107668
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13214607
telemt_me_endpoint_quarantine_total 1381
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1545
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 55109
telemt_desync_full_logged_total 17609
telemt_desync_suppressed_total 37500
telemt_desync_frames_bucket_total{bucket="1_2"} 12304
telemt_desync_frames_bucket_total{bucket="3_10"} 21581
telemt_desync_frames_bucket_total{bucket="gt_10"} 21224
telemt_pool_swap_total 221
telemt_pool_force_close_total 7095
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1100
telemt_me_draining_writers_reap_progress_total 70557
telemt_me_writer_removed_unexpected_total 1572
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5921
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65494
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6625
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63462
telemt_me_writer_teardown_success_total{mode="normal"} 71415
telemt_me_writer_teardown_noop_total 70611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142026
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.935685
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142026
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1100
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1459
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 13214470
telemt_user_connections_current{user="hello"} 1473
telemt_user_octets_from_client{user="hello"} 200006865773 (186.27 GB)
telemt_user_octets_to_client{user="hello"} 3584112138851 (3.26 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 605
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 203983.3 (56h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12154679
telemt_connections_bad_total 1289406
telemt_connections_current 1086
telemt_connections_me_current 1086
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 351790
telemt_upstream_connect_attempt_total 106060
telemt_upstream_connect_success_total 104648
telemt_upstream_connect_fail_total 899
telemt_upstream_connect_attempts_per_request{bucket="1"} 105547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 899
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4679
telemt_me_reconnect_success_total 2012
telemt_me_reader_eof_total 1873
telemt_me_idle_close_by_peer_total 1873
telemt_me_route_drop_no_conn_total 4606302
telemt_me_route_drop_channel_closed_total 504
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8990358
telemt_me_endpoint_quarantine_total 1392
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1563
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_me_writers_active_current 47
telemt_desync_total 39507
telemt_desync_full_logged_total 13312
telemt_desync_suppressed_total 26195
telemt_desync_frames_bucket_total{bucket="1_2"} 9798
telemt_desync_frames_bucket_total{bucket="3_10"} 15179
telemt_desync_frames_bucket_total{bucket="gt_10"} 14530
telemt_pool_swap_total 218
telemt_pool_force_close_total 6440
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 722
telemt_me_draining_writers_reap_progress_total 68613
telemt_me_writer_removed_unexpected_total 1904
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6018
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64361
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5928
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62173
telemt_me_writer_teardown_success_total{mode="normal"} 70379
telemt_me_writer_teardown_noop_total 68638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139017
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.682805
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139017
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 722
telemt_me_refill_failed_total 143
telemt_me_writer_restored_same_endpoint_total 1718
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8927935
telemt_user_connections_current{user="hello"} 1086
telemt_user_octets_from_client{user="hello"} 219766695564 (204.67 GB)
telemt_user_octets_to_client{user="hello"} 4025306256467 (3.66 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 448
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 203947.3 (56h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11299727
telemt_connections_bad_total 1033171
telemt_connections_current 1005
telemt_connections_me_current 1005
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 355361
telemt_upstream_connect_attempt_total 90477
telemt_upstream_connect_success_total 88901
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 89106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43748
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2068
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5886
telemt_me_reconnect_success_total 2472
telemt_me_reader_eof_total 2218
telemt_me_idle_close_by_peer_total 2217
telemt_me_route_drop_no_conn_total 5374695
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8498567
telemt_me_endpoint_quarantine_total 1442
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1524
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 72
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
telemt_desync_total 38651
telemt_desync_full_logged_total 12831
telemt_desync_suppressed_total 25820
telemt_desync_frames_bucket_total{bucket="1_2"} 9762
telemt_desync_frames_bucket_total{bucket="3_10"} 14800
telemt_desync_frames_bucket_total{bucket="gt_10"} 14089
telemt_pool_swap_total 214
telemt_pool_force_close_total 6328
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 762
telemt_me_draining_writers_reap_progress_total 69230
telemt_me_writer_removed_unexpected_total 2364
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6751
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64779
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5757
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62902
telemt_me_writer_teardown_success_total{mode="normal"} 71530
telemt_me_writer_teardown_noop_total 69301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 140350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140831
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.966937
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140831
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 762
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2153
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8490392
telemt_user_connections_current{user="hello"} 1005
telemt_user_octets_from_client{user="hello"} 194069655859 (180.74 GB)
telemt_user_octets_to_client{user="hello"} 3522938754289 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 74227.4 (20h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11625848
telemt_connections_bad_total 690943
telemt_connections_current 1795
telemt_connections_me_current 1795
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 313442
telemt_upstream_connect_attempt_total 67123
telemt_upstream_connect_success_total 63553
telemt_upstream_connect_fail_total 2312
telemt_upstream_connect_attempts_per_request{bucket="1"} 65865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22838
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2312
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8403
telemt_me_reconnect_success_total 1552
telemt_me_reader_eof_total 978
telemt_me_idle_close_by_peer_total 977
telemt_me_route_drop_no_conn_total 25365790
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9621319
telemt_me_endpoint_quarantine_total 580
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 213
telemt_me_single_endpoint_outage_reconnect_success_total 56
telemt_me_single_endpoint_quarantine_bypass_total 213
telemt_me_single_endpoint_shadow_rotate_total 598
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
telemt_me_writers_active_current 67
telemt_desync_total 17225
telemt_desync_full_logged_total 4789
telemt_desync_suppressed_total 12436
telemt_desync_frames_bucket_total{bucket="1_2"} 3333
telemt_desync_frames_bucket_total{bucket="3_10"} 7037
telemt_desync_frames_bucket_total{bucket="gt_10"} 6855
telemt_pool_swap_total 76
telemt_pool_force_close_total 2368
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 529
telemt_me_draining_writers_reap_progress_total 24554
telemt_me_writer_removed_unexpected_total 1435
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3208
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22733
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2042
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 326
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22186
telemt_me_writer_teardown_success_total{mode="normal"} 25941
telemt_me_writer_teardown_noop_total 24573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50514
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.845192
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50514
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 529
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 993
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 9648903
telemt_user_connections_current{user="hello"} 1795
telemt_user_octets_from_client{user="hello"} 90475403843 (84.26 GB)
telemt_user_octets_to_client{user="hello"} 714426447297 (665.36 GB)
telemt_user_msgs_from_client{user="hello"} 71666
telemt_user_msgs_to_client{user="hello"} 62721
telemt_user_unique_ips_current{user="hello"} 663
telemt_user_unique_ips_recent_window{user="hello"} 279
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 203954.0 (56h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11263459
telemt_connections_bad_total 991504
telemt_connections_current 1640
telemt_connections_me_current 1640
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 251278
telemt_upstream_connect_attempt_total 119395
telemt_upstream_connect_success_total 118153
telemt_upstream_connect_fail_total 1065
telemt_upstream_connect_attempts_per_request{bucket="1"} 119218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47222
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1377
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1065
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73523
telemt_me_reconnect_success_total 3255
telemt_me_reader_eof_total 2950
telemt_me_idle_close_by_peer_total 2947
telemt_me_route_drop_no_conn_total 5315062
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8867814
telemt_me_endpoint_quarantine_total 1387
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1552
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 47240
telemt_desync_full_logged_total 16238
telemt_desync_suppressed_total 31002
telemt_desync_frames_bucket_total{bucket="1_2"} 9603
telemt_desync_frames_bucket_total{bucket="3_10"} 18112
telemt_desync_frames_bucket_total{bucket="gt_10"} 19525
telemt_pool_swap_total 210
telemt_pool_force_close_total 6050
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 73290
telemt_me_writer_removed_unexpected_total 2967
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7299
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69005
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5301
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67240
telemt_me_writer_teardown_success_total{mode="normal"} 76304
telemt_me_writer_teardown_noop_total 73291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 147439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 148859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 149278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 149551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 149585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 149588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 149588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 149591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 149595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 149595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 149595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 149595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 149595
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.359622
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 149595
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 4322
telemt_me_writer_restored_same_endpoint_total 2740
telemt_me_writer_restored_fallback_total 56
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8870466
telemt_user_connections_current{user="hello"} 1640
telemt_user_octets_from_client{user="hello"} 198929354309 (185.27 GB)
telemt_user_octets_to_client{user="hello"} 3392783327844 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 595
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 140790.3 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12044193
telemt_connections_bad_total 493208
telemt_connections_current 1077
telemt_connections_me_current 1077
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4864018
telemt_upstream_connect_attempt_total 68361
telemt_upstream_connect_success_total 67872
telemt_upstream_connect_fail_total 476
telemt_upstream_connect_attempts_per_request{bucket="1"} 68348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 476
telemt_me_reconnect_attempts_total 49358
telemt_me_reconnect_success_total 1960
telemt_me_reader_eof_total 1644
telemt_me_idle_close_by_peer_total 1643
telemt_me_route_drop_no_conn_total 4138599
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5785052
telemt_me_endpoint_quarantine_total 975
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1087
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32518
telemt_desync_full_logged_total 11113
telemt_desync_suppressed_total 21405
telemt_desync_frames_bucket_total{bucket="1_2"} 6524
telemt_desync_frames_bucket_total{bucket="3_10"} 12813
telemt_desync_frames_bucket_total{bucket="gt_10"} 13181
telemt_pool_swap_total 150
telemt_pool_force_close_total 4240
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 393
telemt_me_draining_writers_reap_progress_total 53216
telemt_me_writer_removed_unexpected_total 1682
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4207
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50747
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48976
telemt_me_writer_teardown_success_total{mode="normal"} 54954
telemt_me_writer_teardown_noop_total 53223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108177
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.832707
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108177
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 393
telemt_me_refill_failed_total 2753
telemt_me_writer_restored_same_endpoint_total 1730
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5776916
telemt_user_connections_current{user="hello"} 1077
telemt_user_octets_from_client{user="hello"} 121606302720 (113.25 GB)
telemt_user_octets_to_client{user="hello"} 2249003554906 (2.05 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 422
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 121761.0 (33h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1679545
telemt_connections_bad_total 37294
telemt_connections_current 828
telemt_connections_me_current 828
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 35378
telemt_upstream_connect_attempt_total 57395
telemt_upstream_connect_success_total 57216
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 57367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 837
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2504
telemt_me_reconnect_success_total 1009
telemt_me_reader_eof_total 1005
telemt_me_idle_close_by_peer_total 1005
telemt_me_route_drop_no_conn_total 561502
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1492644
telemt_me_endpoint_quarantine_total 1036
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1004
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
telemt_desync_total 10295
telemt_desync_full_logged_total 2913
telemt_desync_suppressed_total 7382
telemt_desync_frames_bucket_total{bucket="1_2"} 3239
telemt_desync_frames_bucket_total{bucket="3_10"} 3870
telemt_desync_frames_bucket_total{bucket="gt_10"} 3186
telemt_pool_swap_total 132
telemt_pool_force_close_total 3332
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 178
telemt_me_draining_writers_reap_progress_total 48948
telemt_me_writer_removed_unexpected_total 968
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3698
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46262
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3244
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45616
telemt_me_writer_teardown_success_total{mode="normal"} 49960
telemt_me_writer_teardown_noop_total 48952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98912
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.683200
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98912
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 178
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 864
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1488212
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 27467597425 (25.58 GB)
telemt_user_octets_to_client{user="hello"} 612758957027 (570.68 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 203958.6 (56h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13545355
telemt_connections_bad_total 1635022
telemt_connections_current 1320
telemt_connections_me_current 1320
telemt_handshake_timeouts_total 396433
telemt_upstream_connect_attempt_total 82283
telemt_upstream_connect_success_total 81918
telemt_upstream_connect_fail_total 228
telemt_upstream_connect_attempts_per_request{bucket="1"} 82146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41282
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 228
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3226
telemt_me_reconnect_success_total 1621
telemt_me_reader_eof_total 1612
telemt_me_idle_close_by_peer_total 1612
telemt_me_route_drop_no_conn_total 4525940
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10214469
telemt_me_endpoint_quarantine_total 1510
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1551
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 42887
telemt_desync_full_logged_total 13991
telemt_desync_suppressed_total 28896
telemt_desync_frames_bucket_total{bucket="1_2"} 10450
telemt_desync_frames_bucket_total{bucket="3_10"} 15733
telemt_desync_frames_bucket_total{bucket="gt_10"} 16704
telemt_pool_swap_total 226
telemt_pool_force_close_total 5901
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 700
telemt_me_draining_writers_reap_progress_total 74476
telemt_me_writer_removed_unexpected_total 1542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5725
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70353
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5727
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68575
telemt_me_writer_teardown_success_total{mode="normal"} 76078
telemt_me_writer_teardown_noop_total 74478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 147915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 149664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 150423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 150543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 150556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 150556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 150556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 150556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 150556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 150556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 150556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 150556
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.985676
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 150556
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 700
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 1427
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 10180899
telemt_user_connections_current{user="hello"} 1320
telemt_user_octets_from_client{user="hello"} 196870948820 (183.35 GB)
telemt_user_octets_to_client{user="hello"} 4540300782804 (4.13 TB)
telemt_user_unique_ips_current{user="hello"} 485
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 203955.2 (56h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11863601
telemt_connections_bad_total 1386850
telemt_connections_current 1233
telemt_connections_me_current 1233
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 319602
telemt_upstream_connect_attempt_total 110109
telemt_upstream_connect_success_total 109162
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 109900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11074
telemt_me_reconnect_success_total 2759
telemt_me_reader_eof_total 2563
telemt_me_idle_close_by_peer_total 2562
telemt_me_seq_mismatch_total 107
telemt_me_route_drop_no_conn_total 5692751
telemt_me_route_drop_channel_closed_total 355
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9135211
telemt_me_endpoint_quarantine_total 1685
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1555
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42520
telemt_desync_full_logged_total 13683
telemt_desync_suppressed_total 28837
telemt_desync_frames_bucket_total{bucket="1_2"} 11047
telemt_desync_frames_bucket_total{bucket="3_10"} 15615
telemt_desync_frames_bucket_total{bucket="gt_10"} 15858
telemt_pool_swap_total 216
telemt_pool_force_close_total 5657
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 74796
telemt_me_writer_removed_unexpected_total 2598
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7134
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70361
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5186
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69139
telemt_me_writer_teardown_success_total{mode="normal"} 77495
telemt_me_writer_teardown_noop_total 74801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 149554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 151927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 152246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 152296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 152296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 152296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 152296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 152296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 152296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 152296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 152296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 152296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.833757
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 152296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 432
telemt_me_writer_restored_same_endpoint_total 2201
telemt_me_writer_restored_fallback_total 142
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 9139652
telemt_user_connections_current{user="hello"} 1233
telemt_user_octets_from_client{user="hello"} 159201314272 (148.27 GB)
telemt_user_octets_to_client{user="hello"} 3577975045662 (3.25 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 179
```