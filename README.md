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

# Server Metrics 2026-03-22 22:58:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 93139.2 (25h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3352878
telemt_connections_bad_total 265983
telemt_connections_current 863
telemt_connections_me_current 863
telemt_handshake_timeouts_total 105937
telemt_upstream_connect_attempt_total 34269
telemt_upstream_connect_success_total 34268
telemt_upstream_connect_attempts_per_request{bucket="1"} 34268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22329
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1350
telemt_me_reconnect_success_total 559
telemt_me_reader_eof_total 575
telemt_me_idle_close_by_peer_total 575
telemt_me_route_drop_no_conn_total 2965193
telemt_me_route_drop_channel_closed_total 1229
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2803513
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 636
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 728
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
telemt_desync_total 11962
telemt_desync_full_logged_total 3752
telemt_desync_suppressed_total 8210
telemt_desync_frames_bucket_total{bucket="1_2"} 3228
telemt_desync_frames_bucket_total{bucket="3_10"} 4370
telemt_desync_frames_bucket_total{bucket="gt_10"} 4364
telemt_pool_swap_total 103
telemt_pool_force_close_total 3200
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 633
telemt_me_draining_writers_reap_progress_total 31376
telemt_me_writer_removed_unexpected_total 555
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2288
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29311
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3144
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28176
telemt_me_writer_teardown_success_total{mode="normal"} 31599
telemt_me_writer_teardown_noop_total 31387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62986
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.826111
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62986
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 633
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 498
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2792810
telemt_user_connections_current{user="hello"} 863
telemt_user_octets_from_client{user="hello"} 39965803168 (37.22 GB)
telemt_user_octets_to_client{user="hello"} 758584185520 (706.49 GB)
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 106505.4 (29h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3958304
telemt_connections_bad_total 360614
telemt_connections_current 133
telemt_connections_me_current 133
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99910
telemt_upstream_connect_attempt_total 65091
telemt_upstream_connect_success_total 64294
telemt_upstream_connect_fail_total 705
telemt_upstream_connect_attempts_per_request{bucket="1"} 64999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 705
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9485
telemt_me_reconnect_success_total 3477
telemt_me_reader_eof_total 3488
telemt_me_idle_close_by_peer_total 3488
telemt_me_route_drop_no_conn_total 3636221
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3147690
telemt_me_endpoint_quarantine_total 803
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 824
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 12844
telemt_desync_full_logged_total 7194
telemt_desync_suppressed_total 5650
telemt_desync_frames_bucket_total{bucket="1_2"} 2907
telemt_desync_frames_bucket_total{bucket="3_10"} 5042
telemt_desync_frames_bucket_total{bucket="gt_10"} 4895
telemt_pool_swap_total 98
telemt_pool_force_close_total 2959
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 243
telemt_me_draining_writers_reap_progress_total 42844
telemt_me_writer_removed_unexpected_total 3424
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5871
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40424
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2501
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39885
telemt_me_writer_teardown_success_total{mode="normal"} 46295
telemt_me_writer_teardown_noop_total 42845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89140
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.526177
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89140
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 243
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 3137
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 3159295
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 42751549017 (39.82 GB)
telemt_user_octets_to_client{user="hello"} 780564218564 (726.96 GB)
telemt_user_msgs_from_client{user="hello"} 45221
telemt_user_msgs_to_client{user="hello"} 178309
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 181365.2 (50h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16232674
telemt_connections_bad_total 1620906
telemt_connections_current 915
telemt_connections_me_current 915
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396412
telemt_upstream_connect_attempt_total 80656
telemt_upstream_connect_success_total 80556
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 80573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1702
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2917
telemt_me_reconnect_success_total 1515
telemt_me_reader_eof_total 1460
telemt_me_idle_close_by_peer_total 1458
telemt_me_route_drop_no_conn_total 14032826
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12903149
telemt_me_endpoint_quarantine_total 1173
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1359
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
telemt_me_writers_active_current 50
telemt_desync_total 53347
telemt_desync_full_logged_total 16917
telemt_desync_suppressed_total 36430
telemt_desync_frames_bucket_total{bucket="1_2"} 11858
telemt_desync_frames_bucket_total{bucket="3_10"} 20771
telemt_desync_frames_bucket_total{bucket="gt_10"} 20718
telemt_pool_swap_total 196
telemt_pool_force_close_total 6531
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1048
telemt_me_draining_writers_reap_progress_total 60400
telemt_me_writer_removed_unexpected_total 1408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5244
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55835
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53869
telemt_me_writer_teardown_success_total{mode="normal"} 61079
telemt_me_writer_teardown_noop_total 60453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121532
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.383573
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121532
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1048
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1309
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 12903369
telemt_user_connections_current{user="hello"} 915
telemt_user_octets_from_client{user="hello"} 190123419389 (177.07 GB)
telemt_user_octets_to_client{user="hello"} 3467498715067 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 181366.6 (50h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11781341
telemt_connections_bad_total 1213072
telemt_connections_current 735
telemt_connections_me_current 735
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344039
telemt_upstream_connect_attempt_total 95096
telemt_upstream_connect_success_total 93784
telemt_upstream_connect_fail_total 864
telemt_upstream_connect_attempts_per_request{bucket="1"} 94648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3797
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 864
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4333
telemt_me_reconnect_success_total 1822
telemt_me_reader_eof_total 1683
telemt_me_idle_close_by_peer_total 1683
telemt_me_route_drop_no_conn_total 4545551
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8757881
telemt_me_endpoint_quarantine_total 1181
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1380
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 38617
telemt_desync_full_logged_total 12993
telemt_desync_suppressed_total 25624
telemt_desync_frames_bucket_total{bucket="1_2"} 9543
telemt_desync_frames_bucket_total{bucket="3_10"} 14843
telemt_desync_frames_bucket_total{bucket="gt_10"} 14231
telemt_pool_swap_total 193
telemt_pool_force_close_total 5899
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 58718
telemt_me_writer_removed_unexpected_total 1718
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5363
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54924
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52819
telemt_me_writer_teardown_success_total{mode="normal"} 60287
telemt_me_writer_teardown_noop_total 58743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119030
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.270900
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119030
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1554
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8695701
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 217381193752 (202.45 GB)
telemt_user_octets_to_client{user="hello"} 3939224790667 (3.58 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 181331.3 (50h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10978649
telemt_connections_bad_total 957901
telemt_connections_current 553
telemt_connections_me_current 553
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345062
telemt_upstream_connect_attempt_total 79190
telemt_upstream_connect_success_total 77644
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 77849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37411
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2004
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5653
telemt_me_reconnect_success_total 2302
telemt_me_reader_eof_total 2042
telemt_me_idle_close_by_peer_total 2041
telemt_me_route_drop_no_conn_total 5327865
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8308319
telemt_me_endpoint_quarantine_total 1261
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1335
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
telemt_desync_total 37898
telemt_desync_full_logged_total 12567
telemt_desync_suppressed_total 25331
telemt_desync_frames_bucket_total{bucket="1_2"} 9570
telemt_desync_frames_bucket_total{bucket="3_10"} 14495
telemt_desync_frames_bucket_total{bucket="gt_10"} 13833
telemt_pool_swap_total 189
telemt_pool_force_close_total 5809
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 736
telemt_me_draining_writers_reap_progress_total 58934
telemt_me_writer_removed_unexpected_total 2196
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6086
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54972
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53125
telemt_me_writer_teardown_success_total{mode="normal"} 61058
telemt_me_writer_teardown_noop_total 59005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120063
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.634630
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120063
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 736
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 1993
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8300321
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 192232717947 (179.03 GB)
telemt_user_octets_to_client{user="hello"} 3452533536597 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 51611.1 (14h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11117977
telemt_connections_bad_total 667324
telemt_connections_current 970
telemt_connections_me_current 970
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 256270
telemt_upstream_connect_attempt_total 53570
telemt_upstream_connect_success_total 50787
telemt_upstream_connect_fail_total 1891
telemt_upstream_connect_attempts_per_request{bucket="1"} 52678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16941
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5999
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1891
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7333
telemt_me_reconnect_success_total 1119
telemt_me_reader_eof_total 690
telemt_me_idle_close_by_peer_total 689
telemt_me_route_drop_no_conn_total 25269515
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9234813
telemt_me_endpoint_quarantine_total 366
telemt_me_single_endpoint_outage_enter_total 84
telemt_me_single_endpoint_outage_exit_total 84
telemt_me_single_endpoint_outage_reconnect_attempt_total 157
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 157
telemt_me_single_endpoint_shadow_rotate_total 410
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
telemt_desync_total 15914
telemt_desync_full_logged_total 4248
telemt_desync_suppressed_total 11666
telemt_desync_frames_bucket_total{bucket="1_2"} 3034
telemt_desync_frames_bucket_total{bucket="3_10"} 6429
telemt_desync_frames_bucket_total{bucket="gt_10"} 6451
telemt_pool_swap_total 53
telemt_pool_force_close_total 1815
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 464
telemt_me_draining_writers_reap_progress_total 15447
telemt_me_writer_removed_unexpected_total 1008
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2222
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14185
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1508
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13632
telemt_me_writer_teardown_success_total{mode="normal"} 16407
telemt_me_writer_teardown_noop_total 15466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31873
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.942880
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31873
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 464
telemt_me_refill_failed_total 331
telemt_me_writer_restored_same_endpoint_total 720
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 9260318
telemt_user_connections_current{user="hello"} 970
telemt_user_octets_from_client{user="hello"} 86143493822 (80.23 GB)
telemt_user_octets_to_client{user="hello"} 577546497181 (537.88 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 181337.4 (50h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10907367
telemt_connections_bad_total 928024
telemt_connections_current 821
telemt_connections_me_current 821
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 239898
telemt_upstream_connect_attempt_total 107949
telemt_upstream_connect_success_total 106823
telemt_upstream_connect_fail_total 954
telemt_upstream_connect_attempts_per_request{bucket="1"} 107777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40901
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 954
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72756
telemt_me_reconnect_success_total 2988
telemt_me_reader_eof_total 2680
telemt_me_idle_close_by_peer_total 2678
telemt_me_route_drop_no_conn_total 5248181
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8615433
telemt_me_endpoint_quarantine_total 1205
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1364
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
telemt_me_writers_active_current 44
telemt_desync_total 45992
telemt_desync_full_logged_total 15738
telemt_desync_suppressed_total 30254
telemt_desync_frames_bucket_total{bucket="1_2"} 9327
telemt_desync_frames_bucket_total{bucket="3_10"} 17603
telemt_desync_frames_bucket_total{bucket="gt_10"} 19062
telemt_pool_swap_total 185
telemt_pool_force_close_total 5503
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 656
telemt_me_draining_writers_reap_progress_total 62978
telemt_me_writer_removed_unexpected_total 2711
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6601
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59121
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4754
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57475
telemt_me_writer_teardown_success_total{mode="normal"} 65722
telemt_me_writer_teardown_noop_total 62979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128701
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.189240
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128701
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 656
telemt_me_refill_failed_total 4296
telemt_me_writer_restored_same_endpoint_total 2520
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8618498
telemt_user_connections_current{user="hello"} 821
telemt_user_octets_from_client{user="hello"} 193980614057 (180.66 GB)
telemt_user_octets_to_client{user="hello"} 3290538879180 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 377
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 118173.6 (32h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11583788
telemt_connections_bad_total 463569
telemt_connections_current 570
telemt_connections_me_current 570
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4746295
telemt_upstream_connect_attempt_total 56124
telemt_upstream_connect_success_total 55708
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 56113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_reconnect_attempts_total 48733
telemt_me_reconnect_success_total 1749
telemt_me_reader_eof_total 1414
telemt_me_idle_close_by_peer_total 1413
telemt_me_route_drop_no_conn_total 4076724
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5570458
telemt_me_endpoint_quarantine_total 775
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 900
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
telemt_desync_total 31308
telemt_desync_full_logged_total 10659
telemt_desync_suppressed_total 20649
telemt_desync_frames_bucket_total{bucket="1_2"} 6215
telemt_desync_frames_bucket_total{bucket="3_10"} 12355
telemt_desync_frames_bucket_total{bucket="gt_10"} 12738
telemt_pool_swap_total 125
telemt_pool_force_close_total 3746
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 42050
telemt_me_writer_removed_unexpected_total 1467
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3584
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39974
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3305
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38304
telemt_me_writer_teardown_success_total{mode="normal"} 43558
telemt_me_writer_teardown_noop_total 42057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85615
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.640408
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85615
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 2730
telemt_me_writer_restored_same_endpoint_total 1553
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5563067
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 118687810516 (110.54 GB)
telemt_user_octets_to_client{user="hello"} 2151204792066 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 99144.3 (27h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1473666
telemt_connections_bad_total 36406
telemt_connections_current 504
telemt_connections_me_current 504
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29366
telemt_upstream_connect_attempt_total 46366
telemt_upstream_connect_success_total 46219
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 46338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 773
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2135
telemt_me_reconnect_success_total 871
telemt_me_reader_eof_total 851
telemt_me_idle_close_by_peer_total 851
telemt_me_route_drop_no_conn_total 507768
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1308100
telemt_me_endpoint_quarantine_total 804
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 814
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
telemt_me_writers_active_current 42
telemt_desync_total 8277
telemt_desync_full_logged_total 2496
telemt_desync_suppressed_total 5781
telemt_desync_frames_bucket_total{bucket="1_2"} 2088
telemt_desync_frames_bucket_total{bucket="3_10"} 3201
telemt_desync_frames_bucket_total{bucket="gt_10"} 2988
telemt_pool_swap_total 107
telemt_pool_force_close_total 2757
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 38879
telemt_me_writer_removed_unexpected_total 823
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3057
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36680
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2669
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36122
telemt_me_writer_teardown_success_total{mode="normal"} 39737
telemt_me_writer_teardown_noop_total 38883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78620
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.022060
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78620
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 739
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 1303983
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 25578095513 (23.82 GB)
telemt_user_octets_to_client{user="hello"} 557255309027 (518.98 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 181341.9 (50h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13230299
telemt_connections_bad_total 1570663
telemt_connections_current 820
telemt_connections_me_current 820
telemt_handshake_timeouts_total 380893
telemt_upstream_connect_attempt_total 69704
telemt_upstream_connect_success_total 69363
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 69568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2733
telemt_me_reconnect_success_total 1405
telemt_me_reader_eof_total 1381
telemt_me_idle_close_by_peer_total 1381
telemt_me_route_drop_no_conn_total 4474310
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9999916
telemt_me_endpoint_quarantine_total 1250
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1365
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 41787
telemt_desync_full_logged_total 13640
telemt_desync_suppressed_total 28147
telemt_desync_frames_bucket_total{bucket="1_2"} 10039
telemt_desync_frames_bucket_total{bucket="3_10"} 15375
telemt_desync_frames_bucket_total{bucket="gt_10"} 16373
telemt_pool_swap_total 201
telemt_pool_force_close_total 5456
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 667
telemt_me_draining_writers_reap_progress_total 62916
telemt_me_writer_removed_unexpected_total 1325
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5051
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59236
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5282
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57460
telemt_me_writer_teardown_success_total{mode="normal"} 64287
telemt_me_writer_teardown_noop_total 62918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127205
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.626615
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127205
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 667
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 1231
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 9966675
telemt_user_connections_current{user="hello"} 820
telemt_user_octets_from_client{user="hello"} 194238154516 (180.90 GB)
telemt_user_octets_to_client{user="hello"} 4418309331972 (4.02 TB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 181338.6 (50h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11527586
telemt_connections_bad_total 1318409
telemt_connections_current 593
telemt_connections_me_current 593
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 306199
telemt_upstream_connect_attempt_total 96298
telemt_upstream_connect_success_total 95440
telemt_upstream_connect_fail_total 651
telemt_upstream_connect_attempts_per_request{bucket="1"} 96091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 651
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10136
telemt_me_reconnect_success_total 2476
telemt_me_reader_eof_total 2305
telemt_me_idle_close_by_peer_total 2304
telemt_me_seq_mismatch_total 88
telemt_me_route_drop_no_conn_total 5634534
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8902507
telemt_me_endpoint_quarantine_total 1420
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1368
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
telemt_me_writers_active_current 48
telemt_desync_total 41471
telemt_desync_full_logged_total 13308
telemt_desync_suppressed_total 28163
telemt_desync_frames_bucket_total{bucket="1_2"} 10674
telemt_desync_frames_bucket_total{bucket="3_10"} 15255
telemt_desync_frames_bucket_total{bucket="gt_10"} 15542
telemt_pool_swap_total 191
telemt_pool_force_close_total 5250
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 653
telemt_me_draining_writers_reap_progress_total 62780
telemt_me_writer_removed_unexpected_total 2342
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6407
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58795
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4779
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57530
telemt_me_writer_teardown_success_total{mode="normal"} 65202
telemt_me_writer_teardown_noop_total 62785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127987
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.356413
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127987
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 653
telemt_me_refill_failed_total 396
telemt_me_writer_restored_same_endpoint_total 2002
telemt_me_writer_restored_fallback_total 122
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 8907886
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 156939772685 (146.16 GB)
telemt_user_octets_to_client{user="hello"} 3467661638047 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 52
```